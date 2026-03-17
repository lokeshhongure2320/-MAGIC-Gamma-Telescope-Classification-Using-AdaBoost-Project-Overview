🔭 MAGIC Gamma Telescope Classification Using AdaBoost
📌 Project Overview

This project focuses on classifying high-energy particle signals using the AdaBoost (Adaptive Boosting) algorithm. The dataset is collected from the MAGIC (Major Atmospheric Gamma Imaging Cherenkov) Telescope, which is used in astrophysics to detect gamma rays from cosmic sources.

The main objective is to build a machine learning model that can accurately distinguish between gamma particles and hadron particles based on telescope signal features.

This is a binary classification problem.

📊 Dataset

This project uses the:

MAGIC Gamma Telescope Dataset

Dataset Features

The dataset includes various numerical features extracted from telescope images:

fLength – Major axis length

fWidth – Minor axis length

fSize – Log of total light content

fConc – Light concentration in brightest pixels

fConc1 – Concentration of the brightest pixel

fAsym – Distance between image center and brightest pixel

fM3Long – Third moment along major axis

fM3Trans – Third moment along minor axis

fAlpha – Angle between shower axis and telescope axis

fDist – Distance from camera center

class – Target variable (gamma / hadron)

🎯 Objective

Perform data preprocessing and cleaning

Analyze dataset using EDA techniques

Apply AdaBoost classification algorithm

Evaluate model performance

🔍 Exploratory Data Analysis (EDA)

EDA steps performed:

Checked dataset structure and statistics

Visualized feature distributions

Analyzed correlations using heatmaps

Identified patterns between gamma and hadron signals

⚙️ Data Preprocessing

Converted categorical labels into numeric format

Split dataset into training and testing sets

Applied feature scaling (if required)

🚀 AdaBoost Algorithm

AdaBoost (Adaptive Boosting) is an ensemble learning method that combines multiple weak learners (typically decision stumps) to form a strong classifier.

Working Process:

Train a weak model on the dataset

Assign higher weights to misclassified samples

Train new models focusing on difficult cases

Combine all models to improve accuracy

Advantages:

High accuracy

Reduces overfitting

Effective for classification tasks

📊 Model Evaluation

The model is evaluated using:

Accuracy Score

Confusion Matrix

Precision

Recall

F1 Score

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn
