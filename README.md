# RFM-customer-segmentation-
Applied RFM (Recency, Frequency, Monetary) Analysis to transactional data to segment customers based on purchasing behavior and value. Used Python to uncover customer patterns, identify high-value segments, and generate actionable insights to support targeted marketing, customer retention, and data-driven business decisions.
# Customer Segmentation Using RFM Analysis

## 1. Project Overview

A common mistake many businesses make is treating all customers the same. They run generic promotions, send the same emails, and wonder why their revenue isn't growing.

The truth is, not all customers are created equal. But how do you tell the difference?

That's where **RFM Analysis** comes in. RFM (Recency, Frequency, and Monetary Value) is a customer segmentation technique that helps businesses identify their most valuable customers based on purchasing behaviour.

In this project, I applied RFM Analysis to transactional data to examine customer purchasing patterns, identify high-value customers, and group customers into meaningful segments. The goal is to transform raw transactional data into actionable insights that support customer retention, targeted marketing, customer loyalty, and revenue growth.

## 2. Business Problem

Many businesses adopt a one-size-fits-all marketing strategy without considering differences in customer purchasing behaviour.

This can result in:
- Ineffective marketing campaigns.
- Poor customer retention.
- Missed opportunities to engage high-value customers.
- Difficulty identifying customers who are becoming inactive.
- Inefficient allocation of marketing resources.

**Business Question:** How can businesses use transactional data to identify valuable customer segments and develop targeted strategies to improve customer engagement and retention?

## 3. Project Objectives

- Perform Exploratory Data Analysis (EDA) to understand customer purchasing behaviour.
- Examine sales trends, transaction patterns, and customer activity.
- Calculate Recency, Frequency, and Monetary (RFM) metrics.
- Segment customers based on their purchasing behaviour.
- Identify high-value, loyal, at-risk, and inactive customers.
- Generate actionable business recommendations.

## 4. Tools and Technologies

| Tool | Application |
|---|---|
| Python | Data analysis and manipulation |
| Pandas | Data cleaning and transformation |
| NumPy | Numerical computations |
| Plotly | Interactive visualizations |
| Jupyter Notebook / Google Colab | Development environment |

## 5. Project Methodology

The project follows a structured data analytics workflow:

### 5.1 Data Loading and Understanding
- Upload dataset (Kaggle).
- Examined dataset dimensions, columns, and data types.
- Reviewed data structure and identified relevant variables.

### 5.2 Data Cleaning 
- Handled missing values.
- Identified and removed duplicate records where appropriate.
- Prepared transactional data for analysis.

### 5.3 Exploratory Data Analysis (EDA)

Conducted EDA to understand the underlying patterns and characteristics of the dataset.

Key areas explored:
- Customer purchasing behaviour.
- Sales and revenue distribution.
- Transaction frequency and order patterns.
- Purchase trends over time.
- Product and customer-level performance.
- Outliers and distribution of numerical variables.

Visualizations were used to identify patterns, trends, and potential business opportunities.

### 5.4 RFM Analysis

Calculated the three core RFM metrics:

| Metric | Description | Business Interpretation |
|---|---|---|
| Recency (R) | Time since a customer's last purchase | Measures customer activity |
| Frequency (F) | Number of purchases made | Measures customer engagement and loyalty |
| Monetary (M) | Total amount spent | Measures customer value |

Customers were assigned RFM scores based on their purchasing behaviour.

### 5.5 Customer Segmentation

Used the RFM scores to classify customers into meaningful segments, such as:

- High Value Customers
- Loyal Customers
- Potential New Customers
- At Risk
- Lost Customers
- other (needs further investigation and reclassification)


The segmentation provides a clearer understanding of customer value and engagement.

### 5.6 Data Visualization

Developed visualizations to communicate:
- Customer distribution across segments.
- Revenue contribution by customer segment.
- Customer purchasing behaviour.
- RFM metric distributions.
- Segment-level performance.

Interactive visualizations were created using Plotly to improve data exploration and presentation.

## 6. Key Findings

This section highlights the most important discoveries from the analysis.

Examples of findings to report:
- High Value customer segments contribute the most revenue with 24%
- 6.4% of customers are at risk of becoming inactive
- High Value Customers(24.%), Loyal Customers(21.6%) and Potential New Customers(18.0%) segments demonstrate the highest purchasing frequency
- Around 12k-15k of concerntrated revenue among high-value customers
<img width="1210" height="417" alt="customer segment " src="https://github.com/user-attachments/assets/195de485-8bd2-4f4f-9a8a-8abf396bc61a" />
<img width="1216" height="434" alt="monetary segment" src="https://github.com/user-attachments/assets/4a7b98de-a222-4a12-a912-fa8ce0b1c458" />


## 7. Business Recommendations

Based on the customer segments identified, businesses can consider the following strategies:

| Customer Segment | Recommended Strategy |
|---|---|
| High Value Customers | Reward loyalty and encourage referrals. |
| Loyal Customers | Introduce loyalty programmes and exclusive offers. |
| Potential New Customers| Develop onboarding and engagement campaigns.Encourage repeat purchases through personalized promotions. |
| At Risk | Use targeted win-back campaigns. |
| Lost Customers | Evaluate reactivation opportunities through low-cost campaigns. |
| Cannot Lose Them | Offer personalized incentives to encourage re-engagement. |
| Hibernating | Reintroduce products through relevant promotions. |


## 8. Project Structure

```text
Customer-Segmentation-RFM/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── RFM_Analysis.ipynb
│
├── visualizations/
│   └── charts/
│
├── README.md
└── requirements.txt
```


## 9. How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/klay-10/RFM-customer-segmentation-/tree/main
```

2. Navigate to the project directory:

```bash
cd Customer-Segmentation-RFM
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the notebook cells sequentially to reproduce the analysis.

Alternatively, open the notebook directly in Google Colab.

## 10. Conclusion

This project demonstrates how transactional data can be transformed into meaningful customer insights through Exploratory Data Analysis and RFM-based customer segmentation.

By understanding differences in customer purchasing behaviour, businesses can move beyond generic marketing strategies and adopt more targeted approaches to customer engagement, retention, and revenue growth.

**The ultimate goal is to turn data into decisions that create business value.**
