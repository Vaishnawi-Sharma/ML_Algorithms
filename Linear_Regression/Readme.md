# Linear Regression on Boston Housing Dataset 

This repository contains a simple implementation of **Linear Regression** on the **Boston Housing dataset**.  
The goal is to predict median house prices based on features like crime rate, number of rooms, and pupil–teacher ratio.

---

## Files
- `linear_regression_boston.ipynb` → Jupyter Notebook with the implementation  
- `environment.yml` → Conda environment file with required dependencies  

---

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2.Create the environment:
```bash
conda env create -f environment.yml

3.Activate the environment:
```bash
conda activate <your-environment-name>

4.Launch Jupyter Notebook:
```bash
jupyter notebook


Then open linear_regression_boston.ipynb to run the code.

---

## Requirements

The notebook uses the following packages (all versions pinned in `environment.yml`):

- Python 3.9
- scikit-learn 1.1.3
- pandas 1.3.5
- numpy 1.21.6
- scipy 1.7.3
- matplotlib 3.5.1
- seaborn 0.13.2

---
## Note

- The Boston Housing dataset has been deprecated in newer versions of scikit-learn.
- This notebook works with scikit-learn 1.1.3 to ensure reproducibility.

