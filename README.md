# 🇧🇷 Brazilian E-Commerce Growth Pipeline & Logistics Optimization
### Exploratory Data Analysis (EDA), Supply Chain Operations Modeling, and Customer Retention Analytics

## 🎯 Project Objective
This repository contains an end-to-end data analytics framework analyzing **100,000+ commercial orders** from the Olist e-commerce platform spanning 2016–2018. The analysis unifies supply chain logistics performance with downstream business metrics to diagnose fulfillment inefficiencies, map core revenue-generating categories, and evaluate transaction retention loops.

---

## 🛠️ Tech Stack & Vector Libraries
* **Core Analytics & Transformation:** Python (Pandas for structural data wrangling, advanced data cleansing, and multi-table relational schema merging)
* **Mathematical Vectorization:** NumPy
* **Data Visualization Matrix:** Matplotlib, Seaborn

---

## 🧠 Key Business Insights & Operations Discoveries

### 1. The "Acre Paradox" (Fulfillment Optimization Window)
* **Discovery:** Supply chain logistics mechanics systematically outperform consumer-facing checkout promises. In the state of Acre (AC) specifically, shipments arrive an average of **20.7 days earlier** than the conservative deadline communicated to the buyer.
* **Commercial Impact:** Communicating excessively conservative delivery dates at checkout introduces artificial friction, inflating cart abandonment and depressing user conversion rates among high-intent customers prioritizing shipping velocity.

### 2. Revenue Driver Architecture & Vertical Matrix
* **Top Category Vertical:** **Health & Beauty** represents the primary organizational revenue catalyst, followed sequentially by **Watches & Gifts**.
* **Capital Realignment Strategy:** Analytical insights justify a programmatic reduction of marketing capital from low-margin, underperforming categories (such as *Security & Services*) to reallocate ad spend directly into these dominant revenue-generating categories.

### 3. Customer Lifetime Retention Deficit
* **The Metric:** Transactional cohort analysis isolated a narrow, single-purchase dominant **3.12% Repeat Purchase Rate**.
* **Friction Analysis:** Despite 100% of geographic states actively exceeding delivery SLAs, customer cohorts display a steep single-purchase drop-off. This proves that fulfillment speed alone fails to scale customer lifetime value (LTV), highlighting an urgent operational requirement for post-purchase loyalty programs rather than further logistics speed optimizations.

---

## 📊 Visualizations & Query Analytics

### Customer Distribution by Demographic Hub
![Customer Count in Cities](top_cities.png)

### Revenue Contribution by Top Product Category
![Highest Revenue Product Category](highest_product_category.png)

### Supply Chain Delivery Efficiency Gaps by State (Days Early vs. Late)
![Delivery Gaps](delivery_gaps.png)

### Portfolio Transactional Repeat Purchase Elasticity
![Repeat Purchase Rate](Repeat_Purchase_Rate_pie.png)

---

## 💡 Tactical & Strategic Recommendations

* **Conversion Framework Optimization:** Calibrate consumer-facing "Estimated Delivery Windows" to reflect actual historical fulfillment speeds, removing unnecessary friction from the checkout funnel.
* **Customer Retention Pivot:** Build targeted post-purchase lifecycle workflows, personalized product recommendations for winning categories, and loyalty initiatives to directly target the 3.12% repeat purchase bottleneck.
* **Geographic Ad Spend Expansion:** Target paid digital customer acquisition ad spend toward Northern territorial zones, where established logistical velocity already offers a measurable competitive moat over regional market actors.

---

## 📋 Dataset Reference
Analysis built utilizing the verified, open-source **Brazilian E-Commerce Public Dataset by Olist** hosted on Kaggle.  
🔗 [Access Raw Kaggle Data Repository](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
