# CryptoCurrencies

In this module I processed the crypto_data.csv using unsupervised learning to analyze data on the cryptocurrencies traded on the market. 

## Data cleaning and pre-processing
* Removed values that were not trading, checked that all had an algorithmn defined, sorted and removed the IsTrading column, checked for duplicates , removed NAN values,  and stored the coins name. I then created dummy values for text using pd.get.dummies and used the standard scaler from sklearn to standardize the data in the dataframe.

## Reducing data dimensions 
* Used PCA to reduce the data dimensions to three PC components. Created the data frame pcs_df and with 3 new columns PC1, PC2 and PC3. 

## Clustering 
* Created and Elbow Curve
* Predicted the K Clusters
* Created clustered_df with specified columns

## Visualization
* Used a 3D Scatter Plot using plotly express
* Created data table using hvplot.table
* Created a scatter plot using hvplot.scatter
