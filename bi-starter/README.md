# Retail BI Starter (DuckDB + SQL + Streamlit)

A compact, end-to-end **Business Intelligence** project that demonstrates modern data analytics skills — clean ETL, an analytical data model, SQL-based metrics, and a Streamlit dashboard for visualization.

---

## Project Overview
This project simulates a small-scale retail analytics pipeline:

1. **ETL:** Loads raw transactional data, cleans and transforms it using Pandas, and stores it in a DuckDB data warehouse.  
2. **Analytics Layer:** Runs SQL logic to compute revenue, gross margin, repeat purchase rates, and product-level performance.  
3. **Dashboard:** Interactive Streamlit UI for visualizing key KPIs, daily revenue trends, and top products.

---

## Tech Stack
- **DuckDB** — embedded analytics database  
- **Pandas** — lightweight ETL  
- **SQL** — metrics and transformations  
- **Streamlit** — front-end BI dashboard  
- **Pytest** — simple data sanity tests  

---

## ⚙️ Setup & Run Locally
Clone the repo and install dependencies:
```bash
git clone https://github.com/SamarthAnalytics/retail-bi-starter.git
cd retail-bi-starter
pip install -r requirements.txt
