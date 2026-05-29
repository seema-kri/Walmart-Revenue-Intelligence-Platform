# Walmart Revenue Intelligence Platform

> Walmart leadership lacked a unified view of revenue drivers across regions, product categories, and customer segments.
> This project builds a **production-grade Business Intelligence platform** that transforms **550K+ raw retail transactions** into **executive-level insights, strategic recommendations, and revenue growth opportunities**.

---

# 🎯 Business Impact Snapshot

* Identified a **$59M regional revenue gap** enabling targeted expansion strategies
* Discovered a **$367M untapped B2B opportunity** for enterprise customer growth
* Recommended category reallocation from Clothing → Books with projected **3–5% revenue uplift**
* Built a scalable analytics pipeline processing **$764M revenue across 4 years**

---

# Dashboard Preview

| Executive Summary                                     | Product & Store                                      | Customer & Employee                                          |
| ----------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ |
| ![Executive Summary](images/Excecutive%20Summary.png) | ![Product & Store](images/Product%20%26%20Store.png) | ![Customer & Employee](images/Customer%20%26%20Employee.png) |

---

# Business Problem

Retail executives need clear answers to critical business questions:

* Which regions are underperforming?
* Where is revenue stagnating?
* Which categories drive sustainable growth?
* What opportunities can unlock new revenue streams?

Raw transactional data alone cannot answer these questions.

This project solves that problem by building an **end-to-end BI system** that converts raw sales data into **actionable business intelligence and decision-ready dashboards**.

**Project Scope:**
550K+ Transactions · $764M Revenue · 4 Years · 5 Categories · 4 Regions · 93 Employees

---

# Pipeline Architecture

Raw CSV → Python (Pandas) → PostgreSQL (Star Schema) → SQL Analytics → Power BI Dashboard

---

# What I Built

## 1. Data Engineering

* Cleaned and processed **550K+ retail transactions** across multiple datasets
* Handled missing values, duplicates, and inconsistent formats
* Improved overall data quality for accurate downstream analytics

## 2. Data Warehouse

* Designed a scalable **star schema architecture**
* Built **1 fact table + 4 dimension tables**
* Optimized analytical querying and reporting performance

## 3. SQL Analytics

Developed **15+ business-driven SQL analyses** using:

* CTEs
* Window functions (`LAG`, `RANK`, `DENSE_RANK`)
* YoY and MoM growth analysis
* Rolling revenue trend analysis

## 4. Executive Dashboard

Built a **3-page interactive Power BI dashboard** featuring:

* Revenue trend analysis
* Regional and category performance
* Customer and employee insights
* 20+ DAX measures and KPIs

Designed specifically for executive decision-making and operational monitoring.

---

# Key Insights → Business Actions

## Revenue Stagnation

Monthly revenue remained flat between **$14M–$17M** over 4 years.

### Action

Prioritize investment in high-growth regions and product categories.

### Impact

Potential **+$8M–$12M annual revenue uplift**.

---

## $59M Regional Revenue Gap

Central Region: **$221M**
West Region: **$162M**

### Action

Replicate high-performing regional strategies across underperforming markets.

### Impact

Opportunity to recover **$50M+ revenue gap**.

---

## Category Performance Shift

* Books: **+3.6% YoY Growth**
* Clothing: **–1.3% YoY Decline**

### Action

Reallocate budget toward high-growth product categories.

### Impact

Estimated **3–5% revenue growth improvement**.

---

## Untapped B2B Opportunity

* Consumer Revenue: **$519M**
* Corporate Revenue: **$153M**

### Action

Launch dedicated B2B acquisition and retention strategies.

### Impact

Potential **$300M+ enterprise expansion opportunity**.

---

## Employee Performance Gap

Top-performing employees generated **2.25× higher output** than average performers.

### Action

Implement incentive programs and performance optimization initiatives.

### Impact

Improved workforce productivity and revenue contribution.

---

# Business Recommendations

* Expand successful regional strategies
* Increase investment in high-growth categories
* Build a dedicated B2B sales channel
* Optimize workforce performance through incentives and training

---

# Project Structure

```bash
walmart-revenue-intelligence-platform/
├── data/                # Source data & schema files
├── images/              # Dashboard screenshots
├── notebooks/           # Data cleaning, ETL, EDA
├── sql/                 # Business analysis queries
├── dashboard.pbix       # Power BI dashboard
├── dashboard_pdf.pdf    # Dashboard export
├── requirements.txt     # Dependencies
└── README.md
```

# Tech Stack

* Python (Pandas)
* PostgreSQL
* SQL
* Power BI
* DAX

---

# Performance & Scalability

* Optimized star schema for analytical workloads
* Efficiently processes **550K+ rows**
* Modular architecture designed for scalability

---

# Future Enhancements

* Revenue forecasting models
* Customer segmentation (RFM analysis)
* Real-time data pipelines
* Power BI Service deployment

