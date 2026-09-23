# 🪔 Diwali Sales Analysis (Exploratory Data Analysis)

An end-to-end Exploratory Data Analysis (EDA) project focused on analyzing consumer purchasing behavior during the Diwali festival. This project cleans raw transactional data, discovers demographic and regional purchasing trends, and translates data insights into actionable business strategies for maximizing sales and inventory planning.

## 📌 Table of Contents

* [Project Overview](#-project-overview)

* [Dataset Overview](#-dataset-overview)

* [Key Business Questions Answered](#-key-business-questions-answered)

* [Key Insights & Findings](#-key-insights--findings)

* [Actionable Recommendations](#-actionable-recommendations)

* [Tech Stack & Libraries](#-tech-stack--libraries)

* [Project Structure](#-project-structure)

* [How to Run the Project](#-how-to-run-the-project)

* [Author & Connect](#-author--connect)

## 🎯 Project Overview

During festive seasons like Diwali, retail businesses experience heavy demand fluctuations across different product categories and customer demographics. The objective of this project is to:

1. Perform **Data Cleaning and Preprocessing** (handling null values, data type casting, and anomaly treatment).

2. Conduct **Exploratory Data Analysis (EDA)** using visualization tools.

3. Identify top-performing customer segments (by gender, age, marital status, occupation, and state).

4. Provide data-driven business insights to enhance targeted marketing and inventory distribution.

## 📂 Dataset Overview

The dataset contains customer order records with demographic and product-level details.

| **Column Name** | **Description** | 
| `User_ID` | Unique customer identifier | 
| `Cust_name` | Name of the customer | 
| `Product_ID` | Unique product identifier | 
| `Gender` | Gender of the customer (`M` / `F`) | 
| `Age Group` | Age cohort (e.g., `18-25`, `26-35`, `36-45`) | 
| `Age` | Exact age of the customer | 
| `Marital_Status` | Marital status indicator (`0` or `1`) | 
| `State` | State in India where the purchase was made | 
| `Zone` | Geographic zone (`Central`, `Southern`, `Western`, `Northern`, `Eastern`) | 
| `Occupation` | Professional background (e.g., `IT Sector`, `Healthcare`, `Banking`) | 
| `Product_Category` | Category of the purchased item (`Food`, `Clothing`, `Electronics`, etc.) | 
| `Orders` | Total quantity ordered | 
| `Amount` | Total transaction amount (in INR) | 

## 🔍 Key Business Questions Answered

* **Gender Dynamics:** Who spends more on average and overall—men or women?

* **Age Distribution:** Which age group drives the largest share of sales?

* **Geographic Trends:** Which states generate the highest revenue and order volume?

* **Marital Demographics:** How does marital status impact overall purchasing power?

* **Sector Analysis:** Which occupational sectors have the highest purchasing capacity?

* **Product Demand:** What are the most sold and highest revenue-generating product categories?

## 💡 Key Insights & Findings

1. **Buyer Demographics:**

   * **Gender:** Female buyers significantly outnumber male buyers in both order count and total purchasing power (\~65%+ of overall sales).

   * **Age Group:** The most dominant customer demographic is between **26–35 years old**, accounting for the majority of total sales.

   * **Marital Status:** Married individuals exhibit significantly higher purchasing power compared to unmarried customers.

2. **Geographical Performance:**

   * The top 3 revenue-generating states are **Uttar Pradesh**, **Maharashtra**, and **Karnataka**.

   * Central and Southern zones contribute the largest chunks of orders.

3. **Occupation & Spending Power:**

   * Customers working in the **IT Sector**, **Healthcare**, and **Banking/Aviation** have the highest average ticket size and overall spending volume.

4. **Product Categories:**

   * Highest sales volume and revenue come from **Food**, followed by **Clothing & Apparel**, and **Electronics & Gadgets**.

> **Summary Customer Persona:**
>
> The highest-value buyer profile is a **married female, aged 26–35, residing in Uttar Pradesh, Maharashtra, or Karnataka, working in IT/Healthcare, purchasing Food, Clothing, and Electronics**.

## 🚀 Actionable Recommendations

* **Targeted Advertising:** Allocate the majority of ad budgets toward married women aged 26–35 across digital platforms (Instagram, Meta, Google Ads).

* **Localized Campaigns:** Run targeted regional offers and local vernacular ad campaigns in Uttar Pradesh, Maharashtra, and Karnataka.

* **Cross-Selling & Bundling:** Bundle high-demand categories (e.g., complimentary Festive Food hampers with Apparel purchases) to increase Average Order Value (AOV).

* **Corporate & Festive Tie-ups:** Partner with IT and healthcare companies for festive corporate gifting programs.

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x

* **Data Manipulation:** `pandas`, `numpy`

* **Data Visualization:** `matplotlib`, `seaborn`

* **Development Environment:** Jupyter Notebook / VS Code

## 📁 Project Structure

```
├── Diwali Sales Data.csv        # Raw dataset in CSV format
├── Diwali_Sales_Analysis.ipynb  # Jupyter Notebook containing data cleaning, charts, and EDA
└── README.md                    # Project documentation and summary

```

## ⚙️ How to Run the Project

1. **Clone this repository:**

   ```
   git clone https://github.com/your-username/diwali-sales-analysis.git
   cd diwali-sales-analysis
   
   ```

2. **Install required dependencies:**

   ```
   pip install pandas numpy matplotlib seaborn jupyter
   
   ```

3. **Launch Jupyter Notebook:**

   ```
   jupyter notebook
   
   ```

4. Open `Diwali_Sales_Analysis.ipynb` and click **Run All** to reproduce the analysis and plots.

## 👤 Author & Connect

* **Author:** \[Your Name\]

* **LinkedIn:** \[Your LinkedIn Profile URL\]

* **GitHub:** [@your-username](https://github.com/your-username?utm_source=gemini)

* **Portfolio / Email:** \[Your Email or Website\]
