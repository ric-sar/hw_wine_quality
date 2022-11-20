# Homework - Analysis of Wine Quality Dataset
Homework of Advanced Machine Learning

Once viewed as a luxury good, nowadays wine is increasingly enjoyed by a wider range of consumers. Portugal is a top ten wine exporting country, with 3.17% of the market share in 2005.

Advances in information technologies have made it possible to collect, store and process massive, often highly complex datasets.

The following analysis is applied on the dataset provided by P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis, featured on the article "Modeling wine preferences by data mining from physicochemical properties" in Decision Support Systems, Elsevier, 47(4) pag. 547-553, 2009, where support vector machines and neural networks are applied in the context of ordinal regression.

The study considered vinho verde, a unique product from the Minho (northwest) region of Portugal. Medium in alcohol, is it particularly appreciated due to its freshness (specially in the summer). The data were collected from May of 2004 to February of 2007 by a computerized system (iLab), which automatically manages the process of wine sample testing from producer requests to laboratory and sensory analysis. Each entry denotes the physicochemical characteristics and the final database was exported into a .csv file.

Since the red and white tastes are quite different, the analysis has been performed separately, thus two datasets were built with 1599 red and 4898 white examples.

Regarding the preferences, each sample was evaluated by a minimum of three sensory assessors (using blind tastes), which graded the wine in a scale that ranges from 0 (very bad) to 10 (excellent). The final sensory score is given by the median of these evaluations.

The analysis is divided into four main chapters: this first introductory chapter which describes the required steps to replicate the analysis and the dataset structure; in the second chapter we will analyze each variable of the dataset; in the third chapter the application of the supervised learning methods (Decision Tree, Extra Tree, Random Forest, Bayesian Classification, K-Nearest Neighbors, Radius Neighbors, Support Vector Machine and Logistic Regression) with comparison between methods using accuracy metric and computation of the confusion matrix; in the fourth chapter we perform unsupervised learning methods (K-Means, Mini Batch K-Means, DBSCAN and Hierarchical Agglomerative Clustering) with comparison between methods using accuracy metric and computation of the confusion matrix.

# Run
You can run the code on [Google Colab](https://colab.research.google.com/drive/1GCWpJbxLxZ0Doc6RDSBvkcnZef5TDHwD?usp=sharing).
