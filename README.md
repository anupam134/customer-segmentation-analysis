📌 Customer Segmentation Analysis
📖 Overview
Customer segmentation is a crucial technique in marketing that helps businesses group customers based on similar characteristics. This project leverages unsupervised machine learning (K-Means, Hierarchical Clustering, and DBSCAN) to segment customers based on spending behavior and demographics.

📂 Dataset
We use the Mall Customers Dataset, which contains the following features:

CustomerID – Unique identifier for each customer
Gender – Male/Female
Age – Age of the customer
Annual Income (k$) – Annual income in thousands
Spending Score (1-100) – A metric of customer engagement with the mall
🎯 Objective
Identify different customer groups based on spending habits
Provide insights for targeted marketing strategies
Compare clustering algorithms to find the best segmentation method
🔧 Installation & Setup
Prerequisites
Ensure you have Python 3.7+ and the following libraries installed:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
📊 Methodology
1️⃣ Exploratory Data Analysis (EDA)
Handling missing values
Visualizing age distribution, income levels, and spending behavior
Correlation analysis
2️⃣ Feature Scaling
Standardizing the numerical features for better clustering performance
3️⃣ Clustering Techniques
✔ K-Means Clustering
✔ Hierarchical Clustering
✔ DBSCAN (Density-Based Spatial Clustering)

4️⃣ Model Evaluation
Elbow Method & Silhouette Score for optimal cluster selection
Visualization of clusters using scatter plots & pair plots
📈 Results
Customers were segmented into X distinct groups based on income and spending score
Key Findings: High spenders vs. low spenders, budget-conscious customers, and potential high-value customers
