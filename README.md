# Customer Segmentation using K-means Clustering

## Project Overview

This project demonstrates customer segmentation using the K-means clustering algorithm. The goal is to group customers of a retail store based on their purchase history, specifically their annual income and spending score. 

## Dataset

The project uses the "Mall_Customers.csv" dataset, which contains information about customers' gender, age, annual income, and spending score.

## Methodology

1. **Data Loading:** The customer data is loaded from the CSV file into a pandas DataFrame.
2. **Data Exploration:** The data is explored to understand its structure, identify potential features for clustering, and check for missing values or outliers.
3. **Data Preparation:** The 'Annual Income (k$)' and 'Spending Score (1-100)' features are selected and standardized using StandardScaler.
4. **Data Clustering:** The K-means clustering algorithm is applied to the standardized data, and the optimal number of clusters is determined using the elbow method.
5. **Data Visualization:** The clusters are visualized in a 2D scatter plot, color-coded by cluster label.
6. **Data Analysis:** The characteristics of each customer cluster are analyzed by calculating the mean income and spending score for each cluster.

## Results

The analysis identified five distinct customer segments:

* **High Income, High Spenders:** Customers with high annual income and high spending scores.
* **Low Income, High Spenders:** Customers with low annual income but high spending scores.
* **High Income, Low Spenders:** Customers with high annual income but low spending scores.
* **Low Income, Low Spenders:** Customers with low annual income and low spending scores.
* **Average Income, Average Spenders:** Customers with average annual income and spending scores.

## Usage

1. Make sure you have the necessary libraries installed (`pandas`, `scikit-learn`, `matplotlib`).
2. Upload the "Mall_Customers.csv" file to your Colab environment.
3. Run the provided code in the notebook.
4. The results will be displayed in the notebook, including the cluster visualization and the cluster summary table.

## Contributing

Feel free to contribute to this project by:

* Improving the data exploration and analysis.
* Experimenting with different clustering algorithms or parameters.
* Adding new features or visualizations.

## License

This project is licensed under the MIT License.
