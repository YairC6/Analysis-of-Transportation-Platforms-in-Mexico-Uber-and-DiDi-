# 🚗 Analysis of Transportation Platforms in Mexico (Uber and DiDi)

**Author:** Yair Carrillo Maldonado  
**Date:** July 20, 2025

---

## 📋 Project Description

This project analyzes the growth, user preferences, and behavior on mobility platforms such as **Uber** and **DiDi** in Mexico. The analysis is based on real-world data obtained from **Sensor Tower** and **Statista**, covering the years from 2018 to 2024.

---

## 🗃️ Dataset Overview

The dataset includes key variables to understand the market performance of each platform:

- **Year** (`Year`)
- **Quarter** (`Quarter`)
- **Platform** (`Plataform`)
- **Active Users in Mexico** (`Active_Users_MX`)
- **Weekly Downloads** (`Downloads_Per_Week`)
- **Market Share (%)** (`Market_Share`)
- **Average Trips per User per Week** (`Avg_Trips_Per_User_Per_Week`)

---

## 📊 Analysis Highlights

- **Growth of Active Users Over Time**  
  A line plot comparing the user growth trends of Uber and DiDi.

- **Yearly Market Share Comparison**  
  A bar chart displaying market share by year for each platform, with value labels.

- **Distribution of Average Trips per User**  
  A boxplot showing trip distribution per user across platforms.

- **Descriptive Statistics Table**  
  Summary table including median, quartiles, and min/max values for weekly average trips per user.

---

## 📈 Key Insights

- **Uber** consistently leads the market in terms of user base and market share.
- **DiDi** shows a steady increase in both active users and average trips per user.
- Overall, ride frequency per user has shown a positive trend since 2018.

---

## 📁 Files Included

- `mobility.csv` – The dataset used in the analysis.
- `analisis_plataformas.ipynb` – Jupyter Notebook containing all the code and visualizations.
- `README.md` – This documentation file.

---

## 📚 Data Sources

- [Sensor Tower (2024) - Top 5 Carpooling and Ridesharing Apps Performance](https://sensortower.com/blog/2024-q3-unified-top-5-carpooling%20and%20ridesharin)
- [Sensor Tower (2024) - Navigating LatAm’s Ride-Hailing Landscape](https://sensortower.com/blog/navigating-lat-ams-ride-hailing-landscape-growth-co)
- [Statista (2025) - Shared Mobility Statistics and Facts](https://www.news.market.us/shared-mobility-statistics)

---

## 🧠 Technical Requirements

This project was developed in **Jupyter Notebook** using the following Python libraries:

```python
pandas
seaborn
matplotlib
