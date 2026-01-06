# 📊 YouTube Global Trends: Business Intelligence & Market Analysis

## 🎯 Project Objective
The goal of this project was to engineer a **Business Intelligence (BI) solution** to track and analyze the dynamics of viral content on YouTube. By transforming raw historical data into an interactive analytical pipeline, I identified key performance drivers and behavioral patterns across global markets to optimize digital marketing strategies.

## 🛠️ Data Engineering & Architecture
The project follows a structured data pipeline from raw ingestion to cloud-based visualization:

* **Source:** `trending_by_time.csv` (Historical trend logs).
* **Dimensional Modeling:** Data was structured into three core dimensions:
    * **Temporal:** `trending_date` for time-series forecasting.
    * **Geographic:** `region` for market segmentation (US, India, France, Russia, etc.).
    * **Categorical:** `category_title` for content performance indexing.
* **KPI Definition:** The primary metric is `videos_count`, used to quantify the density of engagement and market share.

## 📈 Visual Analytics & EDA
I developed an interactive dashboard in **Tableau** that enables granular **Exploratory Data Analysis (EDA)** through:
* **Time-Series Evolution (Stacked Area Chart):** Analyzing the "market share" of content categories over time to detect seasonal trends.
* **Relative Distribution (Pie Chart):** Identifying geographic clusters with the highest digital engagement.
* **Strategic Quadrant Analysis:** Classifying categories into **Stars** (High-growth/High-volume) and **Stable Baselines** (Consistent traffic).

## 💡 Data-Driven Insights
1.  **US Market Specifics:** Detected a unique statistical preference for **"Science & Technology"** content in the US, outperforming global averages for this niche.
2.  **Digital Infrastructure Impact:** Analysis confirms that trend volume is more closely correlated with **internet penetration and engagement density** than with total population or geographic size.
3.  **Content Drivers:** "Music" and "Entertainment" remain the global engines of traffic, while "News & Politics" maintains a stable, low-variance daily presence.

## 🔗 Live Interactive Dashboard
The full automated dashboard is deployed and available for real-time interaction:
👉 **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/sprint_12_tripleten/Dashboard1?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

## 📂 Project Deliverables
* `trending_by_time.csv`: Raw source dataset.
* `sprint_12_tripleten.twbx`: Packaged Tableau Workbook.
* `Presentacion_Analisis_YouTube.pdf`: Executive report with statistical conclusions.

---
**Tech Stack:** Tableau Desktop | Data Pipelines | Time-Series Analysis | Business Intelligence.
**Analyst:** Marcel Andrés Palma Céspedes
