## Clustering using K-Means and Gaussian Mixture Models (GMM)

## Overview
This experiment focuses on **unsupervised learning techniques**, specifically:
- **K-Means Clustering**
- **Gaussian Mixture Models (GMM)**

The goal is to group data points (customers) based on similarity and analyze patterns in customer behavior.

## Dataset
- **Name:** Mall Customer Segmentation Dataset  
- **Source:** Kaggle  
- **Features Used:**
  - **Annual Income**  
  - **Spending Score**  
  - **Age (optional)**

##  Objectives
- Understand clustering concepts  
- Apply **K-Means** and **GMM** algorithms  
- Compare **hard and soft clustering**  
- Visualize and interpret clusters  

##  Technologies Used
- **Python**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-learn**  

##  Scenario 1: K-Means Clustering

### Description
**K-Means** groups data into **K clusters** by minimizing the distance between points and their cluster centroid.

###  Steps
1. Import libraries  
2. Load dataset  
3. Perform data preprocessing (**handling missing values, scaling**)  
4. Select relevant features  
5. Use **Elbow Method** to determine optimal K  
6. Apply **K-Means clustering**  
7. Assign cluster labels  
8. Visualize clusters  
9. Interpret cluster characteristics  

###  Evaluation Metrics
- **Inertia (WCSS)**  
- **Silhouette Score**  

###  Visualizations
- Elbow Curve  
- Scatter Plot of Clusters  
- Cluster Centroids  

##  Scenario 2: Gaussian Mixture Model (GMM)

###  Description
**GMM** is a **probabilistic clustering method** that assigns data points to clusters based on probability.

###  Steps
1. Load dataset  
2. Perform preprocessing and scaling  
3. Apply **Gaussian Mixture Model**  
4. Choose number of components  
5. Fit model using **Expectation-Maximization (EM)**  
6. Predict cluster probabilities  
7. Assign clusters based on highest probability  
8. Compare with K-Means clustering  

###  Evaluation Metrics
- **Log-Likelihood**  
- **AIC (Akaike Information Criterion)**  
- **BIC (Bayesian Information Criterion)**  
- **Silhouette Score**  

###  Visualizations
- Cluster Probability Distribution  
- GMM Contour Plots  
- Comparison Plot (**K-Means vs GMM**)  

##  Key Analysis

### K-Means
- Forms **spherical clusters**  
- Sensitive to initialization  
- Works well for **well-separated data**  

### GMM
- Handles **overlapping clusters**  
- Produces **elliptical clusters**  
- Provides **probability-based clustering**  

##  Results
- Identified customer segments such as:
  - **High Income – High Spending**  
  - **Low Income – Low Spending**  
- Observed clear differences between **K-Means** and **GMM clustering**

## Repository Contents
- Python Code Files  
- Dataset  
- Output Screenshots  
- Graphs and Visualizations  
