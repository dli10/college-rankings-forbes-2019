# college-rankings-forbes-2019

## A data visualization project for 2019 College Rankings by Forbes.

The dataset (.csv) for this data visualization can be found in 'Forbes Ranking.zip'.

'TrendLineGraphs' codes for visualizing the data as is, plotting different data columns (i.e. undergraduate population, net price, etc.) vs college ranking. Each plot also includes trendlines calculated with either a linear regression model or a logistic regression model. The p-values and R-squared values are also calculated and included on each graph.

'KMeansClustering' applies a k-means clustering method to the data that we have graphed in BasicGraphs. The outputted graphs indicate the clusters as well as the calculated centroids.

'PredictRankings' fits the data to a linear regression model, walking through the steps from a single variable model to a multi-variable model. The intention of fitting a model is to be able to predict college rankings (i.e. for future years, for colleges that are not present in the given data). The data is also fitted to a logistic regression model, but this model seems to perform worse than the linear regression model, with respect to the data used.

'DataScraping' scrapes information for colleges that Forbes includes in their most recent ranking on their website. This was specifically done to scrape the 2021 College Rankings by Forbes. As our initial dataset of 2019 College Rankings by Forbes was found on Kaggle and there was no dataset readily available for other years, this data scraping code was written to obtain more data from a different year. So far, this code is only able to scrape information from specific college profile sites on Forbes, and not the website with all the college rankings, so the url for each college must be specified to be able to data scrape. Extraneous characters (i.e. '#', '$', etc.) have also not been accounted for in this data scraping.
