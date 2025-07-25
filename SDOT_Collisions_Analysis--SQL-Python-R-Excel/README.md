# 🚗 Seattle Vehicle Collisions Analysis (SDOT) --SQL-Python-R-Excel

This project analyzes vehicle collision data in Seattle using datasets published by the Seattle Department of Transportation (SDOT). The goal is to identify patterns, contributing factors, and strategic opportunities for reducing accidents and enhancing road safety.
  
> 📅 **Date Range of Analysis:** 2004 – 2025  
> 📁 **Tools Used:** SQL, Python, R, Excel

---

## 📌 Project Overview

Every year, thousands of collisions occur in Seattle — leading to injury, congestion, and economic costs. This project explores:
- Key risk factors such as **Speeding**, **DUI**, and **Inattentiveness**
- Temporal trends by **year**, **month**, **day of week**, and **time of day**
- Environmental conditions such as **light**, **weather**, and **road surfaces**
- **Logistic regression modeling** to predict severity
- **Recommendations** to support Vision Zero initiatives and smarter urban planning

---

## 🧠 Key Insights

| Factor           | Impact on Severity                                          |
|------------------|--------------------------------------------------------------|
| Speeding         | Increases fatal crash likelihood by **2.55x**               |
| DUI              | Raises severity odds by **2.03x**                           |
| Inattentiveness  | Leads to more rear-end crashes but lower fatality risk     |
| Lighting         | Dark, unlit conditions have a **2.16x** higher severity risk |
| Weather          | Wet/Icy conditions reduce severity — cautious driving effect|

---

## 🧪 Methodology

- **Dataset:** [SDOT Collisions – All Years](https://data.seattle.gov/dataset/SDOT-Collisions-All-Years/qdnv-25h8) (253,884 records, 50 columns)
- **Data Cleaning:** Python & pandas used for cleaning, remapping, and time bucketing
- **Exploratory Analysis:** SQL queries to examine collision patterns
- **Modeling:** Logistic Regression in R to understand severity predictors

---

## 📈 Visual Insights

- 📉 **Accidents peaked** in October and December; lowest during July
- 🕒 **Noon and evening** hours saw highest collision counts
- 🧍 **Pedestrian-involved** fatal accidents mostly occur in dark/lighted areas
- 📉 **2020 crash count** dropped significantly due to COVID-19
- 🚦 **Aurora Ave N** and **6th Ave & James St** are major hotspots

---

## 📊 Logistic Regression Model

| Predictor        | Odds Ratio (OR) | Interpretation                                   |
|------------------|------------------|--------------------------------------------------|
| Speeding         | 2.55             | Significantly higher risk of severe accidents    |
| DUI              | 2.03             | Doubles the odds of fatal/injury collisions      |
| Inattention      | 0.57             | Associated with minor (low-speed) incidents      |
| Dark Lighting    | 2.16             | High risk in areas with poor visibility          |
| Wet Roads        | 0.75             | Severity lower due to cautious driving behavior  |
| Snow/Ice         | 0.42 – 0.54      | Drivers more alert; less likely to be fatal      |

---

## 💡 Strategic Recommendations

- 🚧 Target enforcement and awareness in **October & Fridays**
- 🚦 Improve lighting in high-risk intersections and left-turn lanes
- 🚔 Enforce DUI checkpoints in **December** and late nights
- 🧠 Educate on speeding dangers — especially during low-traffic hours
- 📍 Deploy smart traffic systems in accident-prone corridors

---

## 📁 Project Files

- `DataCleaning_Python.ipynb` – Time processing, geospatial conversion, cleaning
- `Insights_SQL.sql` – Weekly, monthly, and condition-based analysis queries
- `LogisticModel_Severity.R` – Regression model for predicting accident severity
- `Presentation.pptx` – Final summary deck
- 'Python Notebook' - Python Data Analysis

---

## 📚 References

- [SDOT Open Data](https://data.seattle.gov/dataset/SDOT-Collisions-All-Years/qdnv-25h8)  
- [Ride the Ducks – Seattle Times](https://www.seattletimes.com/seattle-news/ride-the-ducks-vehicle-collides-with-bus-on-aurora-bridge/)  

---

## 👩‍💻 Author

**Pallavi Khabale**  
🎓 Master’s in Supply Chain Management, University of Washington (2024–2025)  
🔗 [LinkedIn](https://www.linkedin.com/in/pallavi-khabale)  
📧 [Email](mailto:pallavikhabale@gmail.com)

---
