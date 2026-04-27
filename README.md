# 🌳 Ireland Afforestation Decision Support System (DSS)

A Tableau-powered analytics dashboard designed to support **evidence-based afforestation planning in Ireland** by combining **carbon sequestration forecasts, soil suitability analysis, species ranking, and policy payment comparisons**.

> Built as part of MIS41040 Assignment 2 – University College Dublin. :contentReference[oaicite:0]{index=0}

---

## 📌 Project Overview

Ireland has one of the lowest forest cover rates in Europe (approx. 11–12%). To address this, the Irish government introduced the **National Afforestation Scheme (2023–2027)** with the goal of increasing forest cover to **18%**.

This project develops an interactive **Decision Support System (DSS)** using **Tableau** to help:

- Government planners  
- Forestry agencies  
- Environmental analysts  
- Landowners / farmers  
- Policy makers  

make informed planting decisions using environmental, financial, and sustainability metrics.

---

## 🎯 Objectives

The dashboard helps answer key strategic questions:

- Which tree species capture the most CO₂ over time?
- Which species are best suited to different Irish soil moisture regimes?
- How do government premium payments compare across species?
- What planting mix balances carbon capture, biodiversity, and economics?
- How can Ireland meet long-term afforestation targets efficiently?

---

## 📊 Dashboard Features

### 1️⃣ CO₂ Sequestration Forecast by Stand Age
Interactive line chart showing cumulative CO₂ captured by each species over time.

**Insights:**
- Douglas Fir performs strongest long-term.
- Corsican Pine also performs strongly across policy horizons.
- Useful for evaluating 2030 / 2040 climate targets.

---

### 2️⃣ Soil Moisture Suitability Heatmap
Species suitability across soil moisture conditions:

- VS = Very Suitable  
- S = Suitable  
- M = Moderate  
- U = Unsuitable  

**Insights:**
- Corsican Pine shows strong versatility.
- Fresh soils are suitable for most species.

---

### 3️⃣ Species Carbon Ranking
Dynamic ranking of species based on cumulative sequestration at selected stand age.

Typical ranking:

1. Douglas Fir  
2. Corsican Pine  
3. Oak  
4. Birch  
5. Sitka Spruce

---

### 4️⃣ Economic Policy Payment Comparison
Compares total premium payments per hectare for farmers/non-farmers.

**Insights:**
- Most species receive equal support.
- Sitka Spruce receives lower total incentives.

---

### 5️⃣ CO₂ Over Time by Species
Stacked bar chart showing total carbon accumulation over planting periods.

---

## 🌲 Species Included

| Code | Species |
|------|---------|
| DF | Douglas Fir |
| CP | Corsican Pine |
| OK | Oak |
| BE | Birch |
| SS | Sitka Spruce |

---

## 📈 Recommended Planting Strategy (Balanced Scenario)

| Species | Allocation |
|--------|------------|
| Douglas Fir | 30% |
| Corsican Pine | 25% |
| Oak | 20% |
| Birch | 15% |
| Sitka Spruce | 10% |

### Expected Outcomes

- **1.43 million tCO₂e** captured by Year 20  
- **4.15 million tCO₂e** captured by Year 50  
- **119 million trees** required over scheme period

:contentReference[oaicite:1]{index=1}

---

## 🛠 Tools & Technologies

- **Tableau Public** – Dashboard development & visualization  
- **Excel / CSV** – Data preparation  
- **GIS Soil Data** – Land suitability mapping  
- **Carbon Modelling Data** – Woodland Carbon Code benchmarks

---

## 📂 Data Sources

This DSS integrates multiple datasets:

- UK Woodland Carbon Code  
- Irish Soil Information System (ISIS)  
- UK Forest Research datasets  
- Species ecological profiles  
- Irish Afforestation Scheme payment data

---

## 🚀 Live Dashboard

🔗 **View Tableau Dashboard:**  
https://public.tableau.com/views/BDSS_Forestation/Dashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

---

