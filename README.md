Customer Segmentation Using Unsupervised Learning

Overview
This project focuses on customer segmentation, a technique used to divide a customer base into distinct groups based on shared characteristics such as demographics and purchasing behavior. The goal is to help a fictional retail company target its marketing efforts more effectively by understanding customer behavior and preferences.

The project uses the Mall Customer Dataset, which contains information about customers' age, gender, annual income, and spending score. By applying unsupervised learning techniques like K-Means clustering, we segment customers into meaningful groups and provide actionable insights for the business.


Dataset
The dataset used in this project is the Mall Customer Dataset, available on Kaggle. It includes the following features:

CustomerID: Unique identifier for each customer.

Gender: Gender of the customer (Male/Female).

Age: Age of the customer.

Annual Income (k$): Annual income of the customer in thousands of dollars.

Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature (higher score indicates higher spending).


Project Steps
The project is divided into the following steps:

Data Preprocessing:

Handle missing values and outliers.

Normalize numerical features to ensure all features contribute equally to the analysis.

Exploratory Data Analysis (EDA):

Visualize distributions of customer attributes (e.g., age, income, spending score).

Identify patterns and correlations between features.

Clustering Models:

Apply unsupervised learning algorithms such as K-Means, DBSCAN, or Hierarchical Clustering.

Determine the optimal number of clusters using methods like the Elbow Method and Silhouette Score.

Cluster Profiling:

Analyze the characteristics of each cluster (e.g., average age, income, spending score).

Provide actionable insights and recommendations based on cluster analysis.

Reporting:

Document the data preparation, modeling approach, and findings.

Visualize cluster assignments using Principal Component Analysis (PCA) for a 2D projection.


Tools and Libraries
The following Python libraries are used in this project:

Pandas: For data manipulation and analysis.

NumPy: For numerical computations.

Matplotlib and Seaborn: For data visualization.

Scikit-learn: For preprocessing, clustering, and evaluation.

PCA: For dimensionality reduction and visualization.
