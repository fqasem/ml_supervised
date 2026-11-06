# Supervised Machine Learning Notes and Labs

This repository contains Jupyter notebooks, helper scripts, and exercises for the supervised learning portion of the Stanford Online Machine Learning Specialization. It focuses on foundational machine learning concepts and implementation using Python, NumPy, SciPy, Matplotlib, and scikit-learn.

## Contents

### Week 1: Linear Regression and Gradient Descent
- Linear regression fundamentals
- Cost function
- Gradient descent
- Model representation
- Python and Jupyter basics

### Week 2: Polynomial Regression, Feature Scaling, and Feature Engineering
- Multiple variable regression
- Feature scaling and learning rate considerations
- Polynomial regression
- Data preprocessing and engineering
- scikit-learn workflows

### Week 3: Logistic Regression and Regularization
- Binary classification
- Sigmoid function and decision boundaries
- Logistic loss and cost function
- Gradient descent for classification
- Overfitting and regularization

## Repository Structure

```text
Supervised/
├── README.md
├── requirements.txt
├── Week 1 - linear regression and Cost Function and Gradient Descent/
│   ├── C1_W1_Lab01_Python_Jupyter_Soln.ipynb
│   ├── C1_W1_Lab02_Model_Representation_Soln.ipynb
│   ├── C1_W1_Lab03_Cost_function_Soln.ipynb
│   ├── C1_W1_Lab04_Gradient_Descent_Soln.ipynb
│   ├── lab_utils_common.py
│   └── ...
├── Week 2 - polynomial regression and feature scale and engineering/
│   ├── C1_W2_Lab01_Python_Numpy_Vectorization_Soln.ipynb
│   ├── C1_W2_Lab02_Multiple_Variable_Soln.ipynb
│   ├── C1_W2_Lab03_Feature_Scaling_and_Learning_Rate_Soln.ipynb
│   ├── C1_W2_Lab04_FeatEng_PolyReg_Soln.ipynb
│   ├── lab_utils_common.py
│   └── ...
├── week 3 - classification with logistic regression and overfitting fix with regularization/
│   ├── C1_W3_Lab01_Classification_Soln.ipynb
│   ├── C1_W3_Lab02_Sigmoid_function_Soln.ipynb
│   ├── C1_W3_Lab03_Decision_Boundary_Soln.ipynb
│   ├── C1_W3_Lab04_LogisticLoss_Soln.ipynb
│   ├── C1_W3_Lab05_Cost_Function_Soln.ipynb
│   ├── C1_W3_Lab06_Gradient_Descent_Soln.ipynb
│   ├── C1_W3_Lab07_Scikit_Learn_Soln.ipynb
│   ├── C1_W3_Lab08_Overfitting_Soln.ipynb
│   ├── C1_W3_Lab09_Regularization_Soln.ipynb
│   └── ...
└── .venv/
```

## Setup

1. Create and activate a virtual environment:

```bash
python -m venv .venv
```

On Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Notebooks

Open the notebooks in Jupyter or VS Code and run them in order by week/topic. Many of the lab files include helper utilities in the same folder.

Example:

```bash
jupyter notebook
```

Then navigate to the desired week folder and open the notebook.

## Dependencies

The project uses:
- Python
- Jupyter Notebook / JupyterLab
- NumPy
- Matplotlib
- SciPy
- scikit-learn
- ipykernel and notebook support packages

## Notes

- This is a learning repository and is intended for educational exploration.
- Notebooks are organized by course week and are useful for studying and experimenting with core machine learning algorithms.
- The repository may include Coursera lab solutions and helper scripts that are meant to complement the coursework.


