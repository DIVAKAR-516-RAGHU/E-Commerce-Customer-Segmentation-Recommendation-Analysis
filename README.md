# E-Commerce Customer Segmentation & Recommendation Analysis

## Project Overview
This project analyzes e-commerce customer purchasing behavior using machine learning techniques. It applies **RFM (Recency, Frequency, Monetary) analysis** and **K-Means clustering** to identify customer segments and uses **Cosine Similarity** to generate product recommendations based on previous purchase patterns.

The goal is to support customer retention, personalized marketing, and data-driven business decisions.

## Objectives
- Analyze customer purchasing patterns.
- Clean and preprocess retail transaction data.
- Calculate customer-level RFM metrics.
- Identify customer segments using K-Means clustering.
- Evaluate clustering using the Elbow Method and Silhouette Score.
- Visualize customer segments using PCA.
- Develop a basic product recommendation system.
- Provide business strategies for each customer segment.

## Dataset
**Dataset:** Online Retail Dataset  
**Source:** UCI Machine Learning Repository  
**Link:** https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains transactional records from an online retail store, including invoice numbers, product details, quantities, transaction dates, prices, and customer information.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Techniques
1. **RFM Analysis:** Measures customer recency, purchase frequency, and monetary value.
2. **K-Means Clustering:** Groups customers based on their purchasing behavior.
3. **Elbow Method:** Helps select a suitable number of clusters.
4. **Silhouette Analysis:** Evaluates cluster separation.
5. **Principal Component Analysis (PCA):** Visualizes customer segments in two dimensions.
6. **Cosine Similarity:** Identifies products with similar customer purchase patterns.

## Customer Segmentation
Customers are grouped into four business-oriented segments:

- **Champions:** High-value customers with strong purchasing activity.
- **Regular Customers:** Customers who purchase relatively frequently.
- **Occasional Buyers:** Customers with less frequent purchasing activity.
- **At-Risk Customers:** Customers who have not purchased recently and may need re-engagement.

*Segment labels are assigned based on the calculated cluster characteristics.*

## Product Recommendation
A basic recommendation system uses customer purchase history and product-to-product cosine similarity to suggest products that a customer has not previously purchased.

## Project Workflow
1. Dataset collection and exploration.
2. Data cleaning and preprocessing.
3. Exploratory Data Analysis (EDA).
4. RFM feature engineering.
5. Feature transformation and scaling.
6. Optimal cluster evaluation.
7. K-Means customer segmentation.
8. PCA visualization.
9. Product similarity calculation.
10. Product recommendation.
11. Business insights and recommendations.
12. Exporting project results.

## Project Files
| File | Description |
|---|---|
| `E-Commerce_Customer_Segmentation_Recommendation_Analysis.ipynb` | Complete Jupyter Notebook |
| `Customer_Segmentation_Results.csv` | Customer-level RFM metrics and cluster assignments |
| `Business_Recommendations_Summary.csv` | Summary of customer segments and business insights |
| `Cleaned_Online_Retail.csv` | Cleaned transaction dataset (available locally; not included in this repository) |

## Business Applications
- Customer retention and re-engagement.
- Personalized product recommendations.
- Targeted marketing campaigns.
- Customer loyalty programs.
- Identification of high-value customers.
- Data-driven business planning.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter
   ```

3. Download the Online Retail dataset from the UCI Machine Learning Repository.
4. Place the extracted `Online Retail.xlsx` file inside a `data` folder.
5. Open the Jupyter Notebook.
6. Execute the cells sequentially.

## Project Outcome
The project demonstrates how machine learning and customer analytics can be applied to retail transaction data to identify customer groups, understand purchasing behavior, generate basic product recommendations, and derive actionable business strategies.

## Author
**Divakar R**  
B.E. Electronics and Communication Engineering

GitHub: [DIVAKAR-516-RAGHU](https://github.com/DIVAKAR-516-RAGHU)

---

**Project:** Day 42 – VEDA AI & ML Internship  
**Status:** Completed
