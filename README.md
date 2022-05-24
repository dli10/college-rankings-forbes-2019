# college-rankings-forbes-2019

A data visualization project for 2019 College Rankings by Forbes.

BasicGraphs codes for visualizing the data as is, plotting different data columns (i.e. undergraduate population, net price, etc.) vs college ranking. Each plot also includes a trendline calculated with a linear regression model.

KMeansClustering applies a k-means clustering method to the data that we have graphed in BasicGraphs. The outputted graphs indicate the clusters as well as the calculated centroids.

PredictRankings fits the data to a linear regression model, walking through the steps from a single variable model to a multi-variable model. The intention of fitting a model is to be able to predict college rankings (i.e. for future years, for colleges that are not present in the given data). The data is also fitted to a logistic regression model, but this model seems to perform worse than the linear regression model, with respect to the data used.
