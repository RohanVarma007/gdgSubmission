# Landslide Susceptibility Prediction — Chamoli District

Developed a machine learning model to predict the possibility of landslides in the **Chamoli district of Uttarakhand** using approximately **30,000 geospatial data points**.

The dataset contained geographical and terrain-related factors including **latitude, longitude, NDVI, aspect, curvature, elevation, plan curvature, profile curvature, slope, SPI, TRI, and TWI**, with the **Decision** column representing the target variable.

### Machine Learning Approach

* Cleaned and preprocessed the dataset by handling **null/missing values, invalid values, and physically unrealistic measurements**.
* Split the dataset into **70% training data and 30% testing data**.
* Trained two classification models:

  * **XGBoost**
  * **Random Forest**
* Used the input terrain/environmental factors as the model features (**X**) and the landslide decision as the target (**Y**).
* Compared the performance of both models and selected the model with the better test accuracy.
* Achieved approximately **90% accuracy** on the test dataset.

### Google Colab

[Open the Google Colab Notebook](https://colab.research.google.com/drive/1mAITlKiT8KNCTDYq2H8wKSXpk8AaorJo?authuser=1#scrollTo=smoiNTCN2riz)

### Key Learning

This project provided practical experience in the complete machine learning workflow, including **data collection, data cleaning, feature selection, model training, testing, model comparison, and evaluation**. It also helped develop a better understanding of how geographical and terrain characteristics can be used for landslide susceptibility analysis.
