# Machine Learning & Deep Learning Assignment 1 - Airbnb Pricing Analysis

## Project Overview
The 2024 Summer Olympics was held from July 26 to August 11, 2024, in France, with several events starting from July 24. This project analyzes the primary features that impacted the listing prices for Airbnb listings in Paris during this period. Clustering models were utilized to find clusters based on the selected features that impacted the prices of these listings the most. However, the ultimate goal was to answer the question: "*What are the primary factors that increase/decrease the listing prices in Paris during this period?*". Our findings are visualized in various 3D plots, bivariate- & open-street-map scatter plots and tables of silhouette scores for how each model performed with the selected features against PCA features. Read the attached report for a detailed overview

## Objectives 
- *Exploratory Data Analysis (EDA)*: To identify features that affected the price of the listings in Paris the most during the period leading up to and including the period of the Olympics in Paris 2024. 
- *Cluster Analysis*: To find clusters with KMeans and DBSCAN models to segment listings based on the key features found in the EDA section and then choose the best model. 
- *Principal Component Analysis (PCA)*: To see if reduced dimensionality while preserving variance, made for a better model with KMeans or DBSCAN, compared to the models made in the prior section, where we only used features based on their correlation with the price of the listings.

## Executive Summary
Our analysis revealed that host listing count, minimum nights, and room type significantly impact Airbnb prices in Paris. KMeans clustering identified three distinct price-based groups, showing that higher host listing counts and entire home rentals correlate with higher prices. DBSCAN, however, struggled due to the dataset’s density and non-linearity. PCA analysis confirmed that six principal components preserve over 95% of data variance, improving model efficiency, but only by little compared to our KMeans model. The results suggest that host activity and rental type play a crucial role in price variations, rather than just location alone.

## Libraries Required
Before running the program, ensure the following Python libraries are installed:

- `NumPy`
- `Pandas`
- `Matplotlib`
- `Seaborn`
- `Scikit-Learn`

## How to get the data
1. Go to [Inside Airbnb]([https://takeout.google.com](https://insideairbnb.com/get-the-data/)).
2. Under **Data Downloads** find the one for Paris, Île-de-France, France.
3. Click "*show archived data*".
4. Export the '*calendar.csv.gz*' & '*reviews.csv.gz*' from 16 March, 2024 and the '*listings.csv*' from 10 June, 2024.



















