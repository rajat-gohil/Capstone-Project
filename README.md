# Final Capstone Project: Merchant Clustering and Analysis

## Introduction

This project aims to analyze merchant data and cluster them based on their annual revenue and spending score. The dataset contains information about various merchants, including their annual revenue, spending score, city, most purchased product, and repayment score.

## How to Run the Code

To run the code, follow these steps:

Ensure that you have the necessary libraries installed, including numpy, pandas, matplotlib, and sklearn.

Download the dataset (original data.xlsx) and place it in the same directory as the Python script.

Open the Python script named "Final Capstone Project" in your preferred Python environment (e.g., Jupyter Notebook, Google Colab).

Execute the script cell by cell or all at once to perform data preprocessing, clustering, visualization, analysis, and model training.


## Analysis and Discoveries

The dataset was preprocessed by renaming columns and handling missing values.

KMeans clustering was performed to group merchants into five distinct clusters based on their annual revenue and spending score.

The Elbow Method was used to determine the optimal number of clusters.

Visualizations such as scatter plots and pie charts were created to analyze the distribution of spending scores by city and most purchased product.

Cross-tabulations and bar plots were generated to examine the relationship between city, most purchased product, and cluster nature.

A pivot table was created to compare the average annual revenue across different cities and cluster natures.

Finally, a Random Forest Classifier was trained to predict repayment scores based on merchant features, achieving a certain level of accuracy.


Overall, the analysis provides insights into the segmentation of merchants and their spending behavior, which can be valuable for targeted marketing strategies and business decision-making.
