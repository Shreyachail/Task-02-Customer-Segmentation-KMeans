# Task-02: Customer Segmentation using K-Means

## Objective

To group retail store customers into different segments based on their annual income and spending score using the K-Means clustering algorithm.

## Dataset

The project uses the **Mall Customers Dataset**, which contains customer information such as:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Methodology

1. Loaded and explored the customer dataset.
2. Checked the dataset shape and missing values.
3. Visualized customer demographics and distributions.
4. Selected Annual Income and Spending Score as clustering features.
5. Used the Elbow Method to determine the suitable number of clusters.
6. Applied K-Means clustering with 5 clusters.
7. Visualized the customer segments and cluster centroids.
8. Analyzed the characteristics of each customer segment.

## Customer Segments

- **Cluster 0:** Medium-income customers with medium to high spending.
- **Cluster 1:** High-income customers with high spending.
- **Cluster 2:** Low-income customers with high spending.
- **Cluster 3:** High-income customers with low spending.
- **Cluster 4:** Low-income customers with low spending.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Conclusion

K-Means clustering was successfully used to segment mall customers based on Annual Income and Spending Score. The identified customer groups can help a retail store create targeted marketing campaigns, personalized offers, loyalty programs, and better customer retention strategies.
