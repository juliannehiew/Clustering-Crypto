# Clustering-Crypto

### Background

You are a Senior Manager at the Advisory Services team on a [Big Four firm](https://en.wikipedia.org/wiki/Big_Four_accounting_firms). One of your most important clients, a prominent investment bank, is interested in offering a new cryptocurrencies investment portfolio for its customers, however, they are lost in the immense universe of cryptocurrencies. They ask you to help them make sense of it all by generating a report of what cryptocurrencies are available on the trading market and how they can be grouped using classification.  

In this homework assignment, you will put your new unsupervivsed learning and Amazon SageMaker skills into action by clustering cryptocurrencies and creating plots to present your results.

You are asked to accomplish the following main tasks:

* **[Data Preprocessing](#Data-Preprocessing):** Prepare data for dimension reduction with PCA and clustering using K-Means.

* **[Reducing Data Dimensions Using PCA](#Reducing-Data-Dimensions-Using-PCA):** Reduce data dimension using the `PCA` algorithm from `sklearn`.

* **[Clustering Cryptocurrencies Using K-Means](#Clustering-Cryptocurrencies-Using-K-Means):** Predict clusters using the cryptocurrencies data using the `KMeans` algorithm from `sklearn`.

* **[Visualizing Results](#Visualizing-Results):** Create some plots and data tables to present your results.

* **[Optional Challenge](#Optional-Challenge):** Deploy your notebook to Amazon SageMaker.

---

### Clustering-Crypto Results

### Data visualization

Clustering Cryptocurrencies Using K-Means

* Elbow Curve
## ![Elbow Curve](https://github.com/juliannehiew/Clustering-Crypto/blob/main/Images/Elbow%20Curve.JPG)


Elbow curve is used to calculate the WSS for different values of K, and select the best value of K when WSS starts to diminish.  In this instance, the plot looks like a clear elbow at k = 4.



* 3D-Scatter with the PCA data and the clusters
## ![ 3D-Scatter with the PCA data and the clusters](https://github.com/juliannehiew/Clustering-Crypto/blob/main/Images/Visualising%20results%20-%203D%20Clusters.JPG)


* Scatter Plot with Tradable Cryptocurrencies
## ![ Scatter Plot with Tradable Cryptocurrencies](https://github.com/juliannehiew/Clustering-Crypto/blob/main/Images/Scatter%20Plot%20with%20Tradable%20Cryptocurrencies.JPG)




