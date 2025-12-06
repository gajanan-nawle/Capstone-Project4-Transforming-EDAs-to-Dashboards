# 🌟 Capstone Project 4: Amazon Prime EDA Dashboard

## Project Overview 🎯

This project serves as the final capstone for the Data Visualization Challenge, focused on transforming analytical insights derived from a prior **Python Exploratory Data Analysis (EDA)** on **Amazon Prime Video titles and personnel** into a professional, interactive dashboard using **Power BI**.

The implementation demonstrates proficiency in the full Business Intelligence workflow, delivering a visually compelling, data-driven report adhering to a **Cinematic Dark Theme**. 

[Image of a Power BI dashboard with a dark theme and cinematic visuals]


---

## Problem Statement ❓

The challenge addresses the **gap between static analytical output and actionable business intelligence**. Insights derived from the initial Python EDA are confined to raw data and code, lacking the interactivity, accessibility, and scalability required for strategic review. The problem is to **design and implement a professional, interactive dashboard** that effectively translates complex findings into clear, visual data-driven decision support.

---

## Key Technical Decisions & Features ⚙️

This project required rigorous data modeling and cleaning within Power Query to ensure analytical integrity:

* **Advanced Data Cleaning:** Implemented **Split Column by Delimiter (Rows)** and **Replace Values/Trim** steps on the `genres` and `production_countries` columns to correctly unpivot nested text strings into analyzable fields.
* **Modeling for Accuracy:** Created a single, refined dataset structure to ensure that core metrics, such as **Total Distinct Titles**, were calculated accurately despite the inherent duplication in the original merged dataset.
* **Design & UX:** Applied a **Cinematic Dark Theme** with strategic use of **Vibrant Red** and **Electric Teal** accents to highlight key performance indicators (KPIs) and improve user focus.
* **Interactivity:** Features user-friendly slicers and cross-filtering between visuals for smooth navigation and deep-dive analysis.

---

## Final Insights & Conclusion 📈

* **Content Focus:** The library is **86% skewed toward Movies**, with **Drama** confirming its position as the \#1 genre.
* **Aggressive Growth:** Content volume shows **exponential growth since 2015**, visualizing a strong, competitive investment strategy.
* **Quality Benchmark:** The mean IMDb score of **5.98** confirms content quality is generally **'average,'** indicating a clear need to focus on acquiring high-rated (7.0+) titles.
* **Strategic Gap:** The saturation in core genres presents a clear opportunity for competitive investment in under-represented, high-value niches like **Sci-Fi and Animation**.
* **Hidden Asset:** The prevalence of classic talent (Westerns/older films) confirms the deep catalog is a strong, marketable asset for targeted campaigns.

---
