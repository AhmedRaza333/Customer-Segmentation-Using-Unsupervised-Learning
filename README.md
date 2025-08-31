

Objective

The objective of this project is to segment mall customers based on their spending habits using unsupervised learning techniques. The main goal is to identify different groups of customers and suggest specific marketing strategies for each group.

---

Dataset: Mall Customers Dataset

Columns in the dataset:

* CustomerID: Unique ID for each customer
* Gender: Male or Female
* Age: Age of the customer
* Annual Income (k\$): Annual income in thousands
* Spending Score (1–100): A score assigned based on spending behavior

---

## Steps Performed

### 1. Exploratory Data Analysis (EDA)

* Checked data types and missing values
* Analyzed distributions of Age, Gender, Income, and Spending Score
* Created visualizations (histograms, scatter plots, box plots) to understand patterns

### 2. K-Means Clustering

* Used the Elbow Method to find the optimal number of clusters
* Applied K-Means algorithm to segment customers
* Labeled each customer with their cluster

### 3. Dimensionality Reduction

* Used PCA (Principal Component Analysis) and t-SNE to reduce dimensions
* Visualized clusters in 2D space to clearly show the customer groups

### 4. Marketing Strategy for Each Cluster

* Analyzed each group based on age, income, and spending behavior
* Suggested specific marketing strategies for each group

---

## Tools and Libraries Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Cluster-wise Marketing Strategies

Cluster 0: Young and high spenders
→ Suggest luxury products and loyalty programs

Cluster 1: Older customers with low spending
→ Focus on awareness and discount offers

Cluster 2: High income but moderate spending
→ Offer personalized recommendations and combos

Cluster 3: Low income and low spending
→ Promote affordable products and basic plans

Cluster 4: Middle-aged with high spending
→ Provide exclusive deals and retargeting ads

---

## Conclusion

Using K-Means clustering, we successfully grouped customers into segments based on their behavior. These insights can help the business design targeted marketing campaigns to improve engagement and sales.

---

Name: \[AHMED RAZA ATTARI ]
Task: Customer Segmentation – K-Means Clustering
Date: 31 August 2025 
INTERN DevelopersHub Corporation
