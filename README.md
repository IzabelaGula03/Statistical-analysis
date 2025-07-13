# 📊 Statistical Analysis of Socio-Economic and Environmental Indicators

## 👩‍💻 Author  
Izabela Guła  
AGH University of Science and Technology, Kraków  
Informatics and Econometrics  

## Overview  
This project explores the relationships between socio-economic development (GDP, urbanization, industry/agriculture shares) and environmental impact (CO₂ emissions, renewable energy use) using data from **Gapminder** (1990–2015). Key analyses include:  
- **Hypothesis testing** (t-tests, Wilcoxon, Pearson/Spearman correlations).  
- **Regression modeling** (linear trends between urbanization and CO₂ emissions).  
- **Visualizations** (scatter plots, histograms, box plots).  

Conducted in **R** and **JASP**, the study reveals insights like:  
- 🌍 Higher GDP correlates with increased CO₂ emissions (ρ = 0.91, p < 0.001).  
- 🏙️ Urbanization shows a strong positive link to CO₂ (r = 0.64, p < 0.001).  
- 🌱 Countries with lower industrial/agricultural GDP shares tend to use more renewable energy.  

---

## 🔍 Key Findings  
1. **Renewable Energy Adoption**:  
   - Countries with <20% industrial GDP use **12.3%** renewable energy on average vs. **1.8%** for industrial-heavy economies (p < 0.05).  
   - Agriculture-dominated economies show **4%** renewable use, but variance is high.  

2. **Urbanization & CO₂**:  
   - Urbanization explains **76%** of CO₂ emission variability (R² = 0.76, regression).  
   - Tested with Pearson (r = 0.64) and Kendall-Tau (τ = 0.56, both p < 0.001).  

3. **GDP vs. CO₂**:  
   - Wilcoxon test confirms median CO₂ differs significantly between high/low GDP groups (p < 2.2e-16).  
   - Spearman’s ρ = 0.91 indicates near-monotonic relationship.  

---

## 🛠️ Tools & Methods  
- **Software**: RStudio, JASP.  
- **Tests**:  
  - Parametric (t-tests, Pearson).  
  - Non-parametric (Wilcoxon, Spearman).  
- **Data Cleaning**: Removed Oceania (missing data), aggregated Americas.  

---
