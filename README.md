# Python Outlier and Novelty Detection

This project focuses on implementing techniques for identifying anomalies in data. It provides tools for both **outlier detection** and **novelty detection**, which are essential for ensuring data quality, detecting fraud, and identifying unusual patterns in various domains.


| Term               | Meaning                                                                                      |
|--------------------|----------------------------------------------------------------------------------------------|
| Outlier Detection  | Finding unusual points in training data. (The model has seen the data already.)              |
| Novelty Detection  | Detecting new, unseen patterns in new incoming data. (The model was trained on normal data only.) |

## Algorithms

| Algorithm                     | Notes                                                         |
|-------------------------------|---------------------------------------------------------------|
| Local Outlier Factor (LOF)    | Density-based, compares local neighborhood.                   |
| Isolation Forest               | Randomly isolates observations.                               |
| One-Class SVM                  | Learns the boundary of normal class only.                     |
| Elliptic Envelope              | Assumes normal distribution, finds ellipse around data.       |
| Z-Score                        | Marks points far from the mean.                               |
| Autoencoders (unsupervised)    | Train only on normal data, flag high reconstruction error.    |
| DBSCAN (clustering)            | Density-based clustering; noise points = outliers.            |
| Gaussian Mixture Models (GMM)  | Models normal data; low-probability points are anomalies.     |

## Examples

tbd