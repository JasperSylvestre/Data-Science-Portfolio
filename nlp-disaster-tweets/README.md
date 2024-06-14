# data-science-portfolio / nlp-disaster-tweets

## About Me

Hi, I’m Jasper Sylvestre, a graduate student pursuing a Master of Applied Data Science (MADS) at UNC Chapel Hill. I completed my undergraduate studies at North Carolina State University, where I earned a B.S. in Statistics and a Minor in Mathematics. As an aspiring data scientist, I’m currently working as a software developer, focusing on training large language models (LLMs). My passion lies in data science, particularly machine learning, deep learning, and artificial intelligence.

Looking ahead, I plan to graduate in December 2025 from the MADS program, with a keen interest in data science, applied statistics, and machine learning. This repository showcases a project with analysis related to data science described below.

## Project: NLP Disaster Tweets

The notebook can be examined online for full feature access on [nbviewer](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/nlp-disaster-tweets/notebooks/nlp-disaster-tweets-notebook.ipynb).

This Jupyter Notebook showcases NLP and modeling BiLSTM architecture using data available on Kaggle. This notebook explored using a BiLSTM neural network and NLP to predict real disasters from tweets. The notebook employed data pre-processing, PyTorch model training with early stopping, and various evaluation metrics. While the model showed promise (strong AUC score), there is room for improvement through architecture exploration, hyperparameter tuning, and alternative techniques. Finally, the model was used to form a submission CSV file. The final submission CSV file may be slightly influenced by randomness when running the notebook on your machine. However, using this repository's current saved submission file will yield an F1 score of 0.79037. Significantly improved results can have been achieved to yield an F1 score of 80 to 85%, especially when employing transfer models like BERT.

## Files and Folders

* `data/`: Contains the CSV files containing the datasets examined in this notebook, including the submission CSV.
* `images/`: Saved plots formed in the notebook, such as the ROC curve of the chosen model performed on the validation dataset.
* `notebooks/`: The Jupyter notebook going over data inspection, data preprocessing, model training, evaluation, future model recommendations, and conclusions.
* `README.md`: This file.
* `acknowledgements.txt`: Contains acknowledgements for contributors, dataset providers, and important libraries.
* `requirements.txt`: Lists required Python packages and versions for running the code. Used for managing dependencies.
