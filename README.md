# Framework for Data and Visual Analytics Lab Experiments 📊

This repository contains lab experiments and a mini-project report for the course **Framework for Data and Visual Analytics (AD23632)**. The content focuses on the core stages of Exploratory Data Analysis (EDA) using Python (Pandas, Matplotlib) and the creation of interactive dashboards using industry-leading Business Intelligence (BI) tools (Power BI, Tableau).

## 📁 Repository Structure

The experiments are chronologically ordered, focusing on the end-to-end data analytics workflow.

| File | Experiment No. | Date | Topic | Key Tools |
| :--- | :---: | :---: | :--- | :--- |
| `EXP 1.pdf` / `231501058_Lab Experiments.pdf` (p. 2) | 01 | 16-07-2025 | Setting up the Python Environment (Jupyter Notebook) | `Jupyter`, `ipywidgets` |
| `EXP 2.pdf` / `231501058_Lab Experiments.pdf` (p. 3-5) | 02 | 23-07-2025 | EDA - Data Import and Export | `Pandas`, `SQLite`, `requests`, Web Scraping |
| `EXP 3.pdf` / `231501058_Lab Experiments.pdf` (p. 6-8) | 03 | 30-07-2025 | EDA - Data Cleaning and Preprocessing | `Pandas`, `StandardScaler`, `MinMaxScaler` |
| `EXP 4.pdf` / `231501058_Lab Experiments.pdf` (p. 9-10) | 04 | 06-08-2025 | EDA - Data Inspection and Analysis | `Pandas` (Filtering, Descriptive Stats) |
| `EXP 5.pdf` / `231501058_Lab Experiments.pdf` (p. 11-12) | 05 | 13-08-2025 | EDA - Data Visualization with Matplotlib | `Matplotlib` (Line, Bar, Histograms) |
| `231501058_Lab Experiments.pdf` (p. 13-14) | 06 | N/A | Data Visualization Using Power BI | **Power BI** |
| `231501058_Lab Experiments.pdf` (p. 15-16) | 07 | N/A | Data Visualization Using Tableau | **Tableau Desktop** |
| `FDVA-REPORT.pdf` | Mini-Project | N/A | Store Sales Data Analysis Report | Python, Power BI, Tableau |

---

## ✨ Key Learning Outcomes

### 1. Python Environment and EDA Fundamentals

* [cite_start]**Environment Setup:** Successfully configured the Python environment using **Jupyter Notebook** and demonstrated interactivity using **Jupyter Widgets**[cite: 871, 968].
* [cite_start]**Data I/O:** Implemented methods to **import and export** data across multiple formats, including CSV, Excel, SQL databases (using `sqlite3`), and performed **web scraping** to pull data from HTML tables (e.g., Wikipedia)[cite: 1587, 1646].
* [cite_start]**Data Cleaning:** Applied essential preprocessing techniques to ensure data quality[cite: 1076]:
    * [cite_start]**Handling Missing Values** (imputation with mean/mode, forward fill, or dropping)[cite: 1097, 1099, 152].
    * [cite_start]**Removing Duplicates**[cite: 1076, 1105].
    * [cite_start]**Data Transformation** (Type conversion, **Standardization**, and **Min-Max Scaling** for numerical features)[cite: 1076, 192, 196].
* [cite_start]**Data Inspection:** Used `Pandas` to inspect DataFrame structure (`.info()`, `.shape`, `.columns`) [cite: 283, 284][cite_start], perform **data filtering** based on conditions [cite: 1329][cite_start], and calculate key **descriptive statistics** (Mean, Median, Mode, Variance, Standard Deviation)[cite: 305, 319, 321, 1342, 1347, 1448].
* [cite_start]**Basic Visualization:** Implemented fundamental plotting techniques using **Matplotlib** for Exploratory Data Analysis (EDA): **Line Charts** (for trends), **Bar Charts** (for categorical comparisons), and **Histograms** (for distribution analysis)[cite: 975, 1070].

---

### 2. Business Intelligence Dashboarding

[cite_start]Experiments 06 and 07, along with the mini-project, focused on creating professional, interactive dashboards using BI tools on the **Sample Superstore Dataset**[cite: 2030, 2041].

| Tool | Experiment | Key Design/Component |
| :--- | :--- | :--- |
| **Microsoft Power BI** | 06 & Mini-Project | [cite_start]Designed a **dark-themed dashboard** with KPI cards for Total Sales ($2.30M$), Total Profit ($286.40K$), and Average Discount ($15.6\%$)[cite: 2347, 2352, 2364, 2370]. [cite_start]Visuals included Sales by Category, Sales by Year, and Profit by Sub-Category[cite: 2348]. |
| **Tableau Desktop** | 07 & Mini-Project | [cite_start]Designed a **soft pastel-themed dashboard** with KPIs for Total Profit, Total Sales, Total Quantity, and Total Discount[cite: 2414, 2420]. [cite_start]Visuals included Category-wise Sales and Profit (Bubble Chart), Top 5 Customers, and Subcategory-wise Profit (Line/Bar Chart)[cite: 2421]. |
| **Python Stack** | Mini-Project | [cite_start]Built a lightweight, code-driven web application using **Streamlit** for the interface, **Pandas** for data, and **Matplotlib/Seaborn** for visualizations, demonstrating a customizable, open-source alternative to proprietary tools[cite: 2202, 2208]. |

### 3. Key Business Findings (Superstore Analysis)

[cite_start]The cross-platform analysis consistently revealed critical business insights[cite: 2490]:
* [cite_start]**Profitability:** **Technology** (specifically Copiers and Phones) was the **Most Profitable Category**, despite Office Supplies having high sales volume[cite: 2492].
* [cite_start]**Regional Performance:** The **West Region** consistently led in both sales and profit[cite: 2493].
* [cite_start]**Discounts vs. Profit:** A clear **negative correlation** was observed; discounts above $20-30\%$ consistently led to financial losses[cite: 2495, 2496].

---

## 🛠️ Setup and Installation

To reproduce the Python-based experiments:

### Prerequisites

* Python 3.x

### Installation

Install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn ipywidgets sqlalchemy requests openpyxl beautifulsoup4
