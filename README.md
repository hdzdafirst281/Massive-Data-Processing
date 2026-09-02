# Massive Data Processing Techniques In Data Science

This repository contains the final project for the "Massive Data Processing Techniques In Data Science" course at Ton Duc Thang University. The project demonstrates a comprehensive approach to handling and analyzing large datasets using advanced machine learning algorithms in PySpark.

## Overview

The project is divided into 5 main tasks, each focusing on a specific machine learning technique and its application using PySpark.

### Tasks

1.  **Clustering (Task 1)**
    *   **Algorithm:** K-Means
    *   **Dataset:** `mnist_mini.csv` (Hand-written digit images)
    *   **Description:** Applying K-Means clustering to group similar handwritten digits. The data is preprocessed by assigning specific weights, and the optimal number of clusters is determined. The average distance to the centroid for each cluster is computed and visualized.

2.  **Dimensionality Reduction (Task 2)**
    *   **Algorithm:** Singular Value Decomposition (SVD)
    *   **Dataset:** `mnist_mini.csv`
    *   **Description:** Reducing the dimensionality of the dataset from 784 dimensions to 3 dimensions using SVD to retain the most important information while minimizing complexity. The resulting lower-dimensional data is visualized in a 3D scatter plot.

3.  **Recommendation System (Task 3)**
    *   **Algorithm:** Alternating Least Squares (ALS) for Collaborative Filtering
    *   **Dataset:** `ratings2k.csv`
    *   **Description:** Evaluating the performance of an ALS model for user-item recommendations. The model is trained with different ranks (number of similar users), and the Mean Squared Error (MSE) is used to evaluate performance and visualize the correlation between MSE and rank.

4.  **Stock Price Regression (Task 4)**
    *   **Algorithm:** Multiple Linear Regression
    *   **Dataset:** `stockHVN2022.csv` (Stock prices of HVN code in HOSE in 2022)
    *   **Description:** Predicting the next day's stock price based on the price fluctuations of the previous 5 days. The data is split into training and testing sets, and the model's performance is evaluated using MSE.

5.  **Multi-class Classification (Task 5)**
    *   **Algorithms:** Multi-layer Perceptron (MLPC), Random Forest, Linear Support Vector Machine (Linear SVC)
    *   **Dataset:** `mnist_mini.csv`
    *   **Description:** Classifying handwritten digits using three different classification algorithms. The accuracy of each model on both the training and testing sets is compared. MLPC achieved the highest accuracy on this dataset.

## Technologies Used

*   **Apache Spark (PySpark):** Core framework for large-scale data processing and machine learning (`pyspark.ml`).
*   **Python:** Programming language.
*   **Matplotlib / Numpy:** For data manipulation and visualization.
*   **Jupyter Notebook:** For interactive code execution (`source.ipynb`).

## Project Structure

*   `report.pdf`: The detailed final report containing theoretical background, implementation details, and result analysis.
*   `source.ipynb`: The Jupyter Notebook containing the PySpark source code for all 5 tasks.

## Authors

Group 8, Class 21H50301, Faculty of Information Technology, Ton Duc Thang University:
*   Pham Phu Binh
*   Nguyen Khac Huy
*   Giang Hoang Dat
*   Do Hoang Duy

**Lecturer:** M.Sc. Nguyen Thanh An
