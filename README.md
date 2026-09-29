# 📊 PhonePe Transactions Analysis | Power BI

An interactive Power BI dashboard built to analyze PhonePe transaction data and uncover meaningful insights into transaction performance, payment status, service usage, user demographics, and monthly trends.

The project focuses on transforming raw transaction and user data into an interactive business intelligence dashboard using Power BI, DAX, data modeling, and data visualization techniques.

---

## 🎯 Project Objective

The main objective of this project is to analyze PhonePe transaction data and answer important business questions such as:

- How are transactions performing over time?
- What is the total transaction value?
- What percentage of transactions are successful?
- Which services contribute the most transaction value?
- How are users distributed across different age groups?
- How does transaction performance vary across services and age segments?
- How does transaction value change month-over-month?
- What are the major payment status patterns?

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Data Visualization**
- **Microsoft Excel / CSV Dataset**

---

## 📁 Dataset Structure

The Power BI data model contains multiple tables:

### All_Transactions
Contains transaction-level information such as:

- Transaction ID
- User ID
- Date
- Amount
- Payment Status
- Reason
- Service
- Service Type

### All_Users
Contains user-related information such as:

- User ID
- Name
- Age
- Age Group
- Join Date

### Date_Table
A dedicated date dimension used for time-based analysis created by using DAX formulas.

It contains:

- Date
- Day Name
- Day Number
- Month Name
- Month Number
- Quarter
- Weekend
- Year

### Measures
A separate table was created to organize the DAX measures used in the dashboard.

---

## 🔗 Data Model

A relational data model was created in Power BI to connect transaction, user, and date information.

The model uses:

- **All_Users** → User information
- **All_Transactions** → Transaction information
- **Date_Table** → Time intelligence and date-based analysis
- **Measures** → DAX calculations

The Date Table enables monthly, quarterly, and yearly analysis, while relationships between users and transactions allow user-level analysis.

---

## 📈 Dashboard Overview

The dashboard provides a single-page interactive view of PhonePe transaction performance.

### Key Performance Indicators

The dashboard displays:

- **Total Transactions:** 300K
- **Total Transaction Value:** ₹3.47B
- **Unique Users:** 108K
- **Successful Transaction Rate:** 95.93%

These KPIs provide a quick overview of overall transaction performance.

---

## 📊 Dashboard Visualizations

### 1. Transactions Analysis Over Time

A monthly trend visualization comparing:

- Total Transactions
- Total Transaction Amount

This helps identify changes and patterns in transaction activity throughout the year.

### 2. User Age Group Distribution

A demographic analysis showing the distribution of users across:

- Young Adult
- Mature Adult
- Middle Aged
- Old Aged

This provides insight into the composition of the user base.

### 3. Transaction Value MoM Growth

A month-over-month growth analysis showing how transaction value changes compared with the previous month.

This helps identify periods of positive and negative transaction value growth.

### 4. Payment Status of Transactions

A comparison of successful and failed transactions to understand overall payment performance.

### 5. Transaction Value by Service

Analyzes transaction value generated across different PhonePe services, including:

- Loans
- Insurance
- Money Transfer
- Recharge Bills

This helps compare the contribution of different service categories.

### 6. Service Payment Rate by Age Segment

A stacked analysis comparing service payment performance across different age segments.

This helps understand how different user groups interact with various services.

---

## 🧮 DAX & Calculations

DAX measures were created to calculate important business metrics such as:

- Total Transactions
- Total Transaction Amount
- Total Users
- Successful Transactions
- Successful Transaction Rate
- Transaction Amount MoM Growth
- Monthly transaction metrics

Time-based calculations were implemented using the dedicated Date Table.

---

## 🔍 Key Insights

The dashboard highlights several important observations:

- The dataset contains approximately **300K transactions**.
- The total transaction value analyzed is approximately **₹3.47 billion**.
- The dashboard contains approximately **108K unique users**.
- The overall successful transaction rate is approximately **95.93%**.
- Transaction activity varies across different months.
- Different services contribute different levels of transaction value.
- The user base is distributed across multiple age segments, with **Middle Aged users representing the largest segment** in the analyzed dataset.
- Month-over-month analysis reveals periods of both positive and negative transaction value growth.

> Note: These insights are based on the dataset used in this project and are not intended to represent official PhonePe company statistics.

---

## 📸 Dashboard Preview

![PhonePe Power BI Dashboard](Phonepe%20transaction%20analysis%20dashboard.png)

---

## 🧠 Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- DAX
- Time Intelligence
- KPI Development
- Interactive Dashboard Design
- Data Visualization
- Business Analysis
- User Segmentation
- Trend Analysis
- Month-over-Month Analysis

---

## 💼 Business Value

The dashboard demonstrates how transaction and customer data can be transformed into actionable business insights.

Such analysis can help businesses understand:

- Transaction performance
- Customer demographics
- Service adoption
- Payment success rates
- Monthly growth patterns
- User behavior across different segments

---

## 🚀 Project Outcome

This project strengthened practical skills in Power BI, DAX, data modeling, and business-oriented data analysis by converting raw transaction data into an interactive analytical dashboard.

---
