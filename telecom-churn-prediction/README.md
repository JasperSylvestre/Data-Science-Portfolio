# data-science-portfolio / telecom-churn-prediction

## About Me

Hi, I’m Jasper Sylvestre, a graduate student pursuing a Master of Applied Data Science (MADS) at UNC Chapel Hill. I completed my undergraduate studies at North Carolina State University, where I earned a B.S. in Statistics and a Minor in Mathematics. As an aspiring data scientist, I’m currently working as a software developer, focusing on training large language models (LLMs). My passion lies in data science, particularly machine learning, deep learning, and artificial intelligence.

Looking ahead, I plan to graduate in December 2025 from the MADS program, with a keen interest in data science, applied statistics, and machine learning. This repository showcases a project with analysis related to data science described below.

## Project: Telecom Churn Prediction

The notebook can be examined online for full feature access on [nbviewer](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/telecom-churn-prediction/notebooks/telecom-churn-prediction-notebook.ipynb).

This Jupyter Notebook explores customer churn prediction with XGBoost utilizing telecom data provided by [Kaggle](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets). It goes through a meticulous data preparation pipeline, addressing cleaning, preprocessing, and feature engineering. The notebook then dives into training and optimizing an XGBoost model with techniques like randomized search and stratified sampling to handle class imbalance. The resulting model achieves a promising AUC score of 0.91 on unseen data. The notebook further discusses strategies for ongoing modeling improvement, making it a valuable resource for anyone building churn prediction models in the telecom industry.

## Files and Folders

* `data/`: Contains the CSV files containing the datasets examined in this notebook.
* `images/`: Saved plots formed in the notebook, such as the ROC curve of the chosen XGBoost classification model performed on the testing dataset.
* `notebooks/`: The Jupyter notebook going over data inspection, data preprocessing, model training, evaluation, future model recommendations, and conclusions.
* `README.md`: This file.
* `acknowledgements.txt`: Contains acknowledgements for contributors, dataset providers, and important libraries.
* `requirements.txt`: Lists required Python packages and versions for running the code. Used for managing dependencies.
