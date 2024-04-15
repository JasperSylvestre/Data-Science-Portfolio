# data-science-portfolio

## About Me

I am Jasper Sylvestre, a North Carolina State University (NCSU) alumni (graduated Winter 2023) with a B.S. in Statistics and a Minor in Mathematics, an aspiring data scientist, and current software developer working with training LLMs. I am passionate about machine learning, deep learning, and AI with regards to data science. I hope to enter graduate school with a focus on data science, applied statistics, and machine learning in the coming Fall semester. This repository showcases different projects with analysis related to data science.

## Projects

### Exploratory Data Analysis of Road Accidents ([road-accidents-eda](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/road-accidents-eda)) [[notebook](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/road-accidents-eda/notebooks/road-accident-eda-notebook.ipynb)]

This Jupyter notebook explores road accident data through exploratory data analysis (EDA), data cleaning, and modeling implications. The dataset used for this analysis can be found in the corresponding data folder. For detailed insights through EDA, refer to the notebooks folder. For visualizations, refer to the image folder. This analysis demonstrates the importance of data preproccessing, explorary data analysis, and thoughtful model approaches in extracting insights from complex data sets. Further research, model exploration, and analysis could lead to valuable insights about this data, potentially for reducing road accident death, improving road safety measures, and improving road design

### NLP Disaster Tweets Analysis ([nlp-disaster-tweets](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/nlp-disaster-tweets)) [[notebook](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/nlp-disaster-tweets/notebooks/nlp-disaster-tweets-notebook.ipynb)]

This Jupyter notebook showcases NLP techniques and models BiLSTM architecture using data available on Kaggle, which can be found in the corresponding data folder. For detailed insights into data preprocessing and the modeling process, refer to the corresponding notebooks folder. Visualizations related to this project are available in the corresponding image folder. The final submission CSV file may be influenced by randomness when run on your machine, but using the saved file in this repository will yield an F1 score of 0.79037. Improved results can be achieved, especially when employing transfer models like BERT, aiming for scores between 0.80 to 0.85.

### Medical Error Prediction ([medical-error-prediction](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/medical-error-prediction))

This project aims to predict broad categories of medical errors using machine learning techniques, specifically employing Random Forest classification and Latent Semantic Analysis (LSA). It is a refinement of a project previously conducted at NCSU for ST 495 instructed by Srijan Sengupta during the Fall of 2023. The original project was a collaborative effort with team members: myself, Laylani Callaway, Casey Devine, Tyler March, and Lucy Liu. The final result shows that the Random Forest model has a classification error rate between 5.7 and 9.0% with 95% confidence, and the model using LSA data performed statistically significantly worse than the model not using LSA data.

### Telecom Churn Prediction ([telecom-churn-prediction](https://github.com/JasperSylvestre/data-science-portfolio/tree/main/telecom-churn-prediction)) [[notebook](https://nbviewer.org/github/JasperSylvestre/data-science-portfolio/blob/main/telecom-churn-prediction/notebooks/telecom-churn-prediction-notebook.ipynb)]

This Jupyter notebook explores customer churn prediction with XGBoost utilizing telecom data provided by Kaggle. It goes you through a meticulous data preparation pipeline, addressing cleaning, preprocessing, and feature engineering. The notebook then dives into training and optimizing an XGBoost model with techniques like randomized search and stratified sampling to handle class imbalance. The resulting model achieves a promising AUC of 0.91 on unseen data, but the notebook goes further by discussing strategies for ongoing modeling improvement, making it a valuable resource for anyone building churn prediction models in the telecom industry.
