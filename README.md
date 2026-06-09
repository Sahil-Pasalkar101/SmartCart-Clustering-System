# SmartCart Customer Segmentation System

## Overview

This project develops an intelligent customer segmentation system for SmartCart, an e-commerce platform seeking to improve customer understanding and marketing effectiveness through data-driven decision-making.

Using unsupervised machine learning techniques, customers are segmented into distinct groups based on demographic characteristics, purchasing behavior, engagement metrics, and loyalty indicators. These segments enable more targeted marketing campaigns, improved customer retention strategies, and better allocation of business resources.

---

## Business Problem

SmartCart currently applies generic marketing and engagement strategies across its customer base without a clear understanding of behavioral differences between customers.

This approach results in:

* Inefficient marketing expenditure
* Limited personalization
* Missed opportunities to retain high-value customers
* Delayed identification of churn-prone customers

The objective of this project is to identify meaningful customer segments that can support personalized marketing and customer relationship management initiatives.

---

## Dataset

The dataset contains customer information collected from SmartCart's e-commerce platform.

| Metric           | Value                 |
| ---------------- | --------------------- |
| Customer Records | 2,240                 |
| Features         | 22                    |
| Data Type        | Structured            |
| Learning Method  | Unsupervised Learning |

### Feature Categories

* Customer Demographics
* Household Information
* Product Spending Patterns
* Campaign Response History
* Website Engagement Metrics
* Customer Loyalty Indicators

---

## Methodology

### 1. Data Preparation

* Missing value treatment
* Data quality assessment
* Outlier analysis
* Feature transformation

### 2. Feature Engineering

Additional business-oriented features were created, including:

* Customer Age
* Customer Tenure
* Total Spending
* Total Children
* Education Groups
* Marital Status Groups

### 3. Exploratory Data Analysis

Comprehensive exploratory analysis was performed to understand:

* Customer demographics
* Spending behavior
* Purchase trends
* Campaign response patterns
* Feature relationships

### 4. Customer Segmentation

Customer groups were identified using K-Means Clustering.

Model selection was supported through:

* Elbow Method
* Silhouette Score Analysis

### 5. Cluster Interpretation

Each cluster was analyzed to identify:

* High-value customers
* Frequent purchasers
* Low-engagement customers
* Potential churn segments

---

## Technology Stack

| Category             | Tools                      |
| -------------------- | -------------------------- |
| Programming Language | Python                     |
| Data Analysis        | Pandas, NumPy              |
| Visualization        | Matplotlib, Seaborn        |
| Machine Learning     | Scikit-Learn               |
| Evaluation           | KNeed, Silhouette Analysis |

---

## Project Structure

```text
smartcart-customer-segmentation/
│
├── dataset/
│   ├── raw/
│   └── processed/
│
├── code/
│   └── SmartCart_Clustering_System.ipynb
│
├── outputs/
│   ├── plots/
│   ├── models/
│   └── reports/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Results

The clustering model successfully identified distinct customer segments with measurable differences in purchasing behavior, engagement levels, and loyalty characteristics.

These segments can be leveraged to:

* Improve campaign targeting
* Increase customer retention
* Optimize marketing expenditure
* Support customer lifetime value initiatives
* Enable data-driven business strategies

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<username>/smartcart-customer-segmentation.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

* Implementation of DBSCAN and Hierarchical Clustering for comparison
* Automated cluster monitoring pipeline
* Interactive dashboard for business stakeholders
* Customer lifetime value prediction integration
* Churn prediction modeling

---

## Author

Sahil Pasalkar

Machine Learning | Data Science | GenAI

