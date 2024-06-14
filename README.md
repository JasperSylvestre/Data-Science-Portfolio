# data-science-portfolio

## About Me

Hi, I’m Jasper Sylvestre, a graduate student pursuing a Master of Applied Data Science (MADS) at UNC Chapel Hill. I completed my undergraduate studies at North Carolina State University, where I earned a B.S. in Statistics and a Minor in Mathematics. As an aspiring data scientist, I’m currently working as a software developer, focusing on training large language models (LLMs). My passion lies in data science, particularly machine learning, deep learning, and artificial intelligence.

Looking ahead, I plan to graduate in December 2025 from the MADS program, with a keen interest in data science, applied statistics, and machine learning. This repository showcases various projects where I’ve applied data science techniques and conducted in-depth analyses.

## Projects

### Exploratory Data Analysis of Road Accidents ([road-accidents-eda](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/road-accidents-eda)) [[notebook](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/road-accidents-eda/notebooks/road-accident-eda-notebook.ipynb)]

This Jupyter Notebook explores road accident data through exploratory data analysis (EDA) and data cleaning. This data set can be found on Kaggle. This analysis demonstrates the importance of data preprocessing, exploratory data analysis, and thoughtful model approaches in extracting insights from complex data sets. Further research, model exploration, and analysis could lead to valuable insights about this data, potentially for reducing road accident deaths, improving road safety measures, and improving road design.

### NLP Disaster Tweets Analysis ([nlp-disaster-tweets](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/nlp-disaster-tweets)) [[notebook](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/nlp-disaster-tweets/notebooks/nlp-disaster-tweets-notebook.ipynb)]

This Jupyter Notebook showcases NLP and modeling BiLSTM architecture using data available on Kaggle. This notebook explored using a BiLSTM neural network and NLP to predict real disasters from tweets. The notebook employed data pre-processing, PyTorch model training with early stopping, and various evaluation metrics. While the model showed promise (strong AUC score), there is room for improvement through architecture exploration, hyperparameter tuning, and alternative techniques. Finally, the model was used to form a submission CSV file. The final submission CSV file may be slightly influenced by randomness when running the notebook on your machine. However, using this repository's current saved submission file will yield an F1 score of 0.79037. Significantly improved results can have been achieved to yield an F1 score of 80 to 85%, especially when employing transfer models like BERT.

### Medical Error Prediction ([medical-error-prediction](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/medical-error-prediction))

This project aims to predict broad categories of medical errors using machine learning techniques, specifically employing Random Forest classification and Latent Semantic Analysis (LSA). It is a refinement of a project previously conducted at North Carolina State University for ST 495 instructed by Srijan Sengupta during the Fall of 2023. The original project was a collaborative effort with team members: myself, Laylani Callaway, Casey Devine, Tyler March, and Lucy Liu. The final result shows that the Random Forest model has a classification error rate between 5.7 and 9.0% with 95% confidence, and the model using LSA data performed statistically significantly worse than the model not using LSA data.

### Telecom Churn Prediction ([telecom-churn-prediction](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/telecom-churn-prediction)) [[notebook](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/telecom-churn-prediction/notebooks/telecom-churn-prediction-notebook.ipynb)]

This Jupyter Notebook explores customer churn prediction with XGBoost utilizing telecom data provided by Kaggle. It goes through a meticulous data preparation pipeline, addressing cleaning, preprocessing, and feature engineering. The notebook then dives into training and optimizing an XGBoost model with techniques like randomized search and stratified sampling to handle class imbalance. The resulting model achieves a promising AUC score of 0.91 on unseen data. The notebook further discusses strategies for ongoing modeling improvement, making it a valuable resource for anyone building churn prediction models in the telecom industry.
