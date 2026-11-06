**Wine Quality Prediction** 

Project Overview

This project uses machine learning to predict wine quality based on its physicochemical properties. A Random Forest Classifier is implemented to classify wine as either good or bad based on its quality score.

Dataset

The project uses the winequality.csv dataset.

The dataset contains physicochemical characteristics of wine, including:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

Target Variable: Wine Quality

Methodology

Data Collection

Load the dataset using Pandas.

Examine dataset statistics and missing values.

Exploratory Data Analysis (EDA)

Visualize wine quality distribution.

Analyse the relationship between volatile acidity, citric acid, and wine quality.

Perform correlation analysis using a heatmap.

Data Processing

Separate input features and target variable.

Apply label binarization:

Quality ≥ 7: Good Wine (1)

Quality < 7: Bad Wine (0)

Model Development

Split the dataset into training and testing sets (80:20).

Train a Random Forest Classifier.

Model Evaluation

Evaluate model performance using accuracy score.

Compare training and testing accuracy.

Prediction System

Accept physicochemical properties as input.

Predict whether the wine is good or bad.

Technologies Used

Python

Jupyter Notebook

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Repository Structure

Wine-Quality-Prediction/
│
├── Wine Quality Prediction.ipynb
├── winequality.csv
└── README.md

How to Run

1. Clone this repository.

2. Install the required Python libraries.

3. Place winequality.csv in the working directory.

4. Open the Jupyter Notebook.

5. Run the notebook cells to train the model and make predictions.

Objective

To explore the application of machine learning in wine quality classification using physicochemical properties and understand how a Random Forest Classifier can be used for predictive analysis.