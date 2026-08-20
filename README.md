# 📦 Supply Chain Analysis | Python

> An end-to-end supply chain analytics project focused on sales performance, shipping operations, customer behavior, profitability, and regional trends using Python.

---

## 📊 Overview

As someone transitioning into data analytics, I wanted to work on a real-world business problem that reflects the challenges analysts face in supply chain and retail operations.

This project analyzes the **DataCo Supply Chain Dataset** to understand how sales, profitability, customer segments, product categories, shipping methods, delivery performance, and geographic factors influence overall supply chain performance.

The analysis covers the complete analytical workflow from **data cleaning and exploratory data analysis to feature engineering, statistical analysis, visualization, and business recommendations**. The notebook uses Python libraries including Pandas, NumPy, Matplotlib, and Seaborn to investigate operational patterns and translate them into business insights.

The dataset contains **180,519 records across 53 columns**, covering orders, customers, products, sales, delivery, shipping, markets, regions, product categories, customer segments, and profitability.

---

## 🎯 Business Problem

Supply chain operations involve several interconnected business factors. Poor performance in any one area can affect customer experience, operating efficiency, revenue, and profitability.

This project focuses on analyzing key supply chain challenges including:

- Delivery delays and order fulfillment performance
- Shipping efficiency across different shipping methods
- Sales and profitability across product categories
- Customer segment performance and purchasing behavior
- Geographic differences in sales and operational performance
- Regional supply chain trends
- Factors associated with late deliveries and operational inefficiencies
- Opportunities to improve inventory planning and overall supply chain performance

The goal is to use data to identify meaningful patterns, understand potential operational issues, and provide actionable recommendations that can support better business decision-making.

---

## 🚀 Project Objectives

The analysis aims to:

1. Analyze overall sales and order performance.
2. Evaluate delivery and shipping performance.
3. Identify patterns associated with late deliveries.
4. Compare performance across different shipping modes.
5. Analyze sales and profitability across product categories.
6. Evaluate customer segment performance.
7. Analyze geographic and regional sales distribution.
8. Investigate factors associated with supply chain performance.
9. Perform exploratory and statistical analysis to identify meaningful business patterns.
10. Translate analytical findings into actionable business recommendations.

---

## 🗂️ Dataset

The project uses the **DataCo Supply Chain Dataset**.

### Dataset Size

- **180,519 records**
- **53 columns**
- Approximately **91 MB** as stored in this repository

### Dataset Covers

- Orders
- Customers
- Products
- Sales
- Delivery
- Shipping
- Markets
- Regions
- Product categories
- Customer segments
- Profitability

The raw dataset is available in:

```text
 dataset/DataCoSupplyChainDataset.csv
```

---

## 🛠️ Tools & Technologies

### Python

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Analysis

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Descriptive Statistics
- Statistical Analysis
- Correlation Analysis
- KPI Analysis
- Data Visualization

### Business Intelligence

- Microsoft Power BI
- Interactive Dashboard Development
- Business Reporting
- Data Storytelling

### Development

- Jupyter Notebook
- Git
- GitHub

---

## 📁 Project Structure

```text
Supply-chain-analysis-python/
│
├── README.md
│
├── dataset/
│   └── DataCoSupplyChainDataset.csv
│
├── notebook/
│   └── supply_chain_analysis.ipynb
│
└── supplychainanalysis.pdf
```

### Project Files

**`dataset/DataCoSupplyChainDataset.csv`**  
The raw DataCo supply chain dataset used throughout the analysis.

**`notebook/supply_chain_analysis.ipynb`**  
The main Python notebook containing data loading, cleaning, exploratory analysis, visualizations, statistical analysis, and business insights.

**`supplychainanalysis.pdf`**  
The project report containing the documented analysis and findings.

---

## 🧹 Data Cleaning & Preparation

The project begins by preparing the raw supply chain data for analysis.

The workflow includes:

- Inspecting the dataset structure and data types
- Identifying missing values
- Checking duplicate records
- Reviewing inconsistent or invalid records
- Converting variables into appropriate formats
- Creating analytical features required for supply chain analysis
- Examining sales, delivery, shipping, customer, product, and profitability variables
- Preparing the cleaned data for exploratory and statistical analysis

The objective is to ensure that the subsequent analysis is based on consistent and interpretable data.

---

## 🔍 Exploratory Data Analysis

The exploratory analysis investigates the major dimensions of supply chain performance.

### Sales Performance

Analysis of sales patterns across products, categories, customer segments, markets, and regions helps identify where revenue is being generated and where performance differs.

### Delivery Performance

Delivery-related variables are analyzed to identify late-delivery patterns and understand how shipping and order characteristics relate to fulfillment performance.

### Shipping Efficiency

Different shipping methods are compared to understand their relationship with delivery performance and operational efficiency.

### Customer Behavior

Customer segments and purchasing behavior are analyzed to identify differences in contribution and buying patterns.

### Regional Performance

Sales and operational metrics are examined across markets and geographic regions to identify regional differences and potential areas for improvement.

### Profitability

Profitability metrics are analyzed alongside sales and operational variables to understand whether higher sales necessarily translate into stronger business performance.

---

## 📈 Key Analysis Areas

The project focuses on the following analytical questions:

### 1. Sales and Revenue Performance

- Which products and categories generate the strongest sales?
- How does sales performance vary across regions and markets?
- Which customer segments contribute most to sales?

### 2. Delivery and Shipping Performance

- Which orders experience delivery delays?
- How does delivery performance differ by shipping method?
- What operational factors are associated with late deliveries?

### 3. Customer Behavior

- How do customer segments differ in sales contribution?
- Which segments demonstrate stronger purchasing activity?
- How does customer behavior vary across regions?

### 4. Product and Category Performance

- Which categories perform strongly in terms of sales and profitability?
- Are high-sales categories also highly profitable?
- Which products or categories require further attention?

### 5. Regional and Market Analysis

- Which markets and regions contribute the most to overall performance?
- Are there regional differences in delivery and sales performance?
- Where are potential operational improvement opportunities concentrated?

---

## 📊 Statistical & Analytical Methods

The project applies statistical and analytical techniques to move beyond simple descriptive reporting.

These include:

- Descriptive statistics
- Distribution analysis
- Correlation analysis
- Comparative analysis
- Outlier investigation
- Feature engineering
- KPI analysis
- Trend and pattern identification

The analysis is used to distinguish meaningful business patterns from isolated observations and to support data-driven recommendations.

---

## 💡 Business Insights

The analysis is designed to translate technical findings into practical business actions.

Key areas of recommendation include:

- Improving delivery and fulfillment performance
- Reviewing shipping-method performance
- Strengthening inventory planning
- Improving regional supply chain efficiency
- Understanding customer segment behavior
- Optimizing product and category performance
- Monitoring profitability alongside sales volume
- Using operational KPIs to support management decisions

The detailed findings and supporting analysis are available in the project notebook and PDF report.

---

## 📊 Power BI Dashboard

The project also includes an interactive Power BI dashboard as part of the broader analytical workflow described in the project documentation.

The dashboard is designed to support executive-style analysis through:

- KPI monitoring
- Dynamic filtering
- Sales analysis
- Delivery and shipping analysis
- Customer and regional analysis
- Interactive visualizations

> **Note:** The current GitHub repository contains the Python notebook, dataset, and project report. The Power BI `.pbix` file is not included in the current repository structure.

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/PritishMete/Supply-chain-analysis-python.git
```

Move into the project directory:

```bash
cd Supply-chain-analysis-python
```

### 2. Install the required Python libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

If a `requirements.txt` file is added later, install dependencies using:

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open:

```text
notebook/supply_chain_analysis.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

### 4. Dataset path

The dataset is located at:

```text
dataset/DataCoSupplyChainDataset.csv
```

If you run the notebook locally, make sure the working directory allows the notebook to access the relative `dataset/` path.

---

## 📄 Project Report

A detailed report is included in the repository:

```text
supplychainanalysis.pdf
```

The report documents the business context, analytical approach, findings, and recommendations from the project.

---

## 🎓 Skills Demonstrated

**Data Cleaning** • **Exploratory Data Analysis (EDA)** • **Feature Engineering** • **Statistical Analysis** • **Correlation Analysis** • **KPI Analysis** • **Data Visualization** • **Business Intelligence** • **Dashboard Development** • **Business Reporting** • **Data Storytelling** • **Supply Chain Analytics**

---

## 👨‍💻 Author

**Pritish Mete**  
Data Analyst

📧 Email: jaiphotoshoot@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/pritish-mete-213a03368/)

🔗 Portfolio: Coming soon

---

## ⭐ Feedback

If you find this project useful, feel free to explore the notebook, review the analysis, and share your feedback or suggestions.
