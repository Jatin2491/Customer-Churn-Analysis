# Telco Customer Churn Analysis


## Project Visualizations

### Customer Churn Distribution
<img width="471" height="470" alt="image" src="https://github.com/user-attachments/assets/770c3535-5113-45c1-9d44-f2f8b64075f7" />

### Contract Type vs Churn
<img width="471" height="470" alt="image" src="https://github.com/user-attachments/assets/09ca5d0b-613b-421c-bc2c-a5a20a7625bd" />

### Services vs Churn
<img width="1480" height="1490" alt="image" src="https://github.com/user-attachments/assets/28449489-e52a-4ebf-bee8-b4b83c13d4d2" />


## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Customer Segmentation
- Business Insights Generation
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn


## Overview

Customer churn is a critical challenge in the telecom industry, directly impacting revenue and customer acquisition costs. This project analyzes customer demographics, service subscriptions, billing information, contract details, and payment behavior to identify the key factors contributing to customer churn.

Using Exploratory Data Analysis (EDA), the project uncovers actionable insights that can help telecom companies improve customer retention and reduce customer attrition.

---

## Objectives

- Analyze customer churn patterns and trends.
- Identify the major factors influencing customer attrition.
- Evaluate the impact of demographics, contracts, services, and payment methods on churn.
- Generate business recommendations to improve customer retention.

---

## Dataset Information

The dataset contains information on **7,043 telecom customers** and includes:

- Customer Demographics
- Phone Services
- Internet Services
- Contract Details
- Billing Information
- Payment Methods
- Customer Tenure
- Monthly Charges
- Total Charges
- Churn Status

### Target Variable

**Churn**
- Yes → Customer Left
- No → Customer Retained

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Converted data types
- Cleaned the `TotalCharges` column
- Replaced blank values for customers with zero tenure
- Handled categorical variables
- Performed data validation checks

---

## Key Findings

### Overall Customer Churn

- **73.46%** of customers remain with the company.
- **26.54%** of customers have churned.

This means approximately **1 out of every 4 customers leaves the company**, making customer retention a significant business concern.

---

### Demographic Analysis

#### Gender

- Male and female customers show nearly identical churn behavior.
- Gender is not a significant factor affecting customer retention.

#### Senior Citizens

- Senior Citizens represent **16.2%** of customers.
- Non-Senior Citizens represent **83.8%** of customers.

Senior citizens exhibit a relatively higher churn rate compared to non-senior customers.

---

### Customer Tenure Analysis

Customer tenure emerged as one of the strongest indicators of churn.

#### Key Observations

- Customers with **1–2 months tenure** show the highest churn frequency.
- Churn decreases significantly as tenure increases.
- Long-term customers are considerably more loyal.

#### Business Insight

The first few months of the customer lifecycle are the most critical period for retention efforts.

---

### Contract Type Analysis

Contract type has a strong influence on customer churn.

#### Findings

- Month-to-Month contracts show the highest churn.
- One-Year contracts have significantly lower churn.
- Two-Year contracts exhibit the lowest churn rates.

#### Business Insight

Customers with long-term contracts are less likely to switch providers.

---

### Internet Service Analysis

Internet service type shows a strong relationship with churn.

#### Findings

- Fiber Optic customers demonstrate the highest churn levels.
- DSL customers show lower churn rates.
- Customers without internet service have the lowest churn.

#### Business Insight

Fiber Optic customers may be experiencing service quality, pricing, or satisfaction issues that require further investigation.

---

### Value-Added Services Analysis

The following services were analyzed:

- Online Security
- Online Backup
- Device Protection
- Tech Support

#### Findings

Customers without these services are significantly more likely to churn.

Customers subscribed to these services demonstrate better retention and loyalty.

#### Business Insight

Security and support services increase customer dependency on the platform and improve overall customer satisfaction.

---

### Entertainment Services Analysis

Services analyzed:

- Streaming TV
- Streaming Movies

#### Findings

These services show a relatively weaker relationship with churn compared to support and security services.

---

### Payment Method Analysis

Payment behavior emerged as another important churn indicator.

#### Findings

Customers using:

- Electronic Check

show the highest churn levels compared to customers using:

- Credit Cards
- Bank Transfers
- Automatic Payments

#### Business Insight

Automated payment methods are associated with better customer retention.

---

## Major Drivers of Churn

The analysis identified the following key churn drivers:

- Short Customer Tenure
- Month-to-Month Contracts
- Fiber Optic Internet Service
- Lack of Online Security
- Lack of Online Backup
- Lack of Device Protection
- Lack of Tech Support
- Electronic Check Payment Method
- Senior Citizen Customer Segment

---

## Business Recommendations

### 1. Strengthen Customer Onboarding

Focus on retaining customers during their first 90 days through:

- Welcome campaigns
- Personalized support
- Customer engagement initiatives

### 2. Promote Long-Term Contracts

Encourage customers to switch from Month-to-Month plans by offering:

- Discounts
- Loyalty rewards
- Bundled packages

### 3. Increase Adoption of Support Services

Promote:

- Online Security
- Online Backup
- Device Protection
- Tech Support

through targeted marketing and bundled offerings.

### 4. Improve Fiber Optic Customer Experience

Investigate:

- Service reliability
- Pricing concerns
- Customer support issues
- Network performance

### 5. Encourage Automated Payments

Provide incentives for customers to adopt:

- Credit Card Auto-Pay
- Bank Transfer Auto-Pay

to reduce churn risk.

---

## Conclusion

The analysis reveals that customer churn is primarily driven by customer engagement, service utilization, contract commitment, and payment behavior rather than demographic characteristics.

The strongest churn indicators include:

- Short customer tenure
- Month-to-Month contracts
- Fiber Optic internet service
- Lack of security and support services
- Electronic Check payment method

By implementing targeted retention strategies focused on these areas, telecom companies can significantly reduce churn, improve customer satisfaction, and maximize long-term revenue growth.

---

##  Author

**Jatin Arora**

Data Analytics | Python | SQL | Power BI | Customer Churn Analysis | Exploratory Data Analysis (EDA)
