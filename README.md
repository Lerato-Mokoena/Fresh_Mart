# 🛒 FreshMart Supermarkets – Business Analysis

## 📌 1. Project Overview

FreshMart Supermarkets is a business analysis project focused on investigating declining transaction values across a fictional grocery retail chain operating 42 stores across three South African provinces: Gauteng, Western Cape and KwaZulu-Natal.

The business has experienced an increase in customer footfall of approximately 6% year-on-year, while overall revenue has remained relatively flat or declined slightly. This raises an important business question: **Why are customers spending less per visit despite more people shopping at FreshMart?**

The analysis focuses on understanding changes in customer shopping behaviour, average basket values, transaction volumes and store performance. By examining transaction, store and stockout data, the objective is to identify potential factors contributing to smaller shopping baskets and provide data-driven recommendations to support better business decisions.

## 🎯 2. Business Objectives

The main objectives of the analysis are to:

- Investigate changes in average basket value and the number of items purchased per transaction.
- Analyse transaction volumes and revenue trends throughout 2025.
- Identify stores and regions experiencing changes in basket value.
- Compare customer shopping behaviour between loyalty members and non-loyalty customers.
- Investigate the potential impact of nearby competitors on customer spending.
- Evaluate whether product stockouts are associated with smaller shopping baskets.
- Identify possible root causes behind declining transaction values.
- Develop practical, data-driven recommendations to improve retail performance.

## 📊 3. Dataset Description

The analysis uses a representative extract of FreshMart's 2025 calendar-year data, consisting of three related datasets.

### 3.1 Transactions Dataset
Contains approximately 64,000 till transactions.

Key fields include:
- Transaction ID
- Store ID
- Transaction date
- Day of the week
- Customer ID
- Loyalty membership status
- Number of items purchased
- Basket value (ZAR)
- Payment method

### 3.2 Stores Dataset
Contains information about all 42 FreshMart stores.

Key fields include:
- Store ID
- Store name
- Province
- Store format (Large, Medium and Express)
- Floor area
- Store opening year
- Regional manager
- Nearby competitor information
- Competitor opening date

### 3.3 Stockouts Dataset
Contains records of product availability issues across stores.

Key fields include:
- Stockout ID
- Store ID
- Stockout date
- Affected product category
- Stockout duration in hours
- Operational notes

The datasets are linked through the `store_id` field, allowing transaction activity to be analysed alongside store information and operational events.

## 🔍 4. Key Analysis Areas

The investigation focuses on the following business areas:

**Sales and Transaction Trends**
- Monthly transaction volumes.
- Average basket value.
- Revenue patterns throughout 2025.
- Changes in transaction performance over time.

**Basket Size Analysis**
- Average number of items per transaction.
- Average basket value in ZAR.
- Distribution of small and large shopping baskets.
- Changes in customer spending patterns.

**Store Performance Analysis**
- Comparison of performance across store formats.
- Identification of stores with declining basket values.
- Evaluation of differences in store performance.

**Regional Analysis**
- Comparison across Gauteng, Western Cape and KwaZulu-Natal.
- Identification of regional shopping patterns.
- Assessment of differences in transaction performance.

**Customer Behaviour Analysis**
- Comparison between loyalty members and non-loyalty customers.
- Analysis of shopping patterns across different customer groups.
- Investigation of changes in customer spending behaviour.

**Competitor Analysis**
- Investigation of stores with nearby discount competitors.
- Comparison of stores with and without nearby competitors.
- Assessment of transaction trends before and after competitor openings.

**Stockout Analysis**
- Investigation of product availability issues.
- Analysis of stockout durations.
- Assessment of the relationship between stockouts and basket values.

## 🔄 5. Analysis Process

The analysis follows a structured business analysis approach:

1. **Business Problem Definition** – Understanding the business concern and translating it into measurable analytical questions.

2. **Data Preparation** – Inspecting, organising and preparing the datasets for analysis while identifying missing values, inconsistencies and potential data-quality issues.

3. **Data Exploration** – Examining transaction volumes, basket values, revenue trends and customer shopping patterns.

4. **Data Analysis** – Applying SQL queries, calculations and analytical techniques to investigate business performance.

5. **Data Segmentation** – Comparing results across provinces, store formats, loyalty status, shopping periods and individual stores.

6. **Business Insights** – Identifying patterns, investigating potential root causes and interpreting findings in relation to the business problem.

7. **Recommendations** – Developing practical recommendations supported by the analysis, together with measurable success indicators.

## 🛠️ 6. Tools and Technologies

The following tools are used throughout the analysis and presentation process:

- **Microsoft Excel** – Data organisation, preparation, calculations and preliminary analysis.
- **Databricks** – Data processing, SQL querying and analytical exploration.
- **Power BI** – Developing interactive dashboards and presenting business insights through visualisations.
- **Looker Studio (Data Studio)** – Creating interactive reports and visualising analytical findings.
- **Canva** – Designing visual elements and supporting presentation materials.
- **Figma** – Creating design layouts, visual concepts and dashboard design elements.
- **Microsoft PowerPoint** – Preparing the business analysis presentation and communicating findings.

## 📈 7. Expected Business Outcomes

The analysis aims to provide FreshMart management with a better understanding of:

- Whether average basket values are declining.
- Which stores and regions are experiencing the greatest changes.
- How customer shopping behaviour differs across loyalty groups.
- Whether nearby competitors may be influencing customer spending.
- Whether product availability issues are associated with smaller baskets.
- Which business areas require further investigation or improvement.

The findings will support recommendations focused on improving basket values, strengthening customer shopping experiences and supporting overall retail performance.

## 📋 8. Deliverables

The assignment focuses on three main deliverables:

- **Business Analysis Report** – Documenting the business problem, analytical approach, findings, insights and recommendations.
- **Presentation Deck** – Communicating the key findings and proposed business actions through a professional presentation.
- **Supporting Analysis** – Providing the working files, queries, dashboards and analytical outputs used throughout the investigation.

## 🎯 9. Project Summary

The FreshMart Supermarkets business analysis focuses on investigating the factors that may contribute to declining customer transaction values despite an increase in store footfall.

Through data preparation, SQL querying, exploratory analysis, segmentation and visualisation, the investigation examines different aspects of retail performance, including customer behaviour, store performance, competition and product availability.

The ultimate goal is to transform business data into meaningful insights and actionable recommendations that can help FreshMart understand its performance challenges and make informed business decisions.

---

**Industry:** Retail & Supermarkets

**Analysis Period:** 01 January 2025 – 31 December 2025

**Dataset:** Transactions, Stores and Stockouts

**Focus Area:** Business Analysis, Data Analytics and Data-Driven Decision-Making
