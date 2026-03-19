
# 🏦 Banking Operations & Risk Analytics: An End-to-End Data Pipeline

## 📖 Project Overview
This project demonstrates a comprehensive data analytics pipeline designed to evaluate banking performance, loan health, and fraud risk. By integrating **Python**, **SQL**, and **Power BI**, I transformed raw, fragmented datasets into a "Single Source of Truth" for executive decision-making.

The project highlights the transition from data cleaning (Python) to structured querying (SQL) and finally to interactive storytelling (Power BI).

---

## 🛠️ The Technical Stack
| Tool | Purpose | Key Library/Function |
| :--- | :--- | :--- |
| **Python (Jupyter)** | Data Cleaning & EDA | `Pandas`, `Plotly`, `NumPy` |
| **SQL (MySQL)** | Advanced Querying | CTEs, Window Functions, Joins |
| **Power BI** | Visualization | DAX, Interactive Slicers, Star Schema |

---

## 🔄 Project Workflow

### 1. Data Cleaning & EDA (Python)
* Standardized disparate datasets (customers, transactions, loans).
* Identified and handled missing values and inconsistent date formats.
* **Key Insight:** Performed statistical distribution analysis to identify "Whale" accounts versus high-frequency retail users.

### 2. Advanced Querying (MySQL)
* Engineered a fraud-detection query using `TIMESTAMPDIFF` to flag high-value transactions occurring within a 10-minute window.
* Implemented **Z-Score analysis** via CTEs to mathematically isolate outliers.
* Calculated **Month-over-Month (MoM) Growth** to track the bank's liquidity trends.

### 3. Business Intelligence Dashboard (Power BI)
* **Portfolio Health:** Tracked loan default rates and interest yield.
* **Fraud Analysis:** Created a high-risk scatter plot for transaction monitoring.
* **Geospatial Insights:** Identified branch-specific risks across regions.

---

## 🔍 Cross-Tool Validation (Data Integrity)
One of the core objectives of this project was to ensure data consistency. I validated the results across all three platforms:
* **Total Volume:** Verified that Python's `.sum()` matched the SQL `SUM()` and Power BI's DAX measures.
* **Outlier Detection:** The 12 fraudulent accounts identified via Python’s Z-score calculation were cross-referenced and verified through SQL logic before being flagged in the Power BI dashboard.

---

## 📈 Key Insights & Results
* **Fraud Detection:** Successfully isolated 0.3% of transactions that carried high-risk indicators.
* **Loan Performance:** Identified specific branches where the default rate was 15% higher than the national average, suggesting a need for stricter credit scoring in those regions.
* **Customer Segmentation:** Discovered that 80% of the bank's volume came from just 15% of the customer base.

---

## 📁 Repository Structure
* `Data/`: Contains the (anonymized) raw and cleaned CSV files.
* `Python`: Jupyter Notebook for EDA and cleaning.
* `SQL/`: The `.sql` script.
* `PowerBI files/`: The `.pbix` Power BI file.

---

## 📩 Contact
**Michael Okposo**
* **LinkedIn:** http://linkedin.com/in/okposo-michael-b0b99224a
* **Email:** okposom@gmail.com

---

