# EDA-on-churn-analysis
💳 Credit Card Customer Spending Pattern Analysis
    📘 Overview:
                  This project analyzes customer credit card transaction data to uncover spending patterns, behavioral clusters, and anomalies.
                  Using Python-based Exploratory Data Analysis (EDA) and Machine Learning (K-Means Clustering), it identifies groups of customers with similar financial behaviors, which can help financial                              institutions design targeted offers, detect anomalies, and improve customer engagement.
    🎯 Objectives:
              Understand and visualize spending behavior across customers.
              Identify key trends in purchases, payments, and balances.
              Detect unusual or extreme spending patterns.
              Group customers into clusters using K-Means for business segmentation.

  🧠 Key Insights:
                High spenders show large one-off purchases and high credit limits.
                Low spenders tend to use more installments or minimum payments.
                Some clusters indicate heavy cash advance usage — a potential risk factor.
                Patterns discovered can guide marketing, risk management, and credit limit strategies.


  ⚙️ Project Workflow:-
                  1. Data Preprocessing
                            Handled missing values using mean imputation.
                            Dropped non-numeric identifiers (CUST_ID).
                              Standardized features using StandardScaler for clustering.

  2. Exploratory Data Analysis (EDA)
                      Visualized distributions of spending, cash advances, and balances.
                      Correlation heatmaps to find relationships among features.
                      Outlier detection via boxplots.

3. K-Means Clustering
                    Used the Elbow Method to determine the optimal number of clusters.
                    Segmented customers into 4 behavioral clusters.
                     Visualized clusters using PCA (2D projection).

4. Insights Extraction
                    Compared cluster-wise means to describe financial habits.
                    Suggested possible marketing and retention strategies for each group.

5. Visualization Dashboard (Optional)
                    Created an interactive dashboard using Power BI / Streamlit to visualize:
                    Spending by category and frequency
                    Credit Limit vs Purchases
                    Cluster distribution and characteristics

Conclusion :-
This project analyzes credit card customer data to uncover spending patterns and segment users using K-Means clustering.
It helps identify high spenders, low spenders, and risky customers, providing insights for marketing, risk management, and customer retention.
Overall, it demonstrates strong skills in EDA, visualization, and unsupervised machine learning for real-world financial analytics.
