# 🌿 AirPurity Project

**AirPurity** is an AI-based solution built for the **Green Skilled AI seminar** (sponsored by Shell Petroleum). It helps analyze and optimize whether **Silver Oak trees** planted near factories are enough to offset greenhouse gas emissions — now and in the next 2 years. It also suggests how to use land more efficiently for planting.

---

## ✅ What It Does

- Predicts if current trees are enough to offset emissions
- Forecasts emissions for the next 2 years
- Optimizes land usage for planting trees
- Suggests best locations for planting using factory coordinates

---

## 📥 Input Data

- `total_land_area`: Available area for planting (sq. meters)
- `total_trees`: Number of Silver Oak trees planted
- `emission_current`: Current GHG emissions (tons/year)
- `emission_future`: Predicted emissions for 2 years
- `air_quality_index`: Air quality near the factory
- `emission_quality`: Type of gases emitted
- `latitude`, `longitude`: Location of the factory

---

## 🎯 Output

- `trees_sufficient`: True or False (Are trees enough for emission control?)

---

## 🛠 Tech Stack

- **Python**: For backend and machine learning
- **Pandas, Scikit-learn, XGBoost**: For data handling and model building
---

👨‍💻 Created By
Ashutosh – Engineering student, passionate about AI and sustainability.


📌 Future Plans
Use real-time air quality data

Include tree growth rates

Add satellite imagery for better analysis
