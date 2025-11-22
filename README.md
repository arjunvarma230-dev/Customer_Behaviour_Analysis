# Customer_Behaviour_Analysis
End-to-end data analytics project analyzing customer behaviour using Python, SQL, and Power BI. Includes data cleaning, EDA, SQL business insights, and an interactive dashboard.
# **Customer Behavior Analysis — End-to-End Data Analytics Project**

## **Overview**
This project demonstrates a complete end-to-end data analytics workflow, starting from raw data and ending with insights delivered through SQL analysis, Power BI dashboards, and a final report.  
It includes:

- **Loading and exploring data in Python**
- **Data cleaning and preprocessing**
- **Performing SQL analysis using MySQL / SQL Server**
- **Building an interactive Power BI dashboard**
- **Creating a structured report and presentation (Gamma)**

The objective is to analyze **customer shopping behavior** and uncover insights related to spending patterns, demographics, product preferences, subscription trends, and discount usage.

---

## **Dataset**

| **Attribute** | **Description** |
|---------------|------------------|
| **Rows** | 3,900 |
| **Columns** | 18 |
| **File Type** | Customer purchase and behavior dataset |
| **Missing Values** | 37 missing values in the `review_rating` column |

### **Key Columns**
- **age**, **gender**, **location**, **subscription_status**
- **item_purchased**, **category**, **purchase_amount**
- **season**, **size**, **color**
- **discount_applied**, **previous_purchases**, **review_rating**
- **shipping_type**

---

## **Tools & Technologies**

| **Category** | **Tools Used** |
|--------------|----------------|
| **Programming** | Python |
| **Libraries** | pandas, numpy, matplotlib |
| **Databases** | MySQL / SQL Server |
| **Visualization** | Power BI |
| **Presentation** | Gamma |
| **Version Control** | Git & GitHub |

---

## **Project Steps**

### **1. Data Loading (Python)**
- Loaded the dataset using **pandas**
- Inspected structure using **df.info()**
- Reviewed summary statistics with **df.describe()**

### **2. Exploratory Data Analysis (EDA)**
- Univariate and bivariate exploration
- Analyzed demographic distributions and purchasing trends
- Visualized review ratings, shipping preferences, and category performance

### **3. Data Cleaning**
- Imputed missing values in `review_rating` using median rating per category
- Renamed columns to **snake_case** for consistency
- Removed redundant fields such as **promo_code_used**
- Created new features:
  - **age_group** (categorizing customers)
  - **purchase_frequency_days**

### **4. SQL Analysis**
Performed structured analysis after loading cleaned data into MySQL / SQL Server:

- **Revenue by gender**
- **High-spending discount users**
- **Top 5 highest-rated products**
- **Shipping type comparison**
- **Subscribers vs. non-subscribers**
- **Products with high discount dependency**
- **Customer segmentation (new, returning, loyal)**
- **Top 3 products per category**
- **Repeat buyers & subscription correlation**
- **Revenue by age group**

### **5. Power BI Dashboard**
- Built a fully interactive dashboard
- Included revenue breakdowns, category contributions, customer segments, rating trends, and shipping analysis
- Enabled drill-down functionality for deeper exploration

### **6. Report & Presentation**
- Created a detailed written report summarizing the entire project
- Designed a clean and structured presentation using **Gamma**

---

## **Key Insights**
- Subscribers consistently spent more compared to non-subscribers
- Discount users displayed higher purchase frequency in certain categories
- Express shipping customers tended to have higher purchase amounts
- Highly rated products correlated with repeat purchases
- Certain age groups contributed significantly more revenue

---

## **How to Run This Project**

### **1. Clone the Repository**
