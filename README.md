# 🚀 Crowd Funding Analytics

An end-to-end Data Analytics portfolio project analyzing Kickstarter Crowd Funding data to identify success drivers, campaign behavior, and performance trends using industry-standard analytical workflows.

This project demonstrates complete execution of the analytics lifecycle — from raw data preparation to business KPI analysis and interactive dashboard development across multiple tools.

---

## 📌 Project Summary

Crowdfunding platforms host thousands of campaigns competing for funding across categories and regions.  
Understanding what makes a campaign successful is essential for creators, investors, and platform decision-makers.

This project analyzes crowdfunding campaign data to answer real business questions related to:

- Campaign success patterns
- Funding performance
- Market trends
- Backer engagement behavior
- Time-based growth analysis

All KPIs were independently implemented and validated across **Excel, SQL, Power BI, and Tableau** to ensure analytical accuracy.

---

## 🎯 Business Objectives

- Measure overall project success vs failure
- Identify high-performing categories and regions
- Analyze funding engagement through backers and pledged amounts
- Understand campaign trends over time
- Evaluate impact of funding goals on success probability
- Discover characteristics of top-performing campaigns

---

## 💼 Business Problems & KPI Mapping

| Business Problem | KPI Used | Business Value |
|------------------|----------|----------------|
| Why do some projects succeed while others fail? | Total Projects by Outcome | Evaluates overall platform performance |
| Which categories generate higher success rates? | Success % by Category | Helps prioritize profitable segments |
| Which regions drive crowdfunding activity? | Projects by Location | Identifies geographic demand |
| How has campaign activity evolved over time? | Projects by Year / Quarter / Month | Detects growth & seasonal patterns |
| What defines financially successful campaigns? | Amount Raised & Backer Count | Measures engagement strength |
| Do funding goals influence success probability? | Success % by Goal Range | Suggests optimal funding targets |
| Which campaigns perform exceptionally well? | Top Successful Projects | Establishes performance benchmarks |
| What campaign duration works best? | Avg Duration of Successful Projects | Guides campaign planning strategy |

---

## 🗂 Dataset Overview

The analysis is based on Kickstarter crowdfunding datasets organized using dimensional modeling:

- **Projects** — Fact Table (campaign-level data)
- **Category** — Campaign classification
- **Location** — Geographic information
- **Creator** — Campaign owner details

Large analytical files are managed using **Git Large File Storage (Git LFS)**.

---

## 🧱 Data Modeling & Architecture

A **Star Schema** model was implemented:

- Central Fact Table: `Projects`
- Dimension Tables: `Category`, `Creator`, `Location`
- Custom Calendar Table created for time intelligence
- Bridge table introduced to resolve many-to-many date relationships

This structure enables scalable KPI calculations and accurate time-based analysis.

---

## 🔄 Data Preparation & Transformations

- Conversion of Epoch timestamps to natural date format
- Data type standardization using Power Query
- Derived columns and calculated measures
- Currency normalization (Goal → USD)
- Time intelligence column creation
- Filter context optimization for accurate KPI evaluation

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| 📊 Microsoft Excel | Exploratory analysis & dashboard |
| 🧮 MySQL | KPI validation through SQL queries |
| 📈 Power BI | Data modeling & interactive dashboards |
| 📉 Tableau | Visual analytics dashboards |
| 🔧 GitHub | Version control & project publishing |
| 📦 Git LFS | Large analytics file management |

---

## 📊 KPIs Implemented

- Total Projects by Outcome
- Projects by Category & Location
- Time-based Project Creation Trends
- Amount Raised Analysis
- Backer Participation Analysis
- Average Duration of Successful Campaigns
- Top Performing Projects
- Overall Success Rate
- Success Rate by Category
- Success Rate by Goal Range

---

## 📷 Dashboard Previews
*(Dashboard screenshots will be added here for quick visualization)*

