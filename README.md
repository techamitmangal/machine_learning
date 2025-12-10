# Machine Learning Projects

This workspace contains various machine learning projects and experiments.

## Shared Environment Setup

All projects in this workspace share a common virtual environment and dependencies.

### Prerequisites
- Python 3.12 or higher
- VS Code with Jupyter extension installed
- uv package manager

### Setup
1. **Create venv:** `uv venv`
2. **Activate environment:** `source .venv/bin/activate`
3. **Install dependencies:** `uv sync`
4. **Register Jupyter kernel:** `python -m ipykernel install --user --name machine-learning-workspace --display-name "Machine Learning (Python 3.12)"`

### Managing Dependencies
- **Add new package:** `uv add package-name`
- **Remove package:** `uv remove package-name`
- **Update all:** `uv sync --upgrade`

## Projects

### Simple Linear Regression
A basic linear regression implementation using scikit-learn.

**Location:** `simple_linear_regression/`

**Quick Start:**
1. `cd simple_linear_regression`
2. Open `main.ipynb` in VS Code
3. Execute all cells

**Features:**
- Sample data generation
- Model training and evaluation
- Visualization of results

## Adding New Projects

1. Create a new folder for your project
2. Add project-specific files
3. Update this README with project information
4. Use the shared `.venv` and `requirements.txt` for dependencies