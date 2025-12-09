# Machine Learning Projects

A collection of machine learning and data science projects exploring various predictive modeling techniques and real-world applications.

## Project Overview

This repository contains multiple machine learning projects focusing on data analysis, feature engineering, and predictive modeling. Each project applies different ML techniques to solve domain-specific problems, with an emphasis on F1 racing predictions and performance analysis.

## Project Contents

### F1 Predictions
- **`prediction8.py`** - Machine learning model for Formula 1 race outcome predictions
- **`Testing_push_to_git.py`** - Testing and validation framework for ML models

This section focuses on applying supervised learning techniques to historical F1 data, including data preprocessing, feature selection, model training, and performance evaluation.

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
