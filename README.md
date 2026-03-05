# 📊 Global B2B Sales Pipeline & Deals Analytics Dashboard

## Overview

The **Global B2B Sales Pipeline & Deals Analytics Dashboard** was developed as a comprehensive business intelligence solution designed to transform complex sales pipeline data into meaningful, actionable insights across deal performance, customer segments, sales engagement and revenue forecasting. In many enterprise B2B organisations, large volumes of CRM data remain scattered across sales management systems, activity tracking platforms and customer databases. This fragmentation often prevents leadership teams from obtaining a clear, unified view of pipeline health, deal progression and sales team performance.

This project addresses that challenge by developing an integrated analytical platform that enables revenue forecasting, pipeline monitoring and sales performance optimisation using **Power BI, DAX and a structured star-schema data modelling approach.**

---

## Business Context

The dashboard provides a consolidated view of global sales performance, transforming thousands of deal and activity records into an interactive reporting environment. The system aggregates more than **€1.02 billion in total pipeline value**, including:

- **€606 million** in open pipeline opportunities  
- **€252 million** in weighted forecast revenue  
- **€240 million** in closed-won deals  

All of these insights are presented within a single analytical interface.

The dashboard allows stakeholders to:

- Monitor pipeline health in real time
- Track deal progression across pipeline stages
- Evaluate the impact of sales engagement activities on deal outcomes
- Analyse industry and regional contributions to pipeline performance

By presenting pipeline value trends, win rates, industry contributions and regional insights, the solution enables sales leaders to make informed decisions that improve forecasting accuracy and pipeline conversion efficiency.

---

## Problem Statement

One of the major challenges faced by large B2B organisations is the **lack of visibility into how deals move through the sales pipeline and which factors influence successful deal closure.**

While CRM systems capture transactional data, they often fail to answer important analytical questions such as:

- Where do deals stall within the sales pipeline?
- Which industries generate the highest revenue opportunities?
- How do sales engagement activities affect win rates?
- Which deals are at risk due to inactivity?
- Which sales representatives manage the healthiest pipelines?

This project addresses these gaps by building an **interactive analytical solution capable of answering critical questions around pipeline distribution, deal velocity, sales rep productivity and engagement effectiveness.**

---

## Data Model

The analytical solution is built on a **star-schema data model** designed for scalable and high-performance analytics.

### Fact Tables

**FactDeals**

Contains transactional information about sales opportunities including:

- Deal Value
- Pipeline Stage
- Deal Status
- Win Probability
- Company ID
- Sales Representative ID

**FactActivities**

Captures engagement data including:

- Activity Type
- Activity Duration
- Deal Interactions
- Sales Representative Involvement

### Dimension Tables

**DimCompany**

Provides contextual attributes including:

- Industry
- Company Size
- Geographic Location

**DimSalesRep**

Contains sales representative details such as:

- Representative Name
- Region
- Role
- Seniority

**DimDate**

Enables time intelligence analysis including:

- Monthly trends
- Quarterly performance
- Year-over-year comparisons
![PGD](https://github.com/user-attachments/assets/5cfcaa2c-1f82-4326-9f41-5bf1958f34a6)

---

## Data Preparation

The data preparation phase involved several transformation steps:

- Cleaning inconsistent stage and status labels
- Handling missing values
- Standardising date keys for time intelligence
- Creating calculated columns for pipeline risk analysis
- Deriving **Days Since Last Activity** to identify stalled deals

Several DAX measures were developed to calculate key metrics including:

- Total Pipeline Value
- Open Pipeline Opportunities
- Weighted Revenue Forecast
- Win Rate
- Pipeline Risk Indicators

These measures enable dynamic filtering across **regions, industries, sales representatives and pipeline stages.**

---

## Dashboard Structure

The final analytical solution consists of **three structured dashboard pages**, each designed to support different business perspectives.

---

### 1️⃣ Sales Pipeline Executive Overview

This page provides a high-level snapshot of overall pipeline performance.

Key insights include:

- Total pipeline value
- Open pipeline opportunities
- Weighted forecast revenue
- Closed-won revenue
- Overall win rate

Additional visualisations show:

- Monthly pipeline trends
- Industry contribution to pipeline value
- Geographic distribution of opportunities
- Stage-level pipeline breakdown
- Pipeline inactivity risk indicators

This page acts as a **strategic command centre for sales executives.**


![PGA](https://github.com/user-attachments/assets/d5cd7075-0b0e-4002-9859-93e393bfeae4)

---

### 2️⃣ Pipeline Flow & Deal Bottlenecks

This page focuses on analysing how deals progress through the sales pipeline.

Key analyses include:

- Pipeline value by stage
- Weighted forecast by sales representative
- Deal conversion performance across stages
- Stage-level inactivity analysis
- Deal volume distribution across stages

The analysis reveals where deals accumulate and highlights potential **pipeline bottlenecks that may slow revenue generation.**

---![PGB](https://github.com/user-attachments/assets/165332b5-5c17-483b-a86a-3faa85a69bbb)


### 3️⃣ Sales Representative Performance & Engagement Insights

This page evaluates how individual sales representatives manage their pipelines and interact with customers.

Key insights include:

- Pipeline ownership by sales representative
- Weighted forecast performance
- Win rate comparison across the sales team
- High-risk pipeline exposure
- Average days since last activity

Additional visualisations explore the relationship between **sales engagement activities and deal outcomes**, including:

- Activity distribution (emails, calls, meetings, demos, workshops)
- Activities per deal vs win rate
- Closed-won revenue by company size

This analysis helps identify **top-performing sales representatives and effective engagement behaviours.**


![PGC](https://github.com/user-attachments/assets/2cc58c87-53e4-4ea9-9e41-4e1a61838c68)

---

## Key Insights

Several insights emerged from the analysis:

- **Technology, Financial Services and Retail sectors dominate global pipeline value.**
- **Proposal and Negotiation stages contain the highest concentration of opportunities.**
- Higher levels of **sales engagement correlate with stronger win rates.**
- Several deals show extended inactivity, indicating pipeline risk.
- Sales performance varies significantly across representatives and regions.

---

## Strategic Recommendations

Based on the insights generated, the following recommendations can be made:

- Prioritise high-performing industries to maximise revenue potential
- Increase engagement on mid-stage deals to accelerate pipeline progression
- Implement proactive alerts for deals exceeding inactivity thresholds
- Develop best-practice engagement strategies based on top-performing representatives
- Improve forecasting accuracy by combining stage-level conversion analysis with probability-weighted forecasts

---

## Conclusion

The **Global B2B Sales Pipeline & Deals Analytics Dashboard** demonstrates how structured data modelling, advanced DAX calculations and interactive Power BI visualisations can transform complex CRM data into a powerful business intelligence platform.

By integrating pipeline monitoring, engagement analytics and sales performance insights into a unified reporting system, organisations can move beyond reactive reporting and adopt a **proactive, data-driven approach to sales management.**

This dashboard ultimately provides organisations with the visibility needed to improve forecasting accuracy, optimise pipeline management and drive sustainable revenue growth in competitive B2B markets.

---

