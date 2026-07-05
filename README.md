# Enterprise Job Market Intelligence Dashboard 📊

An interactive, end-to-end Power BI Business Intelligence application designed to analyze data tech jobs globally. This dashboard processes underlying market data to uncover trends regarding recruitment patterns, salary distribution benchmarks across core job titles, structural remote work configurations, and geographical hubs.

## 🔗 Project Architecture & Overview
This solution transforms messy job listing details into structured, visual insights across two specialized dashboard perspectives:

1. **Market Summary Overview:** Explores macroeconomic job volume metrics, temporal hiring trends, and comprehensive salary matrix breakdowns.
2. **Deep-Dive Job Title Drill-Through:** Allows end-users to select a specialized tech profile and drill dynamically into deep micro-metrics like compensation bands, corporate benefit distribution, and primary job search platform performance.

---

## 🖥️ Dashboard Interface & Pages

### 1. Data Jobs Summary (Main Page)
Provides a global operational look at tech hiring volume and benchmark performance metrics. 
* **Dynamic Slicer Navigation:** Clean dropdown control to filter the canvas view by individual core roles.
* **Aggregated Performance KPIs:** High-impact status indicators highlighting total job inventory count, average job sentiment/ratings, and median salary rates.
* **Trend & Matrix Insights:** A temporal line chart tracking recruitment flows alongside a deep-dive matrix table containing custom trend sparklines.

![POWER_BI_DASHBOARDS](/images/PB%20image(1).png)
*Figure 1: Main Overview Canvas showcasing global job distribution, temporal patterns, and macro salary benchmarks.*

### 2. Job Title Drill-Through Canvas (Detail Page)
Accessible via conditional drill-through buttons, this window isolates unique job parameters for laser-focused competitor benchmarking.
* **Salary Band Gauges:** High/Low/Median compensation ranges visualized via advanced visual gauge scales.
* **Benefits & Work Style Proportions:** Multi-segment donut charts analyzing structural proportions of WFH (Work From Home) access, degree requirements, and healthcare provisioning.
* **Geographical Hub Mapping:** Interactive map interface plotting candidate density and platform-by-platform job volumes.

![POWER_BI_DASHBOARDS](/images/PB%20image(2).png)
*Figure 2: Micro-insights drill-through view demonstrating localized clusters, benefit rates, and key platform performance for specific roles.*

---

## 🛠️ Tech Stack & Key Features Implemented

* **BI Platform:** Microsoft Power BI Desktop
* **Data Connectivity & Processing:** Power Query (M Language) for structural column engineering, data type normalization, and cleansing.
* **Analytical Modeling:** Created dynamic relationships between parameters using DAX (Data Analysis Expressions) computations for `Median` and `Average` metrics.
* **Advanced Visual Design & UX:**
  * Custom layout grouping using polished, desaturated container borders.
  * Cross-filtering and interactive tooltips.
  * Advanced conditional visuals including Gauge meters, Matrix heat maps, and custom embedded Sparklines.
  * Seamless Page-to-Page Drill-Through mechanics.

---

## 📈 Key Market Insights Uncovered

1. **Volume Concentration:** Data Engineering and Data Analytics represent the highest volume sectors in the contemporary market landscape, combining for over 240K+ active postings.
2. **Compensation Apex:** Senior Data Scientists and Machine Learning Engineers command the premium top-tier median salaries, pushing benchmarks past the $155K/year valuation scale.
3. **Benefit baselines:** Modern tech infrastructure continues to showcase highly localized patterns; however, core benefits like health insurance configurations remain foundational drivers across top-tier listings.

---

## 🚀 How to Interact with the Local Project File

1. Clone this repository to your local directory:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)

1. Ensure you have the latest version of **Power BI Desktop** installed.
2. Open the `.pbix` file included within this root directory.
3. Use **Ctrl + Click** on the **Drill Through to Job Title** button to experience the dynamic multi-canvas navigation path!