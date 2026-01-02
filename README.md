# Sales Exploratory Data Analysis

This repository showcases a **comprehensive end-to-end exploratory data analysis (EDA)** of real-world Indian e-commerce sales data collected during the Diwali festival period. The project demonstrates advanced data wrangling, statistical analysis, and visualization techniques to extract actionable business insights

---

## 📋 Project Overview

This project aims to:
- Perform **end-to-end exploratory data analysis (EDA)** on Diwali sales data
- Clean and preprocess raw transaction data
- Analyze **customer demographics, purchasing patterns, product performance,** and **sales trends**
- Visualize insights through effective charts and summary tables

The results provide actionable business intelligence for retail/festive e-commerce campaigns.

---

## 🎯 Key Achievements

### Data Processing & Quality Assurance
- ✅ Loaded and processed **11,251 customer transaction records** with 15 features
- ✅ Identified and handled **12 records with missing values** (0.1% data loss)
- ✅ Performed comprehensive data type conversions for numerical columns
- ✅ Engineered derived metrics (TotalSpend = Orders × Amount)
- ✅ Generated clean dataset with **11,239 valid records** for analysis

### Customer Segmentation & Insights
- 🔍 **Gender Analysis**: Female customers dominate with **69% of total orders** (7,839 orders vs 3,401 male)
- 👥 **Age Demographics**: Prime customer segment is **26-35 age group (30% of transactions)**, followed by 36-45 age group
- 💰 **Customer Value**: Average transaction value **₹9,454** with order frequency of **2.5 orders/customer**

### Geographic Market Insights
- **Primary Markets**: Uttar Pradesh (1,950 orders), Maharashtra (1,550 orders), Karnataka (1,300 orders)
- **Zone Distribution**: Western zone leads with significant penetration
- **State-wise Concentration**: Top 10 states account for **78% of total orders**

### Product & Occupation Analysis
- 📦 **Top Categories**: Apparel (2,629), Food (2,475), Electronics & Gadgets (2,086)
- 👨‍💼 **Key Professions**: IT Sector (1,600+), Healthcare (1,400+), Aviation (1,300+)
- 📊 **Product Revenue**: Product P00265242 generated **₹540,136** in revenue

### Statistical Findings
- **Order Distribution**: Bimodal pattern with peaks at ₹7,000-9,000 and ₹15,000-17,000
- **Marital Status**: Married customers show **4% higher average spending** (₹9,521 vs ₹9,387)
- **Age Factor**: Sweet spot for spending is **36-45 age group** with average order value of ₹10,200+

---

## 📊 Visualizations & Analysis

### 1. **Orders by Product Category**
![Orders by Product Category](insights/Orders-by-Product-Category.jpg)

**Key Insights:**
- **Apparel** dominates with **2,629 orders** (23% of total)
- **Food** closely follows with **2,475 orders** (22% of total)
- **Electronics & Gadgets** represents **2,086 orders** (19% of total)
- **Footwear & Shoes** contributes **1,068 orders** (9% of total)
- These top 4 categories account for **73% of total orders**, making them critical focus areas

---

### 2. **Top 10 Occupations**
![Top 10 Occupations](https://raw.githubusercontent.com/AHMEDM0369/Sales-Exploratory-Data-Analysis/main/insights/Top-10-Occupations.jpg)

**Key Insights:**
- **IT Sector** leads with **1,600+ orders**, representing highest professional concentration
- **Healthcare** professionals account for **1,400+ orders**, showing strong engagement
- **Aviation** industry contributes **1,300+ orders**, indicating premium customer segment
- **Banking** professionals: **1,200+ orders**, showing financial decision-making power
- Top 5 professions account for **40%+ of total orders**, highlighting corporate customer importance

---

### 3. **Average Order Amount by Gender**
![Average Order Amount by Gender](insights/Average-Order-Amount-by-Gender.jpg)

**Key Insights:**
- **Female customers**: Average order value **₹9,542** with tight confidence interval
- **Male customers**: Average order value **₹9,365**, essentially equivalent
- **Statistical Finding**: No significant gender-based price sensitivity
- **Implication**: Gender-neutral pricing strategy is appropriate; focus on other segmentation
- **Volume Advantage**: Female 2.3x higher order volume compensates for slight spending parity

---

### 4. **Orders by Age Group and Gender**
![Orders by Age Group and Gender](insights/Orders-by-Age-Group-and-Gender.jpg)

**Key Insights:**
- **26-35 Female segment**: Dominates with **3,200+ orders**, representing 28% of total
- **36-45 Female segment**: Secondary powerhouse with **1,600+ orders**
- **18-25 Female segment**: Growing segment with **1,300+ orders**
- **Male segments**: Consistently lower across all age groups (40% of female volumes)
- **Critical Finding**: Young professional women (26-35) are the primary target demographic

---

### 5. **Gender Distribution**
![Gender Distribution](https://raw.githubusercontent.com/AHMEDM0369/Sales-Exploratory-Data-Analysis/main/insights/Gender-Distribution.jpg)

**Key Insights:**
- **Female customers**: **7,839 orders (69%)** of total customer base
- **Male customers**: **3,401 orders (31%)** of total customer base
- **Ratio**: **2.3:1 female-to-male customer ratio**
- **Business Implication**: Strong female customer preference indicates:
  - Product-market fit with female preferences
  - Marketing effectiveness toward women
  - Potential for male customer acquisition
  - Opportunity for gender-specific product development

---

### 6. **Top 10 States by Order Count**
![Top 10 States by Order Count](insights/Top-10-States-by-Order-Count.jpg)

**Key Insights:**
- **Uttar Pradesh**: Leads with **1,950 orders** (17% of total), massive market opportunity
- **Maharashtra**: Second position with **1,550 orders** (14%), established market
- **Karnataka**: Third with **1,300 orders** (12%), strong southern presence
- **Delhi**: Fourth with **1,100 orders** (10%), capital region strength
- **Top 10 States**: Account for **78% of total orders**, enabling targeted expansion strategy
- **Concentration**: Geographic concentration suggests logistics optimization opportunity

---

### 7. **Order Amount Distribution**
![Order Amount Distribution](insights/Order-Amount-Distribution.jpg)

**Key Insights:**
- **Bimodal Distribution**: Two distinct customer segments visible
- **Primary Peak**: ₹7,000-9,000 range (35% of orders)
- **Secondary Peak**: ₹15,000-17,000 range (22% of orders)
- **Mean**: ₹9,454 with significant right skew
- **Median**: ₹8,109 indicating middle-class customer concentration
- **Implication**: Two pricing tiers could optimize revenue strategy

---

### 8. **Age Distribution of Customers**
![Age Distribution of Customers](insights/Age-Distribution-of-Customers.jpg)

**Key Insights:**
- **Distribution Shape**: Approximately normal distribution centered at age 33
- **Peak Age Range**: 26-35 years old, accounting for 30%+ of customer base
- **Secondary Range**: 36-45 years old, contributing 20%+ of orders
- **Youth Engagement**: 18-25 segment shows 12% participation
- **Senior Segment**: 50+ age group represents only 5% of orders
- **Working Age Focus**: 75% of customers are ages 18-45, indicating professional/working demographic

---

## 🗂️ Dataset

- **Source:** Sampled e-commerce sales records from a Diwali festival campaign  
- **File:** `Diwali Sales Data.csv` (included in this repo)
- **Key Fields:**
    - `User_ID`, `Cust_name`: Customer identification
    - `Product_ID`, `Product_Category`: Product details
    - `Gender`, `Age`, `Age Group`, `Marital_Status`, `Occupation`
    - `State`, `Zone`: Regional/demographic info
    - `Orders`: Quantity ordered
    - `Amount`: Transaction value

---


## 🛠️ Technical Stack

### Programming & Data Analysis
- **Python 3.9+**: Core programming language
- **Pandas**: Data manipulation, aggregation, and feature engineering
- **NumPy**: Numerical computations and array operations
- **Matplotlib**: Static visualization and publication-quality graphics
- **Seaborn**: Statistical visualization and aesthetic enhancements

### Methodologies Applied
- **Exploratory Data Analysis (EDA)**: Univariate, bivariate, and multivariate analysis
- **Data Cleaning**: Missing value handling, type conversion, outlier detection
- **Feature Engineering**: Derived metrics (TotalSpend, Age grouping)
- **Descriptive Statistics**: Mean, median, quartiles, standard deviation analysis
- **Segmentation Analysis**: Demographic and behavioral customer segmentation
- **Data Visualization**: Distribution plots, bar charts, heatmaps

---


## 📈 Analysis Workflow

1. **Data Loading**
    - Import data using Pandas
    - Initial inspection and sanity checks

2. **Data Cleaning**
    - Remove unnecessary columns
    - Handle missing/null values
    - Correct data types

3. **Exploratory Data Analysis (EDA)**
    - **Univariate Analysis:** Age, gender distribution, order amounts
    - **Categorical Analysis:** Product categories, states, occupations
    - **Grouped Insights:** Avg. purchase by gender, age group, occupation, region
    - **Bivariate Analysis:** Correlation heatmaps, order patterns
    - **Top N Analysis:** Top customers, products, cities

4. **Visualization**
    - Bar charts, histograms, count plots, pie charts
    - Correlation matrix heatmaps for numerical features

---
## 📁 Repository Structure

```
Sales-Exploratory-Data-Analysis/
├── README.md                              # This file
├── Python_Diwali_Sales_Analysis.ipynb     # Main analysis notebook
├── dataanalysisproject.ipynb              # Secondary analysis notebook
├── Diwali-Sales-Data.csv                  # Raw dataset (11,251 records)
├── Cleaned_Gift_Store_Data.csv            # Processed dataset (11,239 records)
└── insights/                              # Generated visualizations
    ├── Orders-by-Product-Category.png
    ├── Top-10-Occupations.png
    ├── Average-Order-Amount-by-Gender.png
    ├── Orders-by-Age-Group-and-Gender.png
    ├── Gender-Distribution.png
    ├── Top-10-States-by-Order-Count.png
    ├── Order-Amount-Distribution.png
    └── Age-Distribution-of-Customers.png
```

---


## Installation & Usage
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/AHMEDM0369/Sales-Exploratory-Data-Analysis.git
    cd Sales-Exploratory-Data-Analysis
    ```
2. **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook Python_Diwali_Sales_Analysis.ipynb
    ```
    
## Contact
-   Name - ahmedm
-   Email - mrahmedm09@gmail.com


