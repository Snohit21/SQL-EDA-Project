# 📊 SQL Data Analytics Project

A comprehensive end-to-end SQL analytics project built on a Data Warehouse schema — covering exploratory analysis, KPI reporting, customer segmentation, product performance, and time-series trends.

---

## 👤 About Me

**Snohit Kumar Patro** — Power BI Developer & Microsoft Fabric Engineer with 3+ years of experience at LTIMindtree, Hyderabad.

Microsoft Certified: **PL-300 · DP-600 · DP-700**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/snohit-patro)

---

## 🗂️ Project Structure

```
sql-data-analytics-project/
├── datasets/
│   ├── DataWarehouseAnalytics.bak       # SQL Server backup file
│   └── flat-files/
│       ├── dim_customers.csv
│       ├── dim_products.csv
│       └── fact_sales.csv
├── docs/
│   ├── Project Roadmap.pdf
│   ├── Project Roadmap.png
│   └── Project_Notes_Sketches.pdf
├── scripts/
│   ├── 00_init_database.sql             # DB + schema setup
│   ├── 01_database_exploration.sql      # Table & column inventory
│   ├── 02_dimensions_exploration.sql    # Dimension value exploration
│   ├── 03_date_range_exploration.sql    # Date boundary checks
│   ├── 04_measures_exploration.sql      # Key metric baselines
│   ├── 05_magnitude_analysis.sql        # Volume & scale analysis
│   ├── 06_ranking_analysis.sql          # Top-N ranking queries
│   ├── 07_change_over_time_analysis.sql # YoY / MoM trend analysis
│   ├── 08_cumulative_analysis.sql       # Running totals & cumulative KPIs
│   ├── 09_performance_analysis.sql      # vs. Average / vs. Target benchmarks
│   ├── 10_data_segmentation.sql         # Customer & product segmentation
│   ├── 11_part_to_whole_analysis.sql    # Category contribution %
│   ├── 12_report_customers.sql          # Final customer report (VIP/Regular/New)
│   └── 13_report_products.sql           # Final product performance report
└── LICENSE
```

---

## 🧠 Key Analytical Themes

| Script | What It Covers |
|--------|----------------|
| `00` | Database init, schema creation (`gold` layer) |
| `01–03` | Exploratory analysis — tables, columns, date ranges |
| `04–06` | Measures, magnitudes, ranking (TOP N with DENSE_RANK) |
| `07–08` | Time-series trends, running totals, cumulative revenue |
| `09` | Performance benchmarking — avg order value, target gaps |
| `10` | Segmentation — customer tiers, product cost bands |
| `11` | Part-to-whole — % contribution by category |
| `12–13` | Consolidated customer & product report views |

---

## 🛠️ Tech Stack

- **SQL Server** (T-SQL)
- **Data Warehouse** — Gold layer schema
- **Dataset** — Sales, Customers, Products (Star Schema)

---

## 🚀 How to Run

1. Restore `DataWarehouseAnalytics.bak` into SQL Server, **or** load the CSVs from `datasets/flat-files/` into your preferred environment (SQL Server, Fabric Warehouse, etc.)
2. Run `00_init_database.sql` to set up the schema
3. Execute scripts in order (`01` → `13`)

---

## 📄 License

[MIT License](LICENSE)
