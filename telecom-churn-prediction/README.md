# data-science-portfolio / telecom-churn-prediction

## About Me

I am Jasper Sylvestre, a North Carolina State University (NCSU) alumni (graduated Winter 2023) with a B.S. in Statistics and a Minor in Mathematics, an aspiring data scientist, and current software developer working with training LLMs. I am passionate about machine learning, deep learning, and AI with regards to data science. I hope to enter graduate school with a focus on data science, applied statistics, and machine learning in the coming Fall semester. This repository showcases a project with analysis related to data science described below.

## Project: Telecom Churn Prediction

The notebook can be examined online for full feature access on [nbviewer](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/telecom-churn-prediction/notebooks/telecom-churn-prediction-notebook.ipynb).

This Jupyter notebook explores customer churn prediction with XGBoost utilizing telecom data provided by [Kaggle](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets). It goes you through a meticulous data preparation pipeline, addressing cleaning, preprocessing, and feature engineering. The notebook then dives into training and optimizing an XGBoost model with techniques like randomized search and stratified sampling to handle class imbalance. The resulting model achieves a promising AUC of 0.91 on unseen data, but the notebook goes further by discussing strategies for ongoing modeling improvement, making it a valuable resource for anyone building churn prediction models in the telecom industry.

## Files and Folders

* `data/`: Contains the CSV files containing the datasets examined in this notebook.
* `images/`: Saved plots formed in the notebook, such as the ROC curve of the chosen XGBoost classification model performed on the testing dataset.
* `notebooks/`: The Jupyter notebook going over data inspection, data preprocessing, model training, evaluation, future model recommendations, and conclusions.
* `README.md`: This file.
* `acknowledgements.txt`: Contains acknowledgements for contributors, dataset providers, and important libraries.
* `requirements.txt`: Lists required Python packages and versions for running the code. Used for managing dependencies.
