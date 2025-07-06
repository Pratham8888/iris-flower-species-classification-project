# Iris Flower Species Classification

**Project Status:** Completed

## Objective
The goal of this project was to build a machine learning model capable of accurately classifying the species of an Iris flower (setosa, versicolor, or virginica) based on four physical measurements: sepal length, sepal width, petal length, and petal width.

## Dataset
This project uses the classic Iris dataset, a real-world dataset collected by botanist Edgar Anderson. It contains 150 samples from the three different species of Iris flowers.

## Process
1.  **Data Loading & Exploration:** Loaded the dataset using scikit-learn and used Pandas to inspect its structure and statistics.
2.  **Data Visualization:** Created scatter plots using Matplotlib and Seaborn to visualize the relationships between features and identify patterns among the different species.
3.  **Data Preparation:** Split the data into features (X) and a target (y), and then further divided it into an 80% training set and a 20% testing set.
4.  **Model Training:** Trained a K-Nearest Neighbors (KNN) classification model on the training data.
5.  **Model Evaluation:** Evaluated the trained model's performance on the unseen test set to measure its accuracy.

## Results
The trained K-Nearest Neighbors model achieved an accuracy of **100%** on the test set, correctly identifying the species of all 30 flowers it had never seen before.

## What I Learned
- The full end-to-end workflow of a machine learning project.
- The importance of the train-test split to prevent "cheating" and get a true measure of performance.
- How to use fundamental Python libraries like Pandas (for data manipulation), Matplotlib/Seaborn (for visualization), and Scikit-learn (for modeling).

## How to Run
To run this project, you can open the `iris_classification.ipynb` notebook in Google Colab or another Jupyter environment.
