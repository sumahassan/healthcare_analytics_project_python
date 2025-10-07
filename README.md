# **Five-Year Trends and Cost Analysis of Respiratory Diseases in the U.S. Medicare System**

Introduction
The top 5 most populated states in the USA are California, Texas, Florida, New York, and Pennsylvania. According to recent data, California and Texas are among the most polluted states in the country. California, in particular, has cities like Los Angeles and Bakersfield that rank high in pollution levels due to factors like vehicle emissions and industrial activities. Texas also faces significant pollution challenges, especially in urban areas.

Air pollution has a direct impact on respiratory health. Exposure to pollutants like particulate matter (PM2.5) and ozone can lead to respiratory conditions such as asthma, chronic bronchitis, and other chronic obstructive pulmonary diseases. Long-term exposure can also increase the risk of lung cancer and cardiovascular diseases. Children, the elderly, and those with pre-existing health conditions are particularly vulnerable.

The cost of treating respiratory conditions can vary significantly across states due to differences in healthcare systems, insurance coverage, and local healthcare costs. Generally, states with higher population may have higher pollution which increases the prevalence of respiratory cases. With this study I am trying to understand are these facts true.

This project explores the relationship between **number of cases reported**, and **respiratory health costs** across U.S. states.  
It focuses on highly populated states such as **California**, **Texas**, **Florida**, **New York**, and **Pennsylvania**, aiming to understand how pollution levels affect **respiratory disease prevalence** and **treatment costs**.

---

## 🎯 Project Objective

The goal of this project is to analyze whether **states with higher populations** tend to have **higher number of cases and costs of respiratory diseases**.

Specifically, the project aims to:
- Identify trends linking **population rates**, and **respiratory illness rates**.  
- Compare **treatment costs** for respiratory conditions between high- and low-population states.  
- Create **interactive visualizations** to present key insights effectively.

---

## 🧰 Tools and Technologies

| Tool | Purpose |
|------|----------|
| **Python (Pandas, Matplotlib, Seaborn)** | Data cleaning, processing, and analysis |
| **Tableau** | Interactive dashboard creation and data visualization |
| **Jupyter Notebook** | Analysis and documentation of results |
| **CSV Files** | Data storage and import/export |

---

## 🗂️ Dataset Description
The dataset used in this project is the **Medicare Outpatient Data** which includes information such as:
- Provider Name & City  
- Number of Outpatient Cases  
- Average Total Cost  
- Average Medicare Payment  
- Average Covered Charges  

**Data Source:** Centers for Medicare & Medicaid Services (CMS)  


## 💡 Key Insights

- **California** and **Texas** have some of the **highest pollution levels** and **treatment costs**.  
- States with **larger populations** generally show **higher case counts** and **treatment demand**.  
- A positive correlation was found between **PM2.5 concentration** and **average cost of respiratory treatments**.  
- Some states with **lower pollution but high costs** may indicate inefficiencies or healthcare pricing differences.  

---

## 📈 Tableau Dashboard Preview

<p align="center">
  <img src="screenshots/air_pollution_dashboard.png" alt="Air Pollution Dashboard" width="700">
</p>

*(Replace the image path above with your actual Tableau screenshot or dashboard link.)*

---



## 📊 Analysis Performed
- Cleaned and processed Medicare outpatient dataset using Python  
- Aggregated data at the **city level**  
- Compared **average cost vs number of reported cases**  
- Created interactive visuals in Tableau:
  - Scatter plots showing cost-to-case relationship  
  - City-wise comparison dashboards  
  - Trend charts showing average cost variation  

---

## 💡 Key Insights
- Some cities show **high outpatient costs despite low case counts**, suggesting potential inefficiency or specialized services.  
- Cities with **large case volumes** tend to have **lower average costs per case**, possibly due to economies of scale.  
- Cost variation across regions indicates opportunities for **standardization and resource optimization**.  

---

