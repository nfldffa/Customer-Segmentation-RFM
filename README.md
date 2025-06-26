# Customer Segmentation Analysis with RFM & K-Means

![Gradio App Screenshot](https://github.com/nfldffa/Customer-Segmentation-RFM/blob/main/gradio.png?raw=true)

A data mining project to segment customers based on their purchasing behavior and build an interactive demo using Gradio.

---

## 🤝 Background
In the business world, not all customers are the same. Understanding differences in customer behavior is key to effective marketing strategies. This project aims to address that issue by performing customer segmentation using historical transaction data.

## ☕ Project Workflow
1.  **Data Cleaning & Exploration:** Load the transaction dataset, handle missing values and duplicates, and perform Exploratory Data Analysis (EDA).
2.  **RFM Analysis:** Calculate **Recency**, **Frequency**, and **Monetary** scores for each customer.
3.  **Preprocessing & Clustering:** Apply log transformation and standardization to the RFM data, then use the **K-Means** algorithm to cluster customers into 4 segments.
4.  **Interpretation & Visualization:** Analyze the characteristics of each formed segment and visualize them using a scatter plot.
5.  **Demo App Development:** Build a simple and interactive web interface using **Gradio** so the model output can be tested by anyone.

## 🚀 Technologies Used
- **Data Analysis:** Python, Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **UI/Demo:** Gradio

## 📔 Dataset Source  
The dataset used in this project is available on Kaggle:  
[Online Retail Dataset – Ulrik Thyge Pedersen](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset)  

## 👌 Visualization Result
Here is the result of customer segmentation into 4 clusters:
![Customer Segmentation Plot](https://github.com/nfldffa/Customer-Segmentation-RFM/blob/main/scatter%20plot.png?raw=true)

---
