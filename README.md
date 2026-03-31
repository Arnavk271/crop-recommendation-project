# Crop Recommendation System – Descriptive and Predictive Analytics
Machine Learning project built in DataCamp DataLab to recommend optimal crops based on soil and weather conditions.

## Features
- Analyzes N, P, K values, temperature, humidity, pH, and rainfall
- Predicts best crop from 22 varieties
- Built with scikit-learn, pandas, seaborn

## Results
Pictorial representations

## Summary
I worked on a crop recommendation project in the agriculture domain, using soil nutrients, pH, temperature, humidity and rainfall data to recommend suitable crops. I started with descriptive analytics by cleaning the dataset and exploring it through summary statistics, histograms, boxplots and a correlation heatmap to understand the distributions and relationships between the features. Then I applied predictive analytics by training a Random Forest classifier to predict the crop label, evaluating its performance with accuracy and a classification report and analysing feature importance to see which variables matter most. To go beyond the classroom algorithms, I also implemented a Gaussian Mixture Model for clustering environmental conditions and used t‑SNE to visualize both the true crop labels and the discovered clusters in two dimensions.

For this project, I chose three main algorithms. First, I used a Random Forest classifier as my predictive model to learn from historical crop data and recommend the best crop for new soil and weather conditions; this also gave me feature importance scores to understand which variables are most influential. Second, I applied a Gaussian Mixture Model (GMM) as an unsupervised clustering method to discover groups of similar environmental conditions without using the crop labels, providing a probabilistic view of clusters in the data. Third, I used t‑SNE for non‑linear dimensionality reduction and visualization, projecting the high‑dimensional features into two dimensions so I could visually compare the true crop labels and the GMM clusters

Random Forest:
Random Forest builds many decision trees on random subsets of the data and features, then combines their votes to make the final prediction. By averaging many such trees, the model becomes more accurate than a single tree.​

Gaussian Mixture Model (GMM):
GMM assumes that the data comes from a mix of several Gaussian (normal) distributions, each representing a cluster. It iteratively estimates the probability that each point belongs to each Gaussian and updates the means, variances and mixing weights until the clusters fit the data well.​

t‑SNE:
t‑SNE is a dimensionality‑reduction algorithm that takes high‑dimensional data and places each point in 2‑D so that points that were close in the original space stay close in the plot. It does this by converting pairwise distances into probabilities in high‑ and low‑dimensional space and then moving the 2‑D points to make these probability distributions match as closely as possible.
