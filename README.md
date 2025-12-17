# Customer Churn Analysis Dashboard

## Data Analysis & Visualization Project

### Introduction

This Customer Churn Analysis dashboard is developed to analyze customer behavior, churn patterns, service usage, billing methods, and contract types within a telecommunications company.

The goal of this project is to apply the **Ask, Prepare, Process, Analyze, Share, Act** framework to uncover churn drivers and support data-driven customer retention and revenue optimization strategies.

---

## Background of Study

The dataset contains customer-level information including demographics, subscription details, services used, billing information, support tickets, and churn status.

This project evaluates churn risk across the entire customer lifecycle—from onboarding and contract selection to service usage, billing, and long-term retention.

---

## 1. Ask

### Business Task

Identify customer segments with high churn risk and determine key factors contributing to customer attrition.

### Key Questions

* Which customers are most likely to churn?
* How do contract type and subscription duration affect churn?
* Which payment methods are associated with higher churn rates?
* Does internet service type influence churn behavior?
* What is the revenue impact of churned customers?

### Key Stakeholders

* **Customer Retention & Marketing Team** – Focus on reducing churn and improving customer loyalty.
* **Product & Service Teams** – Improve service offerings and customer experience.
* **Business & Revenue Managers** – Assess financial impact and prioritize high-risk segments.

---

## 2. Prepare

### **Data Source**

Public telecommunications churn dataset containing:

* Customer demographics (gender, senior citizen, partner, dependents)
* Subscription tenure
* Contract type
* Internet and service subscriptions
* Payment method and billing preferences
* Monthly and total charges
* Tech and admin support tickets
* Churn indicator (Yes / No)

### **Tools Used**

* **Power BI** – Data modeling and interactive dashboard creation
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculated KPIs

### **Data Integrity (ROCCC Principles)**

* **Reliable** – Widely used telecom churn dataset
* **Original** – Sourced directly from public dataset
* **Comprehensive** – Covers customer, service, billing, and churn attributes
* **Current** – Static dataset used for analytical practice
* **Cited** – Public dataset

---

## 3. Process

### **Data Preparation & Cleaning**

* Validated churn labels and contract categories
* Standardized subscription tenure into meaningful ranges
* Handled missing values in billing and service fields
* Created calculated fields for:

  * Churn rate (%)
  * Customers at risk
  * Monthly and yearly revenue
  * Average monthly charges
  * Support ticket counts

---

## 4. Analyze

This section summarizes insights from both dashboard pages: **Churn Overview** and **Customer Risk Analysis**.

---

### **Page 1: Churn Overview Dashboard**

#### **Overall Churn & Revenue Impact**

* **26.54% churn rate** across all customers
* High revenue loss driven by churned customers with short tenure
* Customers at risk contribute significantly to monthly revenue

#### **Contract Type Analysis**

* **Month-to-month contracts** show the highest churn rate
* One-year and two-year contracts demonstrate better customer retention

#### **Payment Method**

* **Electronic check** customers have the highest churn proportion
* Automatic payment methods (bank transfer & credit card) show lower churn

#### **Subscription Duration**

* Customers with **< 1 year tenure** show the highest churn rate
* Churn decreases as subscription length increases

#### **Internet Service Type**

* **Fiber optic** customers experience higher churn compared to DSL

---

### **Page 2: Customer Risk Analysis**

#### **Churn by Internet Service**

* Fiber optic users show the highest churn rate
* DSL customers demonstrate more stable retention

#### **Churn by Contract & Tenure**

* Month-to-month customers dominate churn population
* Long-term contracts correlate with reduced churn risk

#### **Revenue & Support Tickets**

* High churn segments generate a large share of monthly charges
* Customers with more tech and admin tickets tend to show higher churn risk

---

## 5. Share

### **Dashboard Pages**

**Page 1 – Churn Dashboard:**
✔ Customers at risk overview
✔ Revenue impact (monthly & yearly charges)
✔ Contract type distribution
✔ Payment method analysis
✔ Subscription time analysis

**Page 2 – Customer Risk Analysis:**
✔ Overall churn rate
✔ Churn by internet service
✔ Churn by contract type
✔ Churn by payment method
✔ Revenue contribution by churn segment

These pages enable stakeholders to explore churn drivers interactively using filters and slicers.

---

## 6. Act

### Recommendations to Reduce Churn

1. **Encourage Long-Term Contracts**

   * Offer incentives for customers to move from month-to-month to annual plans.

2. **Target High-Risk Payment Methods**

   * Promote automatic payment options to electronic check users.

3. **Improve Fiber Optic Customer Experience**

   * Investigate service quality and support issues contributing to higher churn.

4. **Early Retention for New Customers**

   * Implement onboarding and engagement programs within the first year.

5. **Reduce Support Ticket Volume**

   * Improve self-service and proactive customer support.

---

## 7. Conclusion

This Customer Churn Analysis highlights how contract structure, payment method, subscription tenure, and service type strongly influence customer retention.

While short-term and electronic payment customers show higher churn, long-term contracts and automated billing demonstrate better retention and revenue stability.

The dashboard provides actionable insights that support proactive churn prevention and customer lifetime value optimization.

---

### 📌 **Project by:**

**Waiyan Htun**
– Customer Churn Analytics Project

* Download **"Customer Churn Analysis Dashboard.pbix"** and open in Power BI to view the dashboard (internal / academic use only).
