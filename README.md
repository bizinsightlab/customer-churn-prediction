# Gym Customer Churn Prediction & Retention Strategy

## Objective
The goal of this project was to analyze customer behavior for a gym chain (Model Fitness) to predict the probability of cancellation (churn) for each member. From a business perspective, the objective was to develop a predictive model to identify at-risk customers and segment them into distinct profiles to support targeted marketing campaigns and data-driven retention strategies.

## Key Results
The analysis revealed that customer Lifetime, weekly workout frequency in the current month, and the contract period are the most critical factors driving churn. Using unsupervised machine learning, I segmented customers into 5 distinct profiles. **Cluster 0** was identified as the highest-risk group (characterized by short-term contracts and low attendance). Implementing proactive engagement programs before these short-term contracts expire can drastically reduce overall churn.

## Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-Learn** (Classification Models: Logistic Regression, Random Forest; Clustering Models: K-Means, Dendrogram)
- **Jupyter Notebook / VS Code**

## What I Learned
- Implementing and comparing supervised machine learning models applied to customer retention problems.
- Applying data standardization (`StandardScaler`) and evaluating classification metrics (Accuracy, Precision, Recall).
- Performing advanced statistical segmentation using unsupervised learning algorithms (Clustering).

## Future Improvements
- Automate the pipeline to monitor monthly cluster shifts and behavior transitions.
- Design and execute A/B tests with promotional incentives (e.g., discounts on long-term renewals) targeted specifically at the high-risk cluster.

---

## Methodology
1. **Exploratory Data Analysis (EDA):** Analyzed feature distributions, calculated means by churn group, and evaluated correlations.
2. **Classification Modeling:** Split the dataset into training and testing sets, performed hyperparameter tuning, and validated model performance.
3. **Customer Clustering:** Created a distance matrix, plotted a dendrogram, and applied the K-Means algorithm.
4. **Strategic Formulation:** Translated analytical insights into actionable business recommendations.

## How to Run
1. Clone this repository.
2. Ensure Python is installed.
3. Install the required dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
4. Open and execute the `.ipynb` file in Jupyter Notebook or VS Code.
