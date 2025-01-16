# Analysis of House Price Prediction Data in Seattle, USA using K-Means and K-Medoids Clustering

## Objective
The objective of this project is to group houses in Seattle, USA, based on key features such as price, number of bedrooms, building area, land area, and floor count. The goal is to identify patterns in the housing market, which could help prospective buyers find homes that best align with their preferences.

## Data
The analysis uses the [House Price Prediction dataset](https://www.kaggle.com/datasets/shree1992/housedata?select=data.csv) from Kaggle, which provides detailed information about homes in Seattle, including:
- Price
- Number of bedrooms
- Building area
- Land area
- Floor count

## Methods
- **K-Means Clustering**: This method requires the number of clusters to be predefined and partitions the data into clusters based on similarity.
- **K-Medoids Clustering**: Unlike K-Means, this method selects several data points as medoids (central objects) for the clusters. The number of clusters is determined by the number of medoids.

## Results
- Both **K-Means** and **K-Medoids** clustering methods successfully identified two distinct clusters, effectively categorizing the homes in Seattle according to the key features.
- **K-Means Clustering**: Achieved the highest silhouette score of **0.32329** with two clusters.
- **K-Medoids Clustering**: Formed two clusters with a silhouette score of **0.300**.
- Based on the silhouette scores, **K-Means Clustering** was identified as the most suitable method for this dataset due to its higher silhouette score.

## Conclusion
This analysis demonstrated that both clustering methods were effective in categorizing homes in Seattle, with K-Means providing the most robust results. Future work could explore additional features or more advanced clustering techniques to refine the predictions further.
