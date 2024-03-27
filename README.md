# CryptoClustering

This Python script performs clustering analysis on cryptocurrency market data using the K-Means algorithm. The analysis includes data preprocessing, feature scaling, dimensionality reduction using Principal Component Analysis (PCA), and visualization of clustering results.

## Requirements

- Python 3.x

- Google Colab

### Required Python packages: 

- pandas
  
- matplotlib
  
- scikit-learn

  
## Installation

1. Clone the repository or download the Python script (crypto_clustering.py).

2. Open with Colab and upload the .csv file found in Resources. Alternatively, run in VSCode or Jupyter Notebook, changing the reference path.
   
## Usage

1. Place your cryptocurrency market data in a CSV file named crypto_market_data.csv. Ensure that the file includes columns for relevant features such as price change percentages over different time periods.
   
2. Run the Python script crypto_clustering.py.
   
3. The script will perform clustering analysis on the market data and generate visualizations to illustrate the clustering results before and after PCA dimensionality reduction.
   
4. Analyze the visualizations and interpret the clustering results based on the insights obtained.
   
## Explanation

The script begins by loading the cryptocurrency market data from the CSV file and performing basic data exploration.
It then preprocesses the data by standardizing the features using StandardScaler from scikit-learn.
Next, it applies the K-Means algorithm to the scaled data to determine the optimal number of clusters using the Elbow Method.
After determining the optimal number of clusters, K-Means clustering is performed, and the results are visualized using scatter plots.
Additionally, the script applies PCA for dimensionality reduction and repeats the clustering process to compare the results before and after PCA.
Finally, it generates composite plots to compare the Elbow curves and scatter plots before and after PCA.
