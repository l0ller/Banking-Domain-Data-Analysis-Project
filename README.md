# BankIntel: Financial Customer Insights & Analytics
**End-to-End Data Analysis & Business Intelligence Project**

## 📌 Project Overview
BankIntel is a comprehensive data analysis project designed to decode customer financial behavior. By integrating **Python-based Exploratory Data Analysis (EDA)** with **Power BI Visualization**, this project transforms raw banking data into actionable business intelligence. The analysis focuses on customer demographics, income-to-debt ratios, and product lifecycle trends.

## 📊 Key Insights Uncovered
* **The Savings Lifecycle:** Identified a strong positive correlation between age/income and the accumulation of long-term assets (Savings and Retirement accounts).
* **Debt Crossover:** Discovered a moderate link between Personal Bank Loans and Business Lending, suggesting a specific segment of "Solopreneurs" utilizing personal credit for business operations.
* **External Drivers:** Statistical analysis revealed that property ownership is largely independent of standard banking variables in this dataset, suggesting external market factors (inheritance, location) play a larger role.

## 🛠️ Tech Stack
* **Analysis:** Python (`Pandas`, `NumPy`)
* **Visualization:** `Seaborn`, `Matplotlib`
* **Business Intelligence:** Power BI (DAX, Power Query)
* **Data Source:** Multi-dimensional Banking Dataset (Excel/CSV)

## 📂 Project Structure

### 1. Exploratory Data Analysis (`BankEDA.ipynb`)
The Python layer focuses on data hygiene and statistical validation:
* **Data Cleaning:** Handling missing values and normalizing financial variables.
* **Correlation Analysis:** Utilizing heatmaps to identify relationships between account types (Checking, Savings, Business, etc.).
* **Distribution Profiling:** Visualizing density plots for income and age to define target customer personas.

### 2. Interactive Dashboard (`Banking Dashboard (2025).pbix`)
The Power BI layer provides an executive view of the findings:
* **Account Distribution:** High-level overview of total balances across different product categories.
* **Loan Analysis:** Comparative charts for Business vs. Personal lending exposure.
* **Dynamic Filtering:** Integrated slicers allowing for deep-dives into specific age brackets and income levels.

## 🚀 Getting Started

### Prerequisites
* Python 3.8+
* Jupyter Notebook or Google Colab
* Microsoft Power BI Desktop (to view the `.pbix` file)

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/bank-intel-analytics.git](https://github.com/yourusername/bank-intel-analytics.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy seaborn matplotlib
    ```
3.  **Run the analysis:** Open `BankEDA.ipynb` to view the step-by-step data processing.

## 📈 Future Scope
* **Predictive Modeling:** Implementing a Churn Prediction model to identify at-risk customers.
* **Clustering:** Using K-Means to create automated customer segments for targeted marketing.
* **Time-Series:** Analyzing month-over-month growth in deposit balances.

---
**Author:** [Your Name]  
**Role:** Data Analyst
