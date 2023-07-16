# Individual Household Electric Power Consumption Clustering

This repository contains code for clustering individual household electric power consumption using the given dataset. The project focuses on analyzing and visualizing the power consumption patterns and grouping households into clusters based on their consumption behavior.

## Dataset

The dataset used for this project is the Individual Household Electric Power Consumption dataset. It contains 2,075,259 measurements gathered from a house located in Sceaux. The dataset includes features such as date, time, global active power, global reactive power, voltage, global intensity, and energy sub-metering readings for different appliances.

## Data Analysis, Exploration, and Visualization

The provided code performs various data analysis, exploration, and visualization tasks to understand the dataset and its characteristics. It includes:
- Checking the shape of the dataset.
- Extracting additional features such as month, day, hour, and year from the date and time columns.
- Calculating correlations among columns and visualizing the correlation matrix.
- Dropping columns based on correlation analysis.
- Checking for outliers and visualizing boxplots for each column.
- Calculating the percentage of outliers in each column.
- Visualizing the distribution of each column using histograms.
- Dropping unnecessary columns.
- Resampling the data for further analysis.

## Data Cleaning and Preprocessing

The code handles missing values, duplicates, and prepares the data for clustering. It includes:
- Checking and handling missing values in the dataset.
- Checking and handling duplicates in the dataset.
- Splitting the data into training and testing sets.
- Scaling the data using the StandardScaler.

## Model

The clustering task is performed using the K-means algorithm. The code includes the following steps:
- Determining the optimal number of clusters using the elbow method.
- Performing K-means clustering on the test dataset.
- Reducing the dimensionality of the dataset using Principal Component Analysis (PCA).
- Visualizing the clusters in a scatter plot.

## Evaluation

The clustering results are evaluated by analyzing the power consumption patterns of each cluster. The code includes the following steps:
- Calculating the mean consumption of each cluster.
- Visualizing the consumption distribution for each cluster.

## Dependencies

The following libraries are required to run the code:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

