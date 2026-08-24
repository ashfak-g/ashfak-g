<div align="center">

# Ashfakur Rahman
### **Data Analyst • Data Operations Analyst • BI Analyst**
*(Ex-Frontend Developer | Data Operations & Visualization Specialist)*

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![Kaggle](https://img.shields.io/badge/KAGGLE-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/your-username)
[![LeetCode](https://img.shields.io/badge/LEETCODE-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/hsWMQHn8fD/)
[![GitHub](https://img.shields.io/badge/GITHUB-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ashfak-g)
[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ashfakgub221@gmail.com
)
[![Portfolio](https://img.shields.io/badge/LIVE_PORTFOLIO-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://your-portfolio.vercel.app/)

</div>

---

### 👑 Executive Profile Summary

```text
Developer: Ashfakur Rahman
Target Roles: Data Analyst | BI Analyst | Data Operations Analyst
Degree: B.Sc. in Computer Science & Engineering (CSE) - Green University of Bangladesh
Prior Experience: Frontend Developer (Dec 2025 – Aug 2026) | HTML, CSS, JavaScript, Liquid
Core Analytics Stack: SQL, PostgreSQL, Python (Pandas, NumPy), Power BI, Tableau, Looker Studio, Excel
Operations & Tools: Retool, RegEx, Statistical Analysis, Data Preprocessing, ETL Pipelines
Profiles: Kaggle | LeetCode | GitHub
Status: 🚀 Open for Data Analyst, BI Analyst & Data Operations Roles (Remote / On-Site)
```

> *"Transforming complex raw data into actionable business intelligence, operational workflow automations, and executive dashboards."* Leveraging a background in **Frontend Development (HTML, CSS, JS, Liquid)** combined with advanced **SQL, Python, and BI analytics**, I bridge the gap between technical data engineering, internal tool ops (Retool), and high-impact business decision making.

---

### 🚀 Featured Key Projects

| ❤️ [ECG Anomaly Detection & Heart Disease Prediction](https://github.com/ashfak-g/ECG-Anomaly-Detection-Heart-Disease-Prediction) | 🛒 [Amazon Product Review Sentiment Analysis](https://github.com/ashfak-g/Sentiment-Analysis-on-Amazon-Product-Reviews) |
| :--- | :--- |
| **97.44% Accuracy & 0.998 AUC** Healthcare AI platform. Powered by **1D CNN + BiLSTM + Multi-Head Self-Attention** on 187-timestep ECG signals. Classifies 5 cardiac rhythms (N, S, V, F, Q) with Gemini 1.5 Vision API fallback, Flask, PostgreSQL, and multi-role RBAC (Patient/Doctor/Admin). | Production NLP & ML system classifying customer reviews. Features **negation-preserving NLP preprocessing**, class-weight balanced model training (evaluating 5 algorithms), served via **Streamlit Web UI** & **FastAPI REST microservice** with Docker & GitHub Actions CI/CD. |
| 📊 [Business & Data Analytics Dashboard Portfolio](https://github.com/ashfak-g/business-data-analytics-dashboard-portfolio) | 🛢️ [SQL Data Operations & Analytics Suite](https://github.com/ashfak-g/leetcode-sql-50-solutions) |
| Executive Business Intelligence suite built with **Power BI, Excel, DAX & Power Query**. Analyzes sales performance (4.36M+ revenue), delivery efficiency, customer churn, monthly revenue cohorts, and HR attrition metrics. | Production SQL analytics portfolio solving complex data operations. Features **PostgreSQL window functions, CTEs, cohort retention modeling, RegEx text parsing**, and automated ETL database workflows. |

---

### 🧠 Core Architecture & Specializations

| 📊 **BI & Executive Dashboarding** | 🛢️ **SQL & Data Operations** |
| :--- | :--- |
| • Interactive dashboard creation with **Power BI**, **Tableau**, and **Looker Studio**.<br>• Advanced KPI modeling, DAX metrics, and automated reporting.<br>• Executive summary view for data-driven strategic decisions. | • Complex querying using **SQL** & **PostgreSQL** (CTEs, Window Functions, Joins).<br>• Automated data workflows & internal ops apps using **Retool**.<br>• Data validation, ETL pipeline optimization, and DB querying. |
| 🐍 **Python Data Science & Statistics** | 💻 **Web Analytics & Frontend Operations** |
| • Exploratory Data Analysis (EDA) using **Pandas** & **NumPy**.<br>• Data visualization with **Matplotlib** & **Seaborn**.<br>• Statistical hypothesis testing & text pattern parsing using **RegEx**. | • Leveraging **Frontend Experience (Dec 2025 - Aug 2026)** in HTML, CSS, JS & Liquid.<br>• Custom e-commerce data tracking & template data architecture.<br>• Retool UI component customization & internal tool building. |

---

### 💻 Query & Code Snippet: Advanced SQL & Data Operations

```sql
-- Executive Monthly Revenue & Customer Retention Cohort Analysis (PostgreSQL)
WITH MonthlyMetrics AS (
    SELECT 
        DATE_TRUNC('month', order_date) AS sales_month,
        customer_id,
        SUM(order_amount) AS total_spent,
        COUNT(order_id) AS order_count,
        ROW_NUMBER() OVER(PARTITION BY customer_id ORDER BY order_date) AS purchase_rank
    FROM sales_orders
    WHERE status = 'Completed'
    GROUP BY 1, 2
)
SELECT 
    sales_month,
    COUNT(DISTINCT customer_id) AS active_customers,
    ROUND(AVG(total_spent), 2) AS avg_customer_spend,
    COUNT(CASE WHEN purchase_rank > 1 THEN 1 END) AS repeat_buyers
FROM MonthlyMetrics
GROUP BY sales_month
ORDER BY sales_month DESC;
```

---

### 🛠️ Technical Ecosystem

#### 📊 **BI, Data Analytics & Visualization**
[![Power BI](https://img.shields.io/badge/POWER_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![Tableau](https://img.shields.io/badge/TABLEAU-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://tableau.com)
[![Looker Studio](https://img.shields.io/badge/LOOKER_STUDIO-4285F4?style=for-the-badge&logo=googlelookerstudio&logoColor=white)](https://lookerstudio.google.com)
[![Excel](https://img.shields.io/badge/EXCEL-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](#)
[![Retool](https://img.shields.io/badge/RETOOL-3D3D3D?style=for-the-badge&logo=retool&logoColor=white)](https://retool.com)

#### 🛢️ **Databases, SQL & Querying**
[![SQL](https://img.shields.io/badge/SQL-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](#)
[![PostgreSQL](https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![RegEx](https://img.shields.io/badge/REGEX-000000?style=for-the-badge&logo=regex&logoColor=white)](#)

#### 🐍 **Data Science & Statistics**
[![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-11557C?style=for-the-badge&logo=python&logoColor=white)](#)
[![Seaborn](https://img.shields.io/badge/SEABORN-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Statistics](https://img.shields.io/badge/STATISTICS-00599C?style=for-the-badge&logo=scipy&logoColor=white)](#)

#### 💻 **Frontend Experience (Dec 2025 – Aug 2026)**
[![JavaScript](https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Shopify Liquid](https://img.shields.io/badge/SHOPIFY_LIQUID-95BF47?style=for-the-badge&logo=shopify&logoColor=white)](#)

#### 🎯 **Profiles & Platforms**
[![Kaggle](https://img.shields.io/badge/KAGGLE_PROFILE-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/your-username)
[![LeetCode](https://img.shields.io/badge/LEETCODE_PROFILE-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/your-username)
[![GitHub](https://img.shields.io/badge/GITHUB-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ashfak-g)

---

### 💎 Analytics Workflow & Engineering Standards

<details>
<summary>🔍 <b>1. Data Operations, Cleaning & RegEx Extraction</b></summary>
<br>

- **Data Wrangling**: Automated data cleaning workflows using Python (Pandas/NumPy) and SQL.
- **Pattern Mining**: Utilizing **RegEx** to parse unstructured text, logs, and user metadata into clean operational tables.
- **Data Validation**: Ensuring missing values, outliers, and data integrity checks are enforced before ingestion into BI tools.
</details>

<details>
<summary>📊 <b>2. BI Dashboarding & Executive Reporting (Power BI, Tableau, Looker)</b></summary>
<br>

- **DAX & SQL Aggregations**: Writing optimized data models, calculated columns, and measure tables.
- **Visual Storytelling**: Designing intuitive dashboards with dark/light themes, dynamic filters, and drill-through analytics.
- **Retool Integration**: Building custom operational dashboards and internal workflows connected to PostgreSQL databases.
</details>

<details>
<summary>💻 <b>3. Leveraging Frontend Expertise for Data Operations</b></summary>
<br>

- **Web Data Extraction & Analytics**: Utilizing **HTML, CSS, JS, and Liquid** experience (Dec 2025 - Aug 2026) to understand DOM structures, web events, and e-commerce product data schemas.
- **Retool Custom Component Design**: Combining HTML/CSS skills with Retool to craft tailor-made admin panels and data entry apps for operations teams.
</details>

---

### 📮 Let's Connect & Build Data Solutions

Whether you have an opening for a **Data Analyst**, **BI Analyst**, or **Data Operations Analyst**, feel free to connect!

<div align="center">

[![LinkedIn](https://img.shields.io/badge/CONNECT_ON_LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![Kaggle](https://img.shields.io/badge/KAGGLE_PROFILE-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/your-username)
[![LeetCode](https://img.shields.io/badge/LEETCODE_PROFILE-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/your-username)
[![Email](https://img.shields.io/badge/SEND_AN_EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@gmail.com)

</div>
