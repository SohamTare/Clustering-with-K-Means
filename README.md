# Clustering-with-K-Means
Clustering with K-Means

## 📌 Objective
Perform unsupervised learning using K-Means to segment mall customers based on their attributes.

## 🧰 Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📂 Dataset
We use the **Mall_Customers.csv** dataset, which contains:
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

## 🔍 Steps Performed

1. **Data Loading & Inspection**  
   - Imported the dataset and explored structure and basic info.

2. **Feature Selection & Normalization**  
   - Chose relevant features for clustering.
   - Applied `StandardScaler` for normalization.

3. **Dimensionality Reduction**  
   - Applied PCA to reduce features to 2D for visualization.

4. **Elbow Method**  
   - Used to find the optimal number of clusters by plotting inertia values.

5. **K-Means Clustering**  
   - Applied `KMeans` with the optimal K (determined from Elbow).

6. **Evaluation**  
   - Calculated Silhouette Score to assess clustering performance.

7. **Visualization**  
   - Visualized clusters in PCA-reduced 2D space using Seaborn.

## 📊 Results
- The elbow method suggested **K=5** as optimal.
- Clustering visualized using PCA clearly grouped customers based on behavior.
- Silhouette Score was used to validate cluster quality.

## 📁 Files in Repository
- `task8_kmeans_clustering.py`: Python code for the task.
- `Mall_Customers.csv`: Dataset file (not uploaded here for privacy).
- `README.md`: This documentation.

## ✅ Conclusion
K-Means clustering is an effective technique for customer segmentation, helping businesses target marketing efforts based on customer groupings.
