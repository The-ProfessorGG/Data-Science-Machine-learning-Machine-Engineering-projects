# F1 Predictions

Machine learning project for predicting Formula 1 race outcomes and performance metrics.

## Project Overview

This repository contains data analysis and machine learning models focused on Formula 1 racing predictions. The project explores historical F1 data to build predictive models for race results and driver/team performance.

## Files

- **`prediction8.py`** - Main prediction model implementation
- **`Testing_push_to_git.py`** - Testing and validation scripts

## Setup

### Requirements

- Python 3.8+
- Required packages (install via pip):
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

### Virtual Environment (Optional)

Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\Activate.ps1  # Windows PowerShell
# or
venv\Scripts\activate.bat  # Windows Command Prompt
```

## Usage

Run the main prediction model:

```bash
python prediction8.py
```

Run tests:

```bash
python Testing_push_to_git.py
```

## Project Structure

```
F1 Predictions/
├── README.md
├── .gitignore
├── prediction8.py
├── Testing_push_to_git.py
└── venv/  (virtual environment, ignored by git)
```

## Git Workflow

After making changes:

```bash
git add .
git commit -m "Describe your changes"
git push
```

## Author

Gareth Grant (garethgrantza@gmail.com)

## Notes

- Data files (`.csv`, `.db`) are ignored by `.gitignore`
- Jupyter notebooks (`.ipynb`) are ignored to keep repo clean
- Virtual environments are automatically excluded from version control
