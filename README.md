# Interpretable Machine Learning Approach for Breast Cancer Classification

Welcome to the official repository for the research paper *"Interpretable Machine Learning Approach for Breast Cancer Classification"* by Ahmad Tijjani Garba and Hafsah Shuaibu Hamza, submitted to the *Human Centric Intelligent Systems Journal* (Springer). This project explores the use of interpretable machine learning models for breast cancer classification, with a focus on Logistic Regression, Decision Trees, Random Forest, and CatBoost, enhanced by Local Interpretable Model-Agnostic Explanations (LIME).

## Project Overview

Breast cancer remains a critical global health challenge, necessitating reliable and interpretable diagnostic tools. This study evaluates multiple machine learning models on two datasets—Wisconsin Breast Cancer Dataset (WBDC) and Coimbra Breast Cancer Dataset—to classify breast cancer cases. Key performance metrics (e.g., Accuracy, Precision, Recall, F1 Score) are analyzed, and LIME is employed to provide interpretability, addressing the "black-box" problem in AI-based medical diagnostics. Logistic Regression emerged as the top performer, achieving accuracies of 0.97 (WBDC) and 0.84 (Coimbra).

## Repository Contents

- **`code/`**: Python scripts and Jupyter notebooks for data preprocessing, model training, evaluation, and LIME explanations.
- **`data/`**: Placeholder directory for datasets (not uploaded due to size; see "Datasets" section for links).
- **`results/`**: Model performance metrics, plots, and LIME explanation outputs.
- **`docs/`**: Supplementary materials, including the manuscript draft (if applicable) and this README.
- **`requirements.txt`**: List of Python dependencies required to run the code.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- Git (for cloning the repository)
- Required libraries (see `requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kano-analyst/breast-cancer-research.git
   cd BreastCancerClassification# breast-cancer-research
2.Install Dependecies
 ```bash
   pip install -r requirements.txt=
Download the datasets (see "Datasets" section) and place them in the data/ folder.
Running the Code
Open the Jupyter notebook or Python script in the code/ directory (e.g., breast_cancer_classification.ipynb).
Follow the instructions within to preprocess data, train models, and generate results.
Datasets
This study uses two publicly available datasets:

Wisconsin Breast Cancer Dataset (WBDC)
Source: UCI Machine Learning Repository
Description: Diagnostic data with 569 instances and 32 features.
Coimbra Breast Cancer Dataset
Source: UCI Machine Learning Repository
Description: Clinical data with 116 instances and 10 features.
Note: Due to GitHub size limits, datasets are not included in this repository. Please download them from the links above and place them in the data/ directory.

Usage
Preprocessing: Scripts clean and prepare the datasets for model training.
Model Training: Train Logistic Regression, Decision Trees, Random Forest, and CatBoost models.
Evaluation: Assess models using metrics like Accuracy, Precision, and RMSE.
Interpretability: Use LIME to generate explanations for model predictions (see results/ for outputs).
Example command to run the main script (if applicable):
