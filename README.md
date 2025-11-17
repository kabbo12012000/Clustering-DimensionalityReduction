# Clustering-DimensionalityReduction
# Clustering Analysis on Iris Dataset

This project explored K-Means, Hierarchical, and DBSCAN clustering on the Iris dataset. K-Means, applied to both original and PCA-reduced data, successfully isolated Iris-setosa (species 0) but struggled to clearly separate Iris-versicolor (species 1) and Iris-virginica (species 2), often grouping them. Hierarchical clustering showed similar limitations, with species 1 and 2 exhibiting significant overlap.

DBSCAN demonstrated unique behavior, successfully separating two species but failing to form a cluster for a third, instead marking points as noise. Petal dimensions were consistently the most influential features. While all algorithms identified distinct groups, none perfectly distinguished all three species without some misclassification or noise, highlighting the inherent challenges in separating Iris-versicolor and Iris-virginica.


