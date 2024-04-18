# Anomaly-Detection of Retail Store Sales

Introduction:

Anomaly detection plays a crucial role in various fields, including finance, healthcare, and retail. In this project, we focused on applying anomaly detection techniques to retail store sales data. The primary objective was to identify outliers or rare events within the dataset that exhibit abnormal behavior compared to the rest of the data points.
Methodology:
We employed a variety of anomaly detection methods, including statistical models, Isolation Forest, Clustering-Based Local Outlier Factor (CBLOF), and Auto-encoders. These techniques were applied to both univariate and multivariate data to comprehensively analyze the retail sales dataset.

2. Univariate Anomaly Detection:

  2.1 Statistical Modeling: 
  We applied statistical process control methods such as mean and standard deviation thresholding to detect anomalies in sales. Outliers were identified based on the three-    sigma rule, and the top and bottom outlier transactions were analyzed.

  2.2 Isolation Forest:
  We employed the Isolation Forest algorithm to identify outliers in sales data. The algorithm isolates observations by randomly selecting features and splitting values,   making it effective in detecting anomalies.

3. Multivariate Anomaly Detection:
We extended our analysis to multivariate data by considering attributes such as discount and profit. Techniques like CBLOF and Isolation Forest were applied to identify outliers in this context.

  3.1. Auto-encoders:
  Finally, we utilized Auto-encoders, a deep learning model, to detect anomalies in multivariate data. By training the Auto-encoder model, we learned useful data            
  representations and calculated reconstruction errors to identify outliers.
