# 📊 AI Job Market & Students AI Usage Analytics Report (2020–2025)

## 📝 Overview

This repository contains a comprehensive Power BI-based analytical study that examines the evolution of the **AI job market** and **AI adoption among college students** between 2020 and 2025. The project merges diverse datasets, performs advanced DAX-driven calculations, and delivers actionable insights through five interactive dashboards.

---

## 🛠️ 1. Installation and Setup

### Tools & Technologies Used:

* **Microsoft Power BI Desktop** – For interactive data visualization and dashboard creation.
* **Excel/CSV Files** – Primary data source formats used throughout.
* **DAX (Data Analysis Expressions)** – For advanced metrics, KPIs, and custom logic.

> 💡 *Ensure Power BI Desktop is installed before opening the `.pbix` file. All transformations and visuals are built-in.*

---

## 📂 2. Data Preparation and Transformation

### Datasets Used:

| Dataset                    | Description                                                             |
| -------------------------- | ----------------------------------------------------------------------- |
| `ai_job_dataset.csv`       | AI job market data including salaries, remote work %, and company size. |
| `ai_job_dataset1.csv`      | Extension with job title and industry breakdowns (\~5,000 records).     |
| `salaries.csv`             | Historical salary data by job title and company size (\~1,500 records). |
| `Students.csv`             | AI tool usage across disciplines and academic years (\~3,600 records).  |
| `AI On-Campus Survey.xlsx` | Survey on AI awareness and tool usage (258 responses).                  |

### Key Transformations:

* Standardized column headers for consistency.
* Normalized experience and company size values (e.g., `EN`, `MI`, `EX`).
* Extracted `Month-Year` field from timestamp columns for time-series analysis.
* Merged datasets on common fields for enriched analytics.
* Converted survey Likert-scale responses to numeric format.

---

## 📈 3. Metrics and Calculated Measures (DAX-Based)

### Student AI Usage Metrics:

* `% Knows ChatGPT`
* `Average Career Interest in AI`
* `Average Personal Use of AI`
* `Average Work Use of AI`

### AI Job Market Metrics:

* `Total Employees`
* `Average Salary (USD)`
* `Average Remote Work %`
* `Salary by Title/Experience Level`
* `Benefit Score & Required Experience`

---

## 📊 4. Dashboards Overview

### 🔹 Dashboard 1: **2020–2025 Tech Salary Analysis**

* **Avg Salary**: \$158,000 | **Remote Work**: 22% | **Employees**: 73,000
* **Key Insights**:

  * Senior roles dominate high salaries.
  * Large firms offer better pay and global access.
  * Limited but growing remote work adoption.

### 🔹 Dashboard 2: **AI Job Trends and Salaries – Part I**

* **Avg Salary**: \$115,000 | **Experience Required**: 6 years
* **Key Insights**:

  * Education (e.g., Master’s degree) significantly impacts earnings.
  * High AI job demand in Retail, Media, and Automotive.
  * Experience positively correlates with salary until mid-career.

### 🔹 Dashboard 3: **AI Job Trends and Salaries – Part II**

* **Avg Salary**: \$122,000 | **Benefit Score**: 7
* **Key Insights**:

  * Deep Learning and CV specialists earn more.
  * Tech and Consulting industries offer salary stability.
  * Diminishing salary returns after 15+ years experience.

### 🔹 Dashboard 4: **AI On-Campus Usage Report (Survey-Based)**

* **Total Students**: 258 | **Awareness of ChatGPT**: \~85.66%
* **Key Insights**:

  * AI awareness is high, but usage varies by field.
  * Engineering and Business students show high interest.
  * Seasonality affects AI exploration trends.

### 🔹 Dashboard 5: **AI Tool Usage Insights (Wider Student Survey)**

* **Students Surveyed**: 3,614 | **Avg Daily Usage**: 3 hours
* **Key Insights**:

  * Popular tools: ChatGPT, Gemini, Copilot.
  * AI use linked to device/internet availability.
  * 52% of faculty restrict AI use in classrooms.

---

## 💡 5. Key Recommendations

### AI Job Market:

1. Promote hybrid work in mid-sized firms.
2. Standardize job titles across industries.
3. Benchmark salaries for startups and underrepresented roles.
4. Align job experience requirements with postings.
5. Boost DEI and geographic salary normalization.

### Academic AI Adoption:

1. Launch AI literacy programs across all departments.
2. Provide devices and connectivity for underserved students.
3. Encourage ethical and responsible AI usage.
4. Facilitate semester-wise AI engagement tracking.
5. Run AI career mentoring and student-industry bridges.

---

## 🔗 6. Strategic Alignment

This project underscores the **dual transformation** in AI:

* The **professional AI landscape** is maturing, with nuanced roles and compensation.
* The **academic environment** is catching up, with students showing increasing curiosity and moderate engagement.

**Bridging these worlds** through structured education-to-employment pipelines, faculty enablement, and AI infrastructure will ensure a sustainable and inclusive AI future.

---

## ✅ 7. Conclusion

This repository showcases end-to-end analytics — from raw data transformation to interactive insight delivery — on a critical and timely topic: **AI's impact on workforce dynamics and student readiness**.
---

**Dashboard Timeline**: 2020–2025
**Toolset**: Power BI, Excel, DAX

---
