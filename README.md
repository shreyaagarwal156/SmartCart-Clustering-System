# SmartCart Customer Clustering System 🛒

## 📌 Project Overview
SmartCart is a growing e-commerce platform serving customers across multiple countries. Previously, the platform utilized generic marketing and engagement strategies for all users, which led to inefficient marketing spend, missed opportunities to retain high-value customers, and delayed identification of churn-prone users.

This project implements an **Intelligent Customer Segmentation System** using unsupervised machine learning. By analyzing historical customer transaction data, purchasing behavior, and engagement levels, the system groups customers into meaningful clusters. This data-driven approach allows SmartCart to transition from generic campaigns to highly personalized marketing and targeted customer retention strategies.

## 🎯 System Objectives
* **Data-Driven Segmentation:** Discover hidden patterns in customer behavior using clustering algorithms.
* **Feature Engineering:** Process raw transactional data into structured demographic, frequency, and spending metrics.
* **Targeted Personalization:** Provide actionable insights to support personalized marketing and optimize system resources for high-value users.

## 📁 Repository Structure
* `smartcart.ipynb`: The core Jupyter Notebook containing the data pipeline, Exploratory Data Analysis (EDA), dimensionality reduction, and the K-Means clustering implementation.
* `smartcart_customers.csv`: The dataset containing 2,240 customer records and 22 attributes used to train and evaluate the model.

## 📊 Dataset Description
The system processes 22 distinct attributes, categorized into the following core areas:

**1. Customer Demographics:**
* `ID`, `Year_Birth`, `Education`, `Marital_Status`, `Income`, `Kidhome`, `Teenhome`, `Dt_Customer`

**2. Purchase Behavior (Amount Spent):**
* `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`

**3. Purchase Behavior (Frequency):**
* `NumDealsPurchases`, `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`, `NumWebVisitsMonth`

**4. Customer Feedback & Interactions:**
* `Recency`: Number of days since the last purchase
* `Complain`: Customer complaint history over the last 2 years (1 = Yes, 0 = No)

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning Engine:** Scikit-Learn (K-Means Clustering, PCA)
* **Optimization:** Kneed (Elbow method for optimal cluster automation)
* **Data Visualization:** Matplotlib, Seaborn

## 🚀 How to Run the System Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/shreyaagarwal156/SmartCart-Clustering-System.git](https://github.com/shreyaagarwal156/SmartCart-Clustering-System.git)
Navigate to the directory:

Bash
cd SmartCart-Clustering-System
Install the required dependencies:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn kneed
Execute the Pipeline: Open smartcart.ipynb in your preferred IDE (Jupyter, VS Code) and run the cells sequentially to observe the data processing and clustering outputs.

Successfully reduced high-dimensional customer data using PCA while retaining variance.

Automatically determined the optimal number of customer clusters using the Elbow method.

Segmented users based on spending habits, distinguishing between high-frequency web buyers and physical store shoppers.

📬 Contact
Developed by Shreya Agarwal * 📧 Email: shreyaagarwal0015@gmail.com

🔗 GitHub: @shreyaagarwal156
