# 📊 Financial Analytics Automation Pipeline

An end-to-end automated data analytics project built using Python, MySQL, Google Drive API, Power BI, and Power Automate.

This project automates the complete analytics workflow — from data extraction and transformation to dashboard reporting and workflow automation.

---

# 🚀 Project Overview

This project was developed to create an automated financial analytics pipeline capable of:

✅ Fetching datasets automatically from Google Drive  
✅ Performing data cleaning and preprocessing using Python  
✅ Storing cleaned data in MySQL  
✅ Running advanced SQL analysis queries  
✅ Building an interactive Power BI dashboard  
✅ Automating reporting workflows using Power Automate  

The project demonstrates practical skills in:
- Data Analytics
- ETL Pipeline Development
- SQL Analysis
- Dashboard Development
- API Integration
- Workflow Automation
- Business Intelligence Reporting

---

# 🏗️ Project Architecture

```text
Google Drive API
        ↓
Python ETL & Data Cleaning
        ↓
MySQL Database
        ↓
Power BI Dashboard
        ↓
Power Automate Workflow
```

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Data extraction, preprocessing & automation |
| Jupyter Notebook | Exploratory Data Analysis (EDA) |
| Google Drive API | Automated dataset access |
| MySQL | SQL querying & database management |
| Microsoft Power BI | Dashboard creation & visualization |
| Microsoft Power Automate | Automation & reporting workflow |
| GitHub | Version control & project hosting |

---

# 📂 Dataset

The project uses a USA financial/customer transactional dataset containing information related to:
- Customer behavior
- Sales transactions
- Product categories
- Payment methods
- Branch performance
- Financial trends

---

# ⚡ Key Features

## 🔹 Automated Data Pipeline
- Fetches files dynamically from Google Drive
- Reads CSV and Excel datasets automatically
- Combines multiple files into a single dataframe

## 🔹 Data Cleaning & Transformation
- Missing value handling
- Duplicate removal
- Data type corrections
- Column standardization
- Feature engineering

## 🔹 SQL Analytics
Performed advanced SQL analysis using:
- Window Functions
- CTEs
- Aggregations
- Ranking Functions
- Subqueries
- Business KPI analysis

## 🔹 Power BI Dashboard
Interactive dashboard includes:
- KPI Cards
- Revenue Analysis
- Branch Performance
- Category Insights
- Payment Method Analysis
- Customer Behavior Insights

## 🔹 Workflow Automation
Implemented automation using Power Automate:
- Outlook integration
- Automated report handling
- Google Drive synchronization
- Automated workflow execution

---

# 🔄 Project Workflow

## 📌 Step 1 — Data Extraction
- Connected Google Drive API using service account credentials
- Accessed datasets automatically from cloud storage

## 📌 Step 2 — Data Cleaning & EDA
Performed using Python and Pandas:
- Data preprocessing
- Missing value treatment
- Exploratory Data Analysis (EDA)

## 📌 Step 3 — Database Integration
- Uploaded cleaned dataset into MySQL
- Performed SQL-based business analysis

## 📌 Step 4 — Dashboard Development
- Built an interactive Power BI dashboard
- Generated business insights and visual reports

## 📌 Step 5 — Workflow Automation
- Automated reporting workflow using Power Automate
- Integrated Outlook and Google Drive services

---

# 🧠 SQL Concepts Used

```sql
RANK() OVER()
CTE
GROUP BY
WINDOW FUNCTIONS
AGGREGATIONS
SUBQUERIES
```

---

# 📈 Skills Demonstrated

- Data Analytics
- ETL Pipeline Development
- SQL Query Optimization
- API Integration
- Dashboard Development
- Business Intelligence
- Workflow Automation
- Data Cleaning & Transformation

---

# ▶️ How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone <repository-link>
```

## 2️⃣ Install Required Libraries

```bash
pip install pandas sqlalchemy pymysql google-api-python-client google-auth
```

## 3️⃣ Configure Environment
- Add Google Drive API credentials
- Configure MySQL database connection
- Update dataset file paths

## 4️⃣ Run Python ETL Script

```bash
python main.py
```

## 5️⃣ Open Power BI Dashboard
- Open `.pbix` file in Microsoft Power BI
- Refresh dataset connection

---

# 📌 Future Improvements

- Real-time analytics integration
- Cloud deployment
- Scheduled automatic refresh
- Machine learning integration
- Predictive analytics

---

# 👨‍💻 Author

**Jay Kumar**

---

# 📜 License

This project is licensed under the MIT License.
