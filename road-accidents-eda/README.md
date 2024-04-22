# data-science-portfolio / road-accidents-eda

## About Me

I am Jasper Sylvestre, a North Carolina State University alumni who graduated in Winter 2023 with a B.S. in Statistics and a Minor in Mathematics, an aspiring data scientist, and current software developer working with training LLMs. I am passionate about data science and especially machine learning, deep learning, and AI. I wish to enter graduate school focusing on data science, applied statistics, and machine learning in the Fall, 2024 semester. This repository showcases a project with analysis related to data science described below.

## Project: Road Accident Analysis - EDA

The notebook can be examined online for full feature access on [nbviewer](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/road-accidents-eda/notebooks/road-accident-eda-notebook.ipynb).

This Jupyter Notebook showcases NLP and modeling BiLSTM architecture using data available on [Kaggle](https://www.kaggle.com/datasets/farshidbahrami021/road-accident-dataset). This notebook explored using a BiLSTM neural network and NLP to predict real disasters from tweets. The notebook employed data pre-processing, PyTorch model training with early stopping, and various evaluation metrics. While the model showed promise (strong AUC score), there is room for improvement through architecture exploration, hyperparameter tuning, and alternative techniques. Finally, the model was used to form a submission CSV file. The final submission CSV file may be slightly influenced by randomness when running the notebook on your machine. However, using this repository's current saved submission file will yield an F1 score of 0.79037. Significantly improved results can have been achieved to yield an F1 score of 80 to 85%, especially when employing transfer models like BERT.

Note that this data was randomly generated and is purely for learning purposes, but we will treat it here as a real-world data set.

## Files and Folders

* `data/`: Contains the CSV files containing the dataset examined in this notebook.
* `images/`: Saved plots formed in the notebook, such as bar graphs for categorical variables, histograms for numeric variables, and a correlation matrix for numeric variables.
* `notebooks/`: The Jupyter notebook going over exploratory data analysis, modeling implications, and conclusions.
* `README.md`: This file.
* `acknowledgements.txt`: Contains acknowledgements for contributors, dataset providers, and important libraries.
* `requirements.txt`: Lists required Python packages and versions for running the code. Used for managing dependencies.
