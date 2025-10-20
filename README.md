# Framework for Data and Visual Analytics Lab Experiments 📊

[cite_start]This repository contains lab experiments and a mini-project report for the course **Framework for Data and Visual Analytics (AD23632)**[cite: 105, 108, 1673]. [cite_start]The content covers the core stages of Exploratory Data Analysis (EDA) using Python (Pandas, Matplotlib) and the creation of interactive dashboards using industry-leading Business Intelligence (BI) tools (Power BI, Tableau)[cite: 1682].

## 📁 Repository Structure

The experiments are chronologically ordered, focusing on the end-to-end data analytics workflow.

| File | Experiment No. | Date | Topic | Key Tools |
| :--- | :---: | :---: | :--- | :--- |
| `EXP 1.pdf` / `231501058_Lab Experiments.pdf` (p. 2) | 01 | 16-07-2025 | [cite_start]Setting up the Python Environment (Jupyter Notebook) [cite: 1252, 1253, 111] | [cite_start]`Jupyter`, `ipywidgets` [cite: 1254, 115, 117] |
| `EXP 2.pdf` / `231501058_Lab Experiments.pdf` (p. 3-5) | 02 | 23-07-2025 | [cite_start]EDA - Data Import and Export [cite: 850, 135] | [cite_start]`Pandas`, `SQLite`, `requests`, Web Scraping [cite: 854, 855, 138, 140, 141, 875] |
| `EXP 3.pdf` / `231501058_Lab Experiments.pdf` (p. 6-8) | 03 | 30-07-2025 | [cite_start]EDA - Data Cleaning and Preprocessing [cite: 2243, 2244, 229] | [cite_start]`Pandas`, `StandardScaler`, `MinMaxScaler` [cite: 2246, 2247, 2248, 237] |
| `EXP 4.pdf` / `231501058_Lab Experiments.pdf` (p. 9-10) | 04 | 06-08-2025 | [cite_start]EDA - Data Inspection and Analysis [cite: 1425, 1426, 364] | [cite_start]`Pandas` (Filtering, Descriptive Stats) [cite: 1429, 390, 406] |
| `EXP 5.pdf` / `231501058_Lab Experiments.pdf` (p. 11-12) | 05 | 13-08-2025 | [cite_start]EDA - Data Visualization with Matplotlib [cite: 5, 6, 526, 7] | [cite_start]`Matplotlib` (Line, Bar, Histograms) [cite: 10, 15, 28, 39] |
| `231501058_Lab Experiments.pdf` (p. 13-14) | 06 | N/A | [cite_start]Data Visualization Using Power BI [cite: 662] | [cite_start]**Power BI** [cite: 675, 1992] |
| `231501058_Lab Experiments.pdf` (p. 15-16) | 07 | N/A | [cite_start]Data Visualization Using Tableau [cite: 766] | [cite_start]**Tableau Desktop** [cite: 772, 777] |
| `FDVA-REPORT.pdf` | Mini-Project | N/A | [cite_start]Store Sales Data Analysis Report [cite: 1674, 1681] | [cite_start]Python, Power BI, Tableau [cite: 1682, 1696, 1697, 1698] |

***

## ✨ Key Learning Outcomes

### 1. Python Environment and EDA Fundamentals

* [cite_start]**Environment Setup (Exp 01):** Successfully configured the Python environment using **Jupyter Notebook** [cite: 1253, 111] [cite_start]and demonstrated interactivity using **Jupyter Widgets**[cite: 1254, 115, 117].
* **Data I/O (Exp 02):** Implemented methods to **import and export** data across multiple formats, including CSV, Excel, and SQL databases[cite: 851, 143, 147, 151]. Also performed **web scraping** to pull data from HTML tables[cite: 875, 876, 165].
* [cite_start]**Data Cleaning (Exp 03):** Applied essential preprocessing techniques to ensure data quality[cite: 2244]:
    * [cite_start]**Handling Missing Values** by imputing with mean/mode or dropping[cite: 2262, 2265, 254, 256].
    * **Removing Duplicates**[cite: 2272, 262].
    * [cite_start]**Data Transformation** including type conversion [cite: 2276, 280] [cite_start]and **Standardization/Min-Max Scaling** for numerical features[cite: 2282, 294, 298].
* [cite_start]**Data Inspection (Exp 04):** Used `Pandas` to inspect DataFrame structure (`.info()`, `.shape`, `.columns`), perform **data filtering** based on conditions (e.g., Salary > 55000) [cite: 1445, 1449, 385, 386, 390][cite_start], and calculate key **descriptive statistics** (Mean, Median, Mode, Variance, Standard Deviation)[cite: 1461, 406, 414].
* [cite_start]**Basic Visualization (Exp 05):** Implemented fundamental plotting techniques using **Matplotlib** for Exploratory Data Analysis (EDA) [cite: 7][cite_start]: **Line Charts** (for trends) [cite: 15][cite_start], **Bar Charts** (for categorical comparisons) [cite: 28][cite_start], and **Histograms** (for distribution analysis)[cite: 39].

***

### 2. Business Intelligence Dashboarding

Experiments 06, 07, and the Mini-Project focused on creating professional, interactive dashboards on the **Sample Superstore Dataset**[cite: 1692, 1702].

| Tool | Focus | Key Design/Component |
| :--- | :--- | :--- |
| **Microsoft Power BI** | **Comprehensive View** (Exp 06, Mini-Project) [cite: 662, 1991] | Used a **dark theme** and KPI cards for Total Sales ($2.30\text{M}$), Total Profit ($286.40\text{K}$), and Average Discount ($15.6\%$)[cite: 703, 710, 715, 1998]. Visuals included Sales by Category, Sales by Year, and Sales by Region[cite: 1999]. |
| **Tableau Desktop** | **Interactivity & Deep Dive** (Exp 07, Mini-Project) [cite: 766] | Used a **pastel theme** and four primary KPIs (Sales, Profit, Quantity, Discount)[cite: 2071, 2065]. Visuals featured Customer and Subcategory-wise Profit, and Region-wise Profit/Discount analysis[cite: 2072]. |
| **Python Stack** | **Custom Web App** (Mini-Project) [cite: 1853] | Built a dashboard using **Streamlit** for the web interface, demonstrating a code-driven solution with interactive sidebar filters for Region and Category[cite: 1859, 1862]. |

### 3. Key Business Findings (Superstore Analysis)

The analysis across all platforms consistently revealed critical business insights[cite: 2141, 2142]:
* [cite_start]**Technology is the Most Profitable Category:** Technology (specifically Copiers and Phones) yielded the strongest profits[cite: 2143].
* [cite_start]**Regional Performance:** The **West Region** consistently led in both sales and profit[cite: 2144].
* [cite_start]**High Discounts Erode Profit:** A clear negative correlation was observed; discounts above $20-30\%$ consistently led to financial losses[cite: 2146, 2147].
* [cite_start]**Segment Dominance:** The **Consumer Segment** accounted for over half of the total sales[cite: 2148].

***

## 🛠️ Setup and Installation

To reproduce the Python-based experiments:

### Prerequisites

* Python 3.x
* Power BI Desktop (for Exp 06, Mini-Project)
* Tableau Desktop (for Exp 07, Mini-Project)

### Installation

Install the required Python libraries using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn ipywidgets sqlalchemy requests openpyxl beautifulsoup4
