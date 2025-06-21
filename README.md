# Bachelor Thesis Project

## Developing a Bayesian network for risk stratification in lung cancer patients

This repository contains two Jupyter Notebooks that perform data exploration and build a dynamic Bayesian network (DBN) model for predicting lung cancer recurrence.

## Repository Structure

```
.
├── initial_analysis.ipynb   # Exploratory Data Analysis notebook
├── model.ipynb              # Dynamic Bayesian Network model training and evaluation
└── README.md                # Project overview and instructions
```

## 📘 Notebooks

### 1. `initial_analysis.ipynb`

This notebook includes:

- Data loading and preprocessing
- Visualising distributions
- Initial correlation analysis

### 2. `model.ipynb`

This notebook includes:

- Data loading
- Creating a Dynamic Bayesian Network
- Visualising the model as a graph
- Data preprocessing
- Train/Test split
- Training the model
- Running inference on the trained model
- Evaluation using accuracy, confusion matrices, and CPD tables

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/IvaylaSt/thesis.git
cd thesis
```

### 2. Install Required Packages

```bash
pip install numpy pandas pyreadstat networkx matplotlib pgmpy scikit-learn seaborn
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open `initial_analysis.ipynb` or `model.ipynb` to begin.

## Author

This thesis project was developed by Ivayla Stefanova. All code is created for the project. The data is privacy-protected and cannot be shared.
