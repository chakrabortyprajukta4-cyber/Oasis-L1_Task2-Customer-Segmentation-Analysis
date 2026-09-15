# Oasis-L1_Task2-Customer-Segmentation-Analysis
This project demonstrates mainly about Customer Segmentation. # Customer Segmentation Analysis

## Objective

The objective of this project is to segment customers or sales records into meaningful groups using **K-Means Clustering**. The analysis uses Sales, Quantity, and Profit to identify different business patterns and provide suitable marketing recommendations for each segment.

## Steps Performed

1. Imported the required Python libraries.
2. Loaded the `SampleSuperstore.csv` dataset using Pandas.
3. Explored the dataset structure, columns, shape, and basic information.
4. Checked for missing values and removed incomplete records.
5. Removed duplicate records from the dataset.
6. Performed descriptive statistical analysis on the numerical features.
7. Calculated average Sales, Quantity, and Profit.
8. Selected **Sales, Quantity, and Profit** as features for clustering.
9. Standardized the selected features using `StandardScaler`.
10. Applied the **Elbow Method** to determine a suitable number of clusters.
11. Used **K-Means Clustering** with 4 clusters.
12. Assigned a cluster label to each record.
13. Created visualizations for Sales vs Profit and Quantity vs Sales.
14. Visualized the number of records present in each cluster.
15. Generated cluster profiles based on average Sales, Quantity, and Profit.
16. Developed marketing recommendations for each cluster.
17. Saved the final segmented dataset as `Customer_Segmentation_Result.csv`.

## Tools & Technologies

* **Python**
* **Pandas** – Data loading and manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – StandardScaler and K-Means Clustering
* **Jupyter Notebook / VS Code** – Development environment

## Dataset

The project uses the **Sample Superstore** dataset containing sales-related information such as Sales, Quantity, Discount, and Profit.

## Outcome

The analysis successfully divided the records into **4 clusters** using K-Means clustering. Cluster profiles were created to compare average Sales, Quantity, and Profit across the groups. Based on these characteristics, different marketing strategies such as premium offers, loyalty rewards, cross-selling, bundle offers, and pricing improvements were suggested.

The final clustered dataset is saved as:

`Customer_Segmentation_Result.csv`

## Conclusion

This project demonstrates the practical use of **unsupervised machine learning** for customer segmentation. By identifying groups with similar sales and profit characteristics, businesses can develop more targeted marketing strategies and make better data-driven decisions.

