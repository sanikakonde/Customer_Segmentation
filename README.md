
# Customer Segmentation Using K-Means Clustering

## About the Project

In this project, I worked with customer data to understand their income, spending habits, and purchasing behaviour.

I used **K-Means Clustering**, an unsupervised machine learning algorithm, to group customers with similar characteristics. This can help businesses understand their customers and plan better marketing strategies.

## Objective

- Understand customer data using Exploratory Data Analysis (EDA).
- Find patterns in customer income, spending, and purchases.
- Group similar customers using K-Means Clustering.
- Visualize customer groups using PCA.
- Compare the average income, spending, and purchases of different groups.

## Dataset

I used the Customer Segmentation dataset available on Kaggle.

**Dataset Link:**  
https://www.kaggle.com/datasets/vishakhdapat/customer-segmentation-clustering

The dataset contains information about customers, including their personal details, income, spending on different products, purchase history, website visits, and marketing campaign responses.

### Important Columns

| Column | Description |
|---|---|
| `ID` | Unique customer ID |
| `Year_Birth` | Customer's birth year |
| `Education` | Customer's education level |
| `Marital_Status` | Customer's marital status |
| `Income` | Customer's yearly income |
| `Recency` | Days since the last purchase |
| `MntWines`, `MntFruits`, etc. | Spending on different product categories |
| `NumWebPurchases` | Number of website purchases |
| `NumCatalogPurchases` | Number of catalog purchases |
| `NumStorePurchases` | Number of store purchases |
| `NumWebVisitsMonth` | Website visits per month |
| `Response` | Response to the latest marketing campaign |

## Tools and Technologies Used

- **Python** – Programming language
- **NumPy** – Numerical operations
- **Pandas** – Data cleaning and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Scikit-learn** – Data preprocessing and machine learning
- **Kaggle Notebook** – Development environment

## Project Workflow

### 1. Data Loading
Loaded the dataset using Pandas and explored its structure.

### 2. Data Cleaning
Checked missing values and duplicate records. Handled missing income values and removed an unusually large income value (`666666`) as an outlier.

### 3. Feature Engineering
Created new features such as:
- Age
- Total spending
- Total purchases
- Total children
- Customer association duration
- Total accepted marketing campaigns

### 4. Exploratory Data Analysis (EDA)
Used graphs and charts to understand customer demographics, income, spending patterns, purchases, and relationships between features.

### 5. Data Preprocessing
Scaled numerical features using `StandardScaler` and converted categorical features into numerical form using one-hot encoding.

### 6. Finding the Number of Clusters
Used the Elbow Method and Silhouette Score to compare different numbers of clusters.

### 7. K-Means Clustering
Applied K-Means Clustering with **2 clusters** to group customers based on the selected features.

### 8. PCA Visualization
Used Principal Component Analysis (PCA) to reduce the data to two dimensions and visualize the customer groups.

### 9. Cluster Analysis
Compared the average income, total spending, and total purchases of each cluster to understand the differences between the groups.

## Key Learnings

Through this project, I learned how to:

- Clean and prepare real-world data.
- Perform Exploratory Data Analysis.
- Create useful features from existing columns.
- Handle numerical and categorical data.
- Apply feature scaling and one-hot encoding.
- Use K-Means Clustering for customer segmentation.
- Evaluate clusters using the Elbow Method and Silhouette Score.
- Visualize clusters using PCA.
- Analyze and compare customer groups.

## Conclusion

This project helped me understand how unsupervised machine learning can be used to find patterns in customer data.

By grouping customers with similar characteristics, businesses can better understand customer behaviour and make informed marketing decisions.

It also gave me practical experience in data analysis, data preprocessing, visualization, and machine learning using Python.

---

**Project Type:** Unsupervised Machine Learning  
**Algorithm:** K-Means Clustering  
**Visualization Technique:** PCA
