# Sales Exploratory Data Analysis

Welcome to the **Sales Exploratory Data Analysis** project! This repository showcases a complete data analysis workflow using real-world Indian e-commerce festival sales data, with all steps implemented in **Python** leveraging **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib**.

---

## 📋 Project Overview

This project aims to:
- Perform **end-to-end exploratory data analysis (EDA)** on Diwali sales data
- Clean and preprocess raw transaction data
- Analyze **customer demographics, purchasing patterns, product performance,** and **sales trends**
- Visualize insights through effective charts and summary tables

The results provide actionable business intelligence for retail/festive e-commerce campaigns.

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

## 🛠️ Tools Used

- **Python** (Jupyter Notebook)
- **Pandas & NumPy** (data processing)
- **Matplotlib & Seaborn** (data visualization)

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


