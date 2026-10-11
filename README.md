# ⚙️ Associate Data Engineer in Databricks

![Databricks](https://img.shields.io/badge/Platform-Databricks-FF3621?logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/Library-PySpark-E25A1C?logo=apachespark&logoColor=white)
![SQL](https://img.shields.io/badge/Language-SQL-4479A1?logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Language-Python-3776AB?logo=python&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Storage-Delta%20Lake-00ADD8)
![Modules](https://img.shields.io/badge/Modules-13-orange)
![Level](https://img.shields.io/badge/Level-Beginner--to--Intermediate-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Platform:** [DataCamp](https://www.datacamp.com/) — *Associate Data Engineer in Databricks* career track

---

## 📖 About This Track

*Associate Data Engineer in Databricks* takes the path from a first SQL query to production data pipelines on the Databricks Lakehouse. It starts with SQL (querying, joins, data manipulation), moves through the Databricks platform (Lakehouse architecture, Databricks SQL, Delta Lake, Unity Catalog), adds the engineering toolkit (Python, Git, compute and deployment), and finishes with distributed processing in **PySpark** and **Spark SQL** — including an end-to-end ETL pipeline with data cleaning, broadcast joins, Structured Streaming, Delta tables and a scheduled Databricks Job.

Each module folder below contains its own **showcase notebook** — a portfolio-style writeup (not a copy of the raw notes) built from the official course material, my personal notes and, where the module involved hands-on work, the real code and screenshots from the exercises I completed in DataCamp and in a live Databricks workspace.

---

## 🗂️ Module Structure

| # | Folder | Module | Showcase Notebook |
|---|--------|--------|--------------------|
| 1 | [`1_Introduction to SQL`](./1_Introduction%20to%20SQL) | Introduction to SQL | [`Introduction_to_SQL_Showcase.ipynb`](./1_Introduction%20to%20SQL/Introduction_to_SQL_Showcase.ipynb) |
| 2 | [`2_Intermediate SQL`](./2_Intermediate%20SQL) | Intermediate SQL | [`Intermediate_SQL_Showcase.ipynb`](./2_Intermediate%20SQL/Intermediate_SQL_Showcase.ipynb) |
| 3 | [`3_Joining Data in SQL`](./3_Joining%20Data%20in%20SQL) | Joining Data in SQL | [`Joining_Data_In_SQL.ipynb`](./3_Joining%20Data%20in%20SQL/Joining_Data_In_SQL.ipynb) |
| 4 | [`4_Data Manipulation in SQL`](./4_Data%20Manipulation%20in%20SQL) | Data Manipulation in SQL | [`Data_Manipulation_In_SQL.ipynb`](./4_Data%20Manipulation%20in%20SQL/Data_Manipulation_In_SQL.ipynb) |
| 5 | [`5_Introduction to Databricks`](./5_Introduction%20to%20Databricks) | Introduction to Databricks | [`Databricks_Fundamentals_Showcase.ipynb`](./5_Introduction%20to%20Databricks/Databricks_Fundamentals_Showcase.ipynb) |
| 6 | [`6_Introduction to Databricks SQL`](./6_Introduction%20to%20Databricks%20SQL) | Introduction to Databricks SQL | [`Databricks_SQL_Showcase.ipynb`](./6_Introduction%20to%20Databricks%20SQL/Databricks_SQL_Showcase.ipynb) |
| 7 | [`7_Introduction to Python`](./7_Introduction%20to%20Python) | Introduction to Python | [`Introduction_to_Python_Showcase.ipynb`](./7_Introduction%20to%20Python/Introduction_to_Python_Showcase.ipynb) |
| 8 | [`8_Introduction to Git`](./8_Introduction%20to%20Git) | Introduction to Git | [`Introduction_to_Git_Showcase.ipynb`](./8_Introduction%20to%20Git/Introduction_to_Git_Showcase.ipynb) |
| 9 | [`9_Introduction to Databricks Lakehouse`](./9_Introduction%20to%20Databricks%20Lakehouse) | Introduction to Databricks Lakehouse | [`Databricks_Lakehouse_Showcase.ipynb`](./9_Introduction%20to%20Databricks%20Lakehouse/Databricks_Lakehouse_Showcase.ipynb) |
| 10 | [`10_Data Management in Databricks`](./10_Data%20Management%20in%20Databricks) | Data Management in Databricks | [`Data_Management_Showcase.ipynb`](./10_Data%20Management%20in%20Databricks/Data_Management_Showcase.ipynb) |
| 11 | [`11_Introduction to PySpark`](./11_Introduction%20to%20PySpark) | Introduction to PySpark | [`Introduction_to_PySpark_Showcase.ipynb`](./11_Introduction%20to%20PySpark/Introduction_to_PySpark_Showcase.ipynb) |
| 12 | [`12_Introduction to Spark SQL in Python`](./12_Introduction%20to%20Spark%20SQL%20in%20Python) | Introduction to Spark SQL in Python | [`Spark_SQL_in_Python_Showcase.ipynb`](./12_Introduction%20to%20Spark%20SQL%20in%20Python/Spark_SQL_in_Python_Showcase.ipynb) |
| 13 | [`13_Data transformation SparkSQL Databricks`](./13_Data%20transformation%20SparkSQL%20Databricks) | Data Transformation with Spark SQL in Databricks | [`Data_Transformation_SparkSQL_Showcase.ipynb`](./13_Data%20transformation%20SparkSQL%20Databricks/Data_Transformation_SparkSQL_Showcase.ipynb) |

---

## 📚 Module Details

### 📌 Module 1 — Introduction to SQL
> Folder: [`1_Introduction to SQL`](./1_Introduction%20to%20SQL)

SQL fundamentals: what a relational database and a table are, naming conventions for tables and fields, core data types and schemas, writing basic `SELECT` queries, aliasing, `DISTINCT`, views, and a comparison of the PostgreSQL and SQL Server (T-SQL) flavors.

---

### 📌 Module 2 — Intermediate SQL
> Folder: [`2_Intermediate SQL`](./2_Intermediate%20SQL)

Querying, filtering, aggregate functions, and sorting/grouping data with PostgreSQL, practiced on a films/reviews/people dataset — from `COUNT()` and `DISTINCT` through `WHERE`/`LIKE`/`IN`/`NULL` filtering, `AVG()`/`SUM()`/`ROUND()`, and `GROUP BY`/`HAVING`.

---

### 📌 Module 3 — Joining Data in SQL
> Folder: [`3_Joining Data in SQL`](./3_Joining%20Data%20in%20SQL)

All major SQL join types and set operations — `INNER`, `OUTER`, `CROSS` and `SELF` joins, set theory operations, and subqueries — practiced on a countries database (cities, economies, populations, languages, currencies).

---

### 📌 Module 4 — Data Manipulation in SQL
> Folder: [`4_Data Manipulation in SQL`](./4_Data%20Manipulation%20in%20SQL)

Advanced SQL data manipulation — `CASE` statements, subqueries, correlated queries, CTEs, and window functions — practiced on the European Soccer Database (12,800+ matches across 11 countries, 2011–2015).

---

### 📌 Module 5 — Introduction to Databricks
> Folder: [`5_Introduction to Databricks`](./5_Introduction%20to%20Databricks)

A conceptual module covering the Databricks Data Intelligence Platform: how the Lakehouse architecture unifies data warehouses and data lakes, the Control Plane vs. Compute Plane split, workspace administration, Delta Lake, Unity Catalog, Apache Spark compute (cluster types and runtime), and how Databricks SQL fits in as the platform's warehousing layer.

---

### 📌 Module 6 — Introduction to Databricks SQL
> Folder: [`6_Introduction to Databricks SQL`](./6_Introduction%20to%20Databricks%20SQL)

Hands-on querying and dashboarding over a real insurance claims dataset. Covers the SQL Editor, Unity Catalog, data ingestion with `COPY INTO`, the medallion architecture (Bronze → Silver → Gold), and building interactive dashboards with filters and parameters. **22 exercise screenshots.**

---

### 📌 Module 7 — Introduction to Python
> Folder: [`7_Introduction to Python`](./7_Introduction%20to%20Python)

Python foundations for the PySpark modules that follow: variables and types, lists (subsetting, manipulation, references vs. copies), functions, methods and packages, and NumPy arrays with vectorized calculations, boolean filtering, 2D arrays and basic statistics on a simulated 5,000-person survey. Every code cell is executed, with its output saved in the notebook.

---

### 📌 Module 8 — Introduction to Git
> Folder: [`8_Introduction to Git`](./8_Introduction%20to%20Git)

Version control from the terminal on a mental-health survey project: creating repos, staging and committing, how Git stores data (commit, tree, blob), filtering history with `git log`, comparing versions with `git diff`, and undoing changes with `git restore`, `git checkout` and `git revert`. **10 exercise screenshots.**

---

### 📌 Module 9 — Introduction to Databricks Lakehouse
> Folder: [`9_Introduction to Databricks Lakehouse`](./9_Introduction%20to%20Databricks%20Lakehouse)

Hands-on tour of the Lakehouse in a live Azure Databricks workspace: medallion layers on taxi trip data, control plane vs. data plane and audit logs, all-purpose vs. jobs clusters, multi-language notebooks, Unity Catalog governance, Delta Sharing (native and open protocol), Lakehouse Federation, and deployment with Databricks Asset Bundles (`databricks.yml`). **13 exercise screenshots.**

---

### 📌 Module 10 — Data Management in Databricks
> Folder: [`10_Data Management in Databricks`](./10_Data%20Management%20in%20Databricks)

Delta Lake fundamentals applied to a healthcare dataset (patients, prescriptions, appointments): ACID transactions, managed vs. unmanaged tables, persistent and temporary views, and PII-aware access control through Data Explorer. **23 exercise screenshots.**

---

### 📌 Module 11 — Introduction to PySpark
> Folder: [`11_Introduction to PySpark`](./11_Introduction%20to%20PySpark)

PySpark DataFrames on US Census, Data Scientist salaries and flights datasets: `SparkSession`, reading CSV/JSON with inferred and explicit schemas, cleaning and column operations, joins, UDFs and pandas UDFs, RDDs, Spark SQL on temp views, aggregations, and caching with execution plans (`explain()`). **20 exercise screenshots.**

---

### 📌 Module 12 — Introduction to Spark SQL in Python
> Folder: [`12_Introduction to Spark SQL in Python`](./12_Introduction%20to%20Spark%20SQL%20in%20Python)

Window functions in SQL and dot notation on a train schedule, natural language processing on *The Adventures of Sherlock Holmes* (tokenizing, moving windows, n-gram counts, top-N per chapter), caching, logging without hidden actions, reading query plans, and an end-to-end text classifier with `CountVectorizer` and logistic regression (test AUC 0.893). **38 exercise screenshots.**

---

### 📌 Module 13 — Data Transformation with Spark SQL in Databricks
> Folder: [`13_Data transformation SparkSQL Databricks`](./13_Data%20transformation%20SparkSQL%20Databricks)

An end-to-end ETL pipeline on the `online_retail` dataset (108,361 transactions) in a live Databricks workspace: explicit schemas, a cleaning pipeline with quality metrics, broadcast joins verified in Photon plans, customer ranking with window functions, Structured Streaming into Delta with checkpoints, managed Delta tables, and a multi-task Databricks Job (debugged and re-run), plus Lakeflow's declarative model. The notebook closes with an **end-to-end ETL summary** (extract → transform → load → orchestrate). **24 exercise screenshots.**

---

## 🧰 Skills Demonstrated

- **SQL:** filtering, aggregation, joins and set operations, subqueries, CTEs, `CASE` and window functions (PostgreSQL and Spark SQL).
- **Python:** core types, lists, functions and packages, NumPy vectorized operations and descriptive statistics.
- **PySpark:** DataFrames with explicit `StructType` schemas, cleaning (`na.drop`, `na.fill`, `dropDuplicates`), joins, UDFs and pandas UDFs, RDDs, and temp views queried with Spark SQL.
- **Performance tuning:** broadcast joins, repartitioning, caching/persisting, and reading physical plans to spot shuffles, pushed filters and pruned columns.
- **Streaming:** file-based Structured Streaming into Delta Lake with checkpoints and `availableNow` triggers.
- **Databricks platform:** Lakehouse and medallion architecture, Databricks SQL, Delta Lake tables and views, Unity Catalog governance and lineage, Delta Sharing and Lakehouse Federation.
- **Production & DevOps:** Databricks Jobs with task dependencies, Lakeflow declarative pipelines, Databricks Asset Bundles, cluster selection for cost control, and Git version control.
- **Text analytics & ML:** tokenization and n-grams with window functions, `CountVectorizer` features, and a logistic regression classifier evaluated with AUC.

---

## 📁 Repository Contents

Module folders generally contain:
- **A showcase notebook (`.ipynb`)** — the polished, portfolio-ready writeup for that module.
- **`chapterN.pdf`** — official slide decks from the course.
- **`ChapterN-*.txt` / `note.txt` / `wrapup_course.txt`** — personal notes taken during the course, where applicable.
- **`*Screenshots.docx` + `screenshots/`** — for the hands-on modules, the original exercise screenshots and the result images embedded in the showcase notebook.
- **`Resources/`** — datasets (CSV/zip) used for the SQL exercises, in the SQL modules.

---

## 🚀 How to Run

```bash
git clone https://github.com/JuanCGJ/Associate-Data-Engineer-In-Databricks.git
cd Associate-Data-Engineer-In-Databricks
jupyter notebook
```

Then open any module's showcase notebook directly. The Python notebook (Module 7) runs locally with NumPy; the PySpark and Databricks notebooks document code that was executed in DataCamp or in a Databricks workspace, with the results shown as screenshots.

---

*Built with 🤍 as part of a continuous learning journey in Data Engineering.*
