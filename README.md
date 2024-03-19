# Cow and Buffalo Milk Company: Merchant Analysis and Credit Scoring

## Introduction

The objective of this project is to assist Cow and Buffalo Milk Company in targeting the right customers, increasing sales, and improving efficiency in allocating advertising spend. 
The project involves developing models to analyze merchant data, create a credit scoring algorithm, identify creditworthy merchants, and provide recommendations for targeting.

## Dataset
The dataset contains information about various merchants, including their annual revenue, spending score, payment history, city, and most purchased product.

## Approach

Data Preprocessing: The dataset is preprocessed to handle missing values, rename columns, and extract relevant features for analysis.

Merchant Clustering: KMeans clustering is performed to segment merchants into distinct groups based on their annual revenue and spending score. The clusters are labeled as Careful, Spendthrift, General, Target, and Miser based on their nature.

Credit Scoring Algorithm: A credit scoring algorithm is developed using merchant payment history and city information. This algorithm helps identify the creditworthiness of merchants, distinguishing between high-risk and low-risk merchants.

## Recommendations: 
Based on the analysis and credit scoring results, recommendations are provided to Cow and Buffalo Milk Company on which merchants to target for advertising and sales efforts.

## How to Run the Code

Requirements: Ensure that you have the necessary libraries installed, including numpy, pandas, matplotlib, scikit-learn, and seaborn.

Data: Download the dataset (data.xlsx) and place it in the same directory as the Python scripts.

Run the Notebooks: Open the provided Jupyter notebooks (Final_Capstone_Project.ipynb, Credit_Worthiness.ipynb, Credit_Scording_Algorithm.ipynb) in your preferred Python environment.

Execute Code: Execute the code cells in each notebook to perform data preprocessing, clustering, credit scoring, analysis, and model training.

Review Results: Examine the analysis results, including merchant clusters, creditworthiness scores, and recommendations.


## Recommendations

Targeting Strategy: Focus advertising and sales efforts on merchants classified as "Target" and "General" clusters, as they are likely to have higher spending scores and contribute significantly to sales.

Creditworthiness: Prioritize credit approval for merchants with high credit scores and a history of timely payments. Implement stricter credit terms for merchants with low credit scores or a history of payment defaults.

Efficiency: Allocate advertising spend efficiently by targeting merchants with the highest potential for sales and creditworthiness, optimizing return on investment.


## Final Analysis Data

Download the final analyzed data into a CSV file (analyzed.csv) containing merchant information, including cluster membership and nature classification.

## Conclusion

This project provides valuable insights and tools for Cow and Buffalo Milk Company to improve targeting strategies, increase sales, and enhance efficiency in advertising spend allocation. By leveraging data analysis and credit scoring algorithms, the company can optimize resource allocation and achieve its business objectives effectively.
