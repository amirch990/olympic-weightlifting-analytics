# 🏋️ Olympic Weightlifting Analytics (2000–2020)

This project is a full-stack sports analytics case study exploring 20 years of Olympic weightlifting data.  
It demonstrates deep technical analysis, storytelling, and domain understanding — from raw data to dashboards and custom performance metrics.

---

## 📌 Overview

This project answers a central question:

> **What separates Olympic podium athletes from those who just miss it?**

To explore that, I built:

- 💡 Custom performance KPIs:
  - **CPP** (Critical Podium Point): Near-misses between 3rd and 4th place
  - **CCP** (Critical Champion Point): Battles for 1st vs 2nd place
- 📈 Athlete retention and **cohort flow analysis**
- 🔍 Statistical comparisons of medalists vs non-medalists
- 📊 Interactive dashboards (Tableau & Plotly)

---

## 🧰 Tools & Technologies

| Stack      | Tools & Libraries |
|------------|-------------------|
| **Python** | Pandas, Plotly, Seaborn, Regex, Wikipedia API, Pycountry |
| **SQL**    | DuckDB (embedded SQL inside Python), CTEs, Window Functions |
| **EDA**    | Pandas Profiling, Sweetviz, Joyplot |
| **BI**     | Tableau (including LOD Expressions), Sankey Diagrams |

---

## 🧱 Project Structure

### 📦 Data Enrichment & Cleaning
- Cleaned raw Kaggle dataset (319 missing values reduced to 24)
- Extracted standardized country names using `pycountry` and `Wikipedia API`
- Created derived columns (e.g., weight class, podium status)

### 📊 Exploratory Data Analysis
- Automated profiling with Sweetviz & Ydata Profiling
- Manual deep-dive into athlete bodyweight, lift totals, and medal outcomes
- Retention analysis using **cohort modeling** and **Sankey Diagrams**

### 🧮 KPI Engineering
- **CPP**: Measures how close athletes were to stepping on the podium
- **CCP**: Measures how tightly contested gold medals were
- Normalized metrics (RTD, RBD) to measure closeness by percentage

### 📈 Dashboards & Visualizations
- Tableau dashboards with cohort filters, tooltips, and LOD expressions
- Plotly dashboards for side-by-side CCP/CPP interactive exploration

---

## 📄 Full Presentation

Includes:
- Step-by-step methodology
- Full visuals
- Broadcaster-style reporting

---

## 🎯 Key Takeaways

- Data storytelling is most powerful when insights are *discovered*, not just *answered*.
- The podium isn't always won by lifting more — sometimes it’s bodyweight, tactics, or consistency.
- Close calls matter: a 100g difference or 1kg lift can be the line between legacy and loss.

---

