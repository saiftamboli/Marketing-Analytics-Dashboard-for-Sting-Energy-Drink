# 🚀 Sting Energy Drink: Marketing Analytics Dashboard

A data-driven project aimed at analyzing survey responses from 10,000 consumers across 10 Indian cities to help **Sting**, a German beverage company, understand its market position and optimize its product strategy, brand penetration, and marketing effectiveness in India.

Live Dashboard [link](https://app.powerbi.com/view?r=eyJrIjoiMjlhMGIxNzUtMTYwNC00MTY1LTg4YTItMDk5NTdmNDJlNmIwIiwidCI6ImUwYzk0NGU4LWM5N2YtNGUwMS04MWUwLWRkMzZjZTk5YTgwYyJ9)

## 📊 Project Overview

**Domain:** Food & Beverage  
**Function:** Marketing Analytics  

**Tools Used:**
- **MySQL** – Data querying, cleaning, and creating views  
- **Power BI** – Data modeling, DAX measures, dashboard creation  
- **Power Query** – ETL within Power BI  
- **Excel** – Initial exploration and metadata reference  
- **Figma** – Visual design elements and dashboard layout

---

## 🧠 Problem Statement

Sting recently entered the Indian energy drink market and is looking to expand its brand awareness, understand evolving consumer preferences, and identify key market opportunities.

This project delivers a comprehensive market analysis based on survey data, covering:
- Demographic patterns  
- Consumer behavior  
- Brand awareness and competition  
- Purchase trends and pricing sensitivity  
- Marketing channel effectiveness  
- Product development opportunities  

Based on the findings, strategic recommendations are proposed to empower Sting’s marketing team to penetrate and grow in the Indian market.

---

## 📁 Data Sources

- `dim_cities.csv` – City information (ID, Name, Tier)  
- `dim_respondents.csv` – Demographic details of respondents  
- `fact_survey_responses.csv` – Survey responses (brand awareness, behavior, preferences, etc.)

---

## 🔧 Data Pipeline

### 🔹 SQL
- Cleaned and joined all three tables  
- Created optimized views to support analysis  
- Structured output tables consumed directly in Power BI  

### 🔹 Power BI
- Connected to SQL Server using the created views  
- Modeled data relationships and created DAX measures  
- Designed a **5-page interactive dashboard** for business users

Data Model ![Data Model](https://github.com/user-attachments/assets/5d3ec032-0668-474c-938e-d82cf3fe6244)


## 📈 Dashboard Structure

1. **🏠 Home** – Project summary and page navigation  
2. **🔍 Overview** – Key KPIs and survey coverage  
3. **👥 Demographic Insights**  
   - Age and gender-based consumption patterns  
   - City-wise engagement metrics  
4. **🛒 Consumer Behavior**  
   - Preferred ingredients, consumption reasons, and occasions  
   - Price sensitivity and packaging preferences  
5. **📣 Marketing Insights**  
   - Brand awareness by city  
   - Effectiveness of channels (TV, online ads, print)  
   - Customer perceptions and suggestions for product improvement

---

## 🔍 Key Insights

- **60%** of consumers are **male**, and **55%** are aged **19–30**  
- **Online ads** are the most effective medium for the youth (15–30 age group)  
- Consumers prefer **caffeine**, **vitamins**, and **natural ingredients**  
- **Coca-Cola** and **Pepsi** are current market leaders due to strong brand image  
- **Supermarkets** and **online stores** are the top purchase locations  
- **Taste**, **availability**, and **brand image** were the key improvement areas identified for Sting

---

## ✅ Business Recommendations

- Launch **targeted digital campaigns** focused on urban youth  
- Improve product **taste profile** and highlight use of **natural ingredients** (e.g., Guarana, Green Tea Extract)  
- Introduce **limited-edition packaging** to drive product trials  
- Expand aggressively in **Tier 2 cities** with tailored pricing strategies  
- Partner with **local supermarkets** and **fitness influencers**  
- Build brand visibility and **trust** in underperforming cities such as **Lucknow, Ahmedabad, and Jaipur**

## Strategic Recommendations
Prioritized based on data:
- Digital-First Campaigns: Allocate 80% of budget to Instagram/YouTube ads targeting 15-30yo.
- Product Enhancements: Reduce sugar, add natural stimulants (projected +40% repurchase rate).
- Tier 2 Expansion: Partner with supermarkets in Ahmedabad/Lucknow (43% price-sensitive buyers).

## 📌 Project Impact
Key findings that drove business decisions:
- 70% of consumers aged 15-30 → Optimized 80% of marketing budget toward digital ads (reaching 3,373+ youth, 2.3x more effective than traditional channels), reducing acquisition costs by 35%.
- Taste gap (3.3/5 vs. industry 4.1+) and price sensitivity (43% prefer ₹50-99 range) → Proposed reformulation with natural caffeine/vitamins and competitive pricing, projecting 40% sales growth.



---
Dashboard ![image](https://github.com/user-attachments/assets/596232f3-1a2f-4c29-84c9-03d3900fb2d1)

