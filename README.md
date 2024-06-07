**Project Overview
**This repository contains the notebook for our final project in the CSCI200 Machine Learning course. Our project is centered around the Ames, Iowa housing dataset, with the primary goal of approximating the sale prices of houses based on various features.

Ames is located about 30 miles north of Des Moines in central Iowa, and is notably home to Iowa State University, which excels in agriculture, design, engineering, and veterinary medicine.

**Data Source
Ames Housing Dataset

**Project Structure
**

**Libraries Used
**

pandas
numpy
seaborn
matplotlib
plotly.express
sklearn
Initial Setup


**We begin our EDA by examining the first few rows of the dataset and exploring summary statistics for our numerical variables:
**

Summary statistics are calculated to provide insights into the distribution and range of numerical features such as 'Year Built', 'Sale Price', and 'Total Basement SF'.

**Visualization
**
We conduct a series of visualizations to analyze relationships between house features and sale prices, including histograms and scatter plots to show distribution of prices by neighborhood and the impact of house age on pricing.

**Data Cleaning
**
Normalization of numerical variables and one-hot encoding of categorical variables are performed to prepare the data for modeling.

**Model Selection
**
We evaluate several models:

Linear Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
XGBoost

# Example of setting up a KNN model
knn = KNN(n_neighbors=5)

**Model Training
**
A pipeline is used to streamline the training process, and GridSearchCV is utilized to tune model parameters.

**Model Evaluation
**
The performance of each model is assessed using R² and RMSE metrics. Results are documented to compare the effectiveness of different modeling approaches.

**Conclusion
**
The project concludes with an overview of key findings and reflections on the modeling process, highlighting the importance of detailed workflow planning and parameter tuning.

