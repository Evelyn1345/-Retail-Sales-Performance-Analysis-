# Retail Sales Performance Analysis — End-to-End Project 

## Project Overview  
This project analyzes vendor performance and supply-chain efficiency for a retail/wholesale business. The goal is to turn raw sales, purchase, inventory and invoice data into meaningful business insights — helping stakeholders identify top vendors, spot underperforming vendors or slow-moving inventory, detect pricing or margin issues, and support data-driven decision-making.



## Problem Statement  
Many businesses struggle to understand which vendors contribute positively to profitability, which ones are causing inventory pile-ups, and whether procurement and sales are aligned.  
This project addresses questions like:  
- Which vendors consistently deliver high sales and margins?  
- Which vendors have slow-moving or stuck inventory?  
- Are there pricing or margin inconsistencies across vendors or products?  
- How does vendor performance change over time or across regions?  



##  What This Project Does / Key Features  

- Data ingestion: loads raw sales, purchase, inventory, and invoice data.  
- Data cleaning & merging: handles missing or inconsistent entries; merges datasets (sales ↔ purchases ↔ inventory ↔ invoices).  
- KPI & metric computation: calculates vendor-level sales, margin, inventory turnover, stuck inventory, profitability, and other vendor health metrics.  
- Exploratory & trend analysis: performs trend analysis (sales over time, purchase patterns, inventory aging) and hotspot analysis (regions or vendors with issues).  
- Visualization & reporting: creates interactive dashboards (Power BI) and a regional heatmap to highlight high-risk zones and vendor performance.  
- Business insights & recommendations: identifies underperforming vendors, slow-moving stock, margin leaks, and suggests vendor rationalization or procurement adjustments.  

---

##  Repository Structure (example)  

| File / Folder | Description |
|---------------|-------------|
| `data/` | Raw CSV/data files (sales, purchases, inventory, invoices, etc.) |
| `ingestion/` | Scripts/notebooks for data ingestion into database |
| `cleaning_analysis/` | Data cleaning, EDA, merging datasets, KPI calculations |
| `visualization/` | Power BI dashboards, visualizations, heatmaps |
| `final/` | Cleaned & processed datasets (e.g. merged CSV, SQLite DB) ready for reporting |
| `notebooks/` | Jupyter Notebooks used for analysis and processing |
| `README.md` | This file — project overview and documentation |

---

## Tools & Technologies Used  

- **Python** — for data ingestion, cleaning, transformation, and analysis  
- **Pandas / NumPy** — data wrangling and manipulation  
- **SQL / SQLite** — storing structured data, performing joins and queries  
- **Power BI** — building interactive dashboards and visualizations  
- **Excel / CSV** — raw data format and exports for reporting  

---

## Workflow / Pipeline  

1. **Data Ingestion** — Load raw data from files (sales, purchase, inventory, invoices) into a SQLite database (or data storage)  
2. **Data Cleaning & Merging** — Clean datasets, handle missing values, unify formats, join across tables (sales + purchases + inventory + invoices)  
3. **KPI Computation & Analysis** — Compute vendor-level KPIs: sales volume, margins, inventory turnover, stuck inventory, profitability, etc. Perform trend and hotspot analyses.  
4. **Visualization & Dashboarding** — Build dashboards and heatmaps (Power BI) for vendor health, inventory status, regional analysis.  
5. **Insights & Recommendations** — Generate actionable insights: underperforming vendors, inventory management, procurement/pricing recommendations.  

---

## Key Findings & Business Value _(example)_  

- Identified top-performing and underperforming vendors based on sales, margin, and inventory turnover.  
- Flagged slow-moving inventory and “stuck stock” — helping prevent cash flow blockage.  
- Spotted pricing/margin inconsistencies across vendors and advised strategic vendor renegotiations.  
- Highlighted geographic or regional “hotspots” with logistic or inventory issues, assisting supply-chain optimization.  

---

## How to Reproduce / Run This Project  

1. Clone the repository  
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```  
2. (Optional) Set up a virtual environment (recommended):  
    ```bash
    python -m venv env  
    source env/bin/activate   # Linux/Mac  
    env\Scripts\activate      # Windows  
    ```  
3. Install necessary Python libraries:  
    ```bash
    pip install pandas numpy sqlite3  # plus any others used  
    ```  
4. Run notebooks/scripts in this order (or as per instructions):  
    - Data ingestion  
    - Data cleaning & merging  
    - KPI calculation & analysis  
5. Export cleaned/merged data to a CSV (or SQLite DB) for Power BI.  
6. Open Power BI and load the exported data → explore dashboards and visualizations.  

---

##  About the Author  

**Anjali Singh** — B.Tech Engineering Physics student at IIT (ISM) Dhanbad.  
Skilled in SQL, Python, data analytics, dashboarding — with strong interest in turning raw data into business-driven insights.  

---

