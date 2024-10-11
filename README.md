# CryptoClustering


## Project Overview
The purpose of this project was to determine if K-Means was a better method of clustering the data involving cryptocurrencies than PCA analysis. The project involved scaling the data read in through a csv file. The data would then be subjected to an elbow test in order to find the optimal amount of clusters to use in a K-Means analysis, after which an actual K-Means analysis was conducted. Afterwards, the scaled data was optimized to reduce the features to three principle components, using PCA (Principle Component Analysis). The dataframe produced using PCA was then subjected to another elbow test, and subsequent K-Means analysis. Finally, the plots created for both initial and post PCA analysis were then compared to each other. This was done in order to see if the reduction in features had led to a more useful K-Means analysis.

### Main Script
The jupyter notebook used in this project was titled ["CryptoClustering"](https://github.com/EdGonz44/CryptoClustering/blob/main/Crypto_Clustering.ipynb) and conducting all of the procedures explained in the Project Overview.

## Project Structure

The project repository should have the following structure:

```plaintext
CryptoClustering/
│
├── Resources
|   ├── crypto_market_data.csv
├── CryptoClustering.ipynb
└──README.md

```
