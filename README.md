# Housing Data Analysis and Insights

---

## Project Overview

- Performed data analysis, feature engineering, clustering, anomaly detection, and feature impact analysis on a housing dataset.
- Aimed to extract meaningful insights, detect patterns, and identify key factors influencing house prices.

---

## Operations Performed

- Loaded and explored a dataset with 545 rows and 13 columns, including numerical and categorical features.
- Verified that the dataset contained no missing values.
- Created visualizations such as boxplots to detect outliers in numerical features like price, area, bedrooms, and parking.
- Treated outliers using the Interquartile Range (IQR) method for numerical columns.
- Generated a new feature, `price_per_area`, to measure the cost per unit area of a house.
- Encoded categorical features such as `mainroad`, `guestroom`, `airconditioning`, and `furnishingstatus` using Label Encoding.
- Scaled numerical features to prepare them for clustering analysis using StandardScaler.
- Applied KMeans clustering to group houses into three clusters based on similarities in their attributes.
- Used Principal Component Analysis (PCA) to reduce the dimensions of the dataset for better visualization.
- Identified anomalies by calculating distances of points from the cluster centroids and flagged the top 5% as potential anomalies.
- Trained a Random Forest Regressor to evaluate the importance of features in predicting house prices.
- Visualized feature importance to identify the most significant factors influencing house prices.

---

## Outputs

- Generated `housing_with_operations.csv` with additional columns for engineered features, cluster labels, and anomaly flags.
- Produced `feature_importances.csv` detailing the importance of features such as area, bedrooms, bathrooms, and stories.
- Created plots for data distributions, clustering results, and feature importances for better interpretability.

---

## Insights

- Area, bedrooms, and bathrooms were identified as key drivers of housing prices.
- Houses with anomalies represented unique cases, such as significantly high prices for smaller areas.
- Clustering highlighted distinct groups of houses with similar characteristics, enabling targeted analysis.

---

Feel free to modify this file or reach out for further support on any aspect of the project!
