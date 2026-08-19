# ☕🍵 Tea vs Coffee: Preferences & Lifestyle Trends

An interactive Power BI data analytics project examining global tea and coffee consumption patterns across demographic, lifestyle, and sensory attributes using the **OSEMN** framework.

---

## 📌 Project Overview
This project investigates the multifaceted drivers behind global tea and coffee consumption. Using a dataset of **15,000 respondents** and **34 attributes**, we explore how demographic profiles, daily habits (sleep, stress, physical activity), and sensory preferences (sweetness, aroma, bitterness, acidity) influence beverage choices.

### Key Highlights:
* **Framework:** OSEMN Data Science Life Cycle (Obtain, Scrub, Explore, Model, Interpret)
* **Dataset Scope:** 15,000 records, 34 raw attributes, 7 derived categories
* **Core Tool:** Microsoft Power BI & DAX / Power Query

---

## 📊 Interactive Dashboards
The dashboard is segmented into three tailored stakeholder views:

### 1. Society Dashboard
Focuses on public consumption patterns, daily intake (avg. **2.51 cups/day**), stress impact, sleep duration, and physical activity correlations.
![Society Dashboard](assets/dashboard_society.png)

### 2. Entrepreneur Dashboard
Provides commercial insights including spending behaviour (avg. **$52.02/month**), brand loyalty, workplace demographics (Remote, Office, Student, Hybrid), and café preference levels.
![Entrepreneur Dashboard](assets/dashboard_entrepreneur.png)

### 3. Supplier Dashboard
Details product customization trends such as sugar and milk combinations, brewing styles (Traditional vs. Modern), and sensory profiles (Bitterness, Acidity, Aroma, Taste scores).
![Supplier Dashboard](assets/dashboard_supplier.png)

---

## 🔍 Key Insights & Findings

* **Overall Preference:** Tea holds a slight overall lead (**51.35%**) over coffee (**48.65%**) across diverse demographic backgrounds.
* **Customization Habits:** **Medium sugar** paired with milk is the most favored preparation choice across respondents.
* **Lifestyle Influence:** Daily consumption volume remains remarkably consistent (fluctuating between **2.47 – 2.57 cups/day**) regardless of variations in work stress or sleep duration.
* **Demographics:** Early Career Professionals and Mid-Career/Family Builders represent the largest consumer volume for both beverages.

---

## 🛠️ Methodology (OSEMN Framework)

1. **Obtain:** Sourced multi-variable beverage consumption data (`tea_vs_coffee_global_final.csv`).
2. **Scrub:** Verified data completeness, validated categorical labels, and engineered 7 derivative attributes (e.g., `age_category`, `cupsPerDay_category`, `tasteScore_category`, `sleep_hours_category`).
3. **Explore:** Performed Exploratory Data Analysis (EDA) on distribution metrics and cross-tabulations.
4. **Model:** Built interactive multi-page Power BI dashboards featuring synchronized slicers, KPI cards, and custom visual hierarchies.
5. **Interpret:** Translated dashboard findings into actionable strategies for entrepreneurs, suppliers, and general consumers.

---

## 🚀 How to View the Project

1. **Power BI Desktop:** Clone this repository and open `powerbi/tea_vs_coffee_dashboard.pbix`.
2. **Live Interactive Report:** [Power BI Web Link](https://isiswauitmedu-my.sharepoint.com/:u:/g/personal/2023269148_isiswa_uitm_edu_my/IQAZy4nz5GswRpZNY03850OvAR4c48kTjse712E7HrRICKQ) *(Requires institutional / organizational access)*.
3. **Full Documentation:** Refer to [`reports/TEA VS COFFEE LIFESTYLE & PREFERENCE.pdf`](reports/) for detailed methodology and charts narration.

---

## 👥 Contributors
* **Aina Syafiyah Binti Sambree**
* **Aleya Natasha Binti Abd Rahman**
* **Amirah Atifah Binti Subki**
* **Gloria Linda Anak Robert Nyambong**
* **Puteri Adriana Binti Noor Azli**

---
*Note: This project was conducted for academic purposes using synthetic data to demonstrate end-to-end data analytics and business intelligence workflows.*
