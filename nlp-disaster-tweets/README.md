# data-science-portfolio / nlp-disaster-tweets

## About Me

I am Jasper Sylvestre, an NCSU alumni with a B.S. in Statistics and a Minor in Mathematics, an aspiring data scientist, and current software developer working with training LLMs. I am passionate about machine learning, deep learning, and AI with regards to data science. I hope to enter graduate school with a focus on data science, applied statistics, and machine learning in the coming semester or maybe next year. This repository showcases a project with analysis related to data science.

## Project: NLP Disaster Tweets

The notebook can be examined online for full feature access on [nbviewer](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/nlp-disaster-tweets/notebooks/nlp-disaster-tweets-notebook.ipynb).

This Jupyter notebook showcases NLP and modeling BiLSTM architecture using the data available on [Kaggle](https://www.kaggle.com/competitions/nlp-getting-started/data). This notebook explored using a BiLSTM neural network for NLP to predict real disasters from tweets. The notebook employed data pre-processing, PyTorch model training with early stopping, and various evaluation metrics. While the model showed promise (good AUC score), there's room for improvement through architecture exploration, hyperparameter tuning, and alternative techniques. Finally, the model was used to form a submission CSV file.

The final submission CSV file may be slightly influenced by randomness when running the notebook on your own machine, but using  the current saved file in this repository will yield an F1 score of 0.79037. Significantly improved results can be achieved to get a score of 80 to 85%, especially when employing transfer models like BERT.

## Files and Folders

* `data/`: Contains the CSV files containing the datasets examined in this notebook, including the submission CSV.
* `images/`: Saved plots formed in the notebook, such as the ROC curve of the chosen model performed on the validation dataset.
* `notebooks/`: The Jupyter notebook going over data inspection, data preprocessing, model training, evaluation, future model recommendations, and conclusions.
* `README.md`: This file.
* `acknowledgements.txt`: Contains acknowledgements for contributors, dataset providers, and important libraries.
* `requirements.txt`: Lists required Python packages and versions for running the code. Used for managing dependencies.
