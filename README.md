# AI-Powered SaaS Analytics Dashboard

## Overview

This project delivers an end-to-end analytics system for SaaS business data, combining data engineering, interactive dashboards, and AI-driven insights. Multiple SaaS datasets are integrated, cleaned, and analyzed to uncover trends, detect anomalies, and generate actionable business insights. A Large Language Model (LLM) layer enables natural language querying of metrics, enhancing decision-making and interpretability.

---

## Problem Statement

SaaS companies generate large volumes of time-series data related to subscriptions, revenue, feature usage, and support activity. Visualizing this data alone is insufficient for actionable insights. This project integrates relational data, interactive dashboards, and AI-powered summaries to provide both visual and conversational insights for business performance evaluation.

---

## Objectives

- Clean, validate, and integrate multiple SaaS datasets into a unified analytics base table
- Compute key performance indicators (KPIs) across subscriptions, usage, support, and churn
- Build interactive dashboards to visualize trends and metrics
- Integrate AI (Hugging Face LLM) to generate automated, context-aware business insights
- Enable natural language queries to explore SaaS metrics efficiently

---

## Data Sources

The project uses multiple related CSV files representing SaaS operations:

- `accounts.csv` – Customer metadata
- `subscriptions.csv` – Subscription and revenue details
- `feature_usage.csv` – Product feature usage per account
- `support_tickets.csv` – Customer support interactions
- `churn_events.csv` – Churn and retention events

All datasets are cleaned, validated, and merged into:

- `analytics_base.csv` – Unified fact table for KPI computation, dashboards, and AI integration

---

## Key Performance Indicators (KPIs)

- Monthly Recurring Revenue (MRR) and growth
- Churn rate and retention trends
- Feature adoption and usage metrics
- Support ticket volume and resolution efficiency
- Customer lifetime value (CLV) estimation

---
## Dashboard Development
Built an interactive Power BI dashboard visualizing key SaaS KPIs including revenue trends, churn patterns, usage metrics, and support activity. Implemented dynamic filtering for enhanced data exploration.
---

## System Workflow

1. Raw datasets are explored, cleaned, and validated to ensure consistency and relational integrity
2. Multiple tables are joined into an analytics base table for KPI computation
3. KPIs are calculated and structured for visualization
4. Interactive dashboards (Tableau/Power BI) display trends, patterns, and anomalies
5. AI integration generates summaries and answers natural language queries about SaaS performance metrics

---

## Technologies Used

- **Python**: Data cleaning, KPI computation, AI integration
- **Pandas & NumPy**: Data manipulation and aggregation
- **Tableau / Power BI**: Interactive dashboards
- **Hugging Face LLM APIs**: AI-generated summaries and insights
- **Git & GitHub**: Version control and project management

---

## Expected Outcomes

- Interactive dashboards highlighting revenue, churn, growth, and usage patterns
- AI-generated summaries providing actionable insights
- Natural language interface for querying SaaS metrics
- A professional, end-to-end analytics framework applicable to real-world SaaS environments

---

## Applications

- SaaS business performance monitoring and reporting
- Product adoption and growth analytics
- Customer support and retention analysis
- AI-assisted business intelligence and decision support

---

## Team

- Keshav Kumar
- Sushrut Kane

---
