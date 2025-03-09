# Machine Learning & Deep Learning Assignment 1 - Airbnb Pricing Analysis

## Project Overview
This project aims to analyze the primary factors that contribute to the increase in Airbnb booking prices in Paris during the 2024 Summer Olympics. The assignment involved three key tasks: Exploratory Data Analysis (EDA) to identify pricing patterns (incl. writing your own code for correlation calculation and visualization), Cluster Analysis to segment listings based on key features, and Principal Component Analysis (PCA) to reduce dimensionality while preserving variance.

## How to get the data
1. Go to [Inside Airbnb]([https://takeout.google.com](https://insideairbnb.com/get-the-data/)).
2. Under **Data Downloads** find the one for Paris, Île-de-France, France.
3. Click "*show archived data*".
4. Export the '*calendar.csv.gz*' & '*reviews.csv.gz*' from 16 March, 2024 and the '*listings.csv*' from 10 June, 2024.

## Libraries Required
Before running the program, ensure the following Python libraries are installed:

- `NumPy`
- `Pandas`
- `Matplotlib`
- `Seaborn`
- `Scikit-Learn`

## Key findings
Our analysis revealed that host listing count, minimum nights, and room-type significantly impact Airbnb prices in Paris. K-Means clustering identified three distinct price-based groups, showing that higher host listing counts and entire home rentals correlate with higher prices. DBSCAN, however, struggled due to the dataset’s density and non-linearity. PCA analysis confirmed that six principal components preserve over 95% of data variance, improving model efficiency, but only by little compared to our KMeans model. The results suggest that host activity and rental type play a crucial role in price variations, rather than just location alone.















