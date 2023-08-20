# Churn Prediction

## Overview
This project demonstrates the process of building a churn prediction model using machine learning techniques. Churn prediction is the task of identifying customers who are likely to stop using a service, which is crucial for customer retention efforts. The project involves data preprocessing, hyperparameter tuning, model evaluation, and generating predictions on a new dataset.

## Table of Contents
- [Getting Started](#getting-started)
- [Data](#data)
- [Code Usage](#code-usage)
- [Results](#results)
- [Author](#author)

## Getting Started
To get started with this project, you will need the following:
- Python 3.x
- Jupyter Notebook or any code editor

## Data
The dataset used in this project contains information about customer attributes and whether they have churned (1) or not (0). The features include demographics, service usage, contract details, payment method, and more. The dataset is used for both training models and generating predictions on new data.

## Code Usage
1. Clone the repository:
git clone https://github.com/imalexianne/churn-prediction.git

cd churn-prediction


2. Install the required packages (if not already installed):


3. Run the Jupyter Notebook or Python script to perform the following steps:
- Load and preprocess the dataset
- Split the data into training and testing sets
- Perform hyperparameter tuning for machine learning models
- Evaluate models using metrics like accuracy, recall, precision, and F1-score
- Train the chosen model (e.g., LightGBM) and make predictions on a new dataset

4. View the generated results, classification reports, and confusion matrices.

## Results
The project showcases the following results:
- Model evaluation metrics (accuracy, recall, precision, F1-score) for various models (e.g., K-Nearest Neighbors, Logistic Regression, Decision Trees, Support Vector Machines, LightGBM, Random Forest)
- Classification reports and confusion matrices for custom-trained models
- Generating predictions on a new dataset using the trained LightGBM model


## Workflow

Open this https://github.com/imalexianne/churn-prediction/blob/master/Classification.ipynb for further exploration.


## Setup
Install the required packages to be able to run the evaluation locally.

You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version lower than 3.10**). Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:


- Windows *(Python should be added to the Path variable of environment)*:
        
        python3 -m venv venv; venv\Scripts\activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.


[LinkedIn Article](https://www.linkedin.com/pulse/customer-churn-prediction-machine-learning-alexianne-imanirakarama)


[PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTA4MTJmMjMtNWU0OS00YmMwLTgyYTgtZmYzNGU2Y2RiMDk4IiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9)


## Author
- Alexianne Imanirakarama
- Contact: imalexianne@gmail.com
- [GitHub](https://github.com/imalexianne)


Feel free to reach out for any questions or feedback!
