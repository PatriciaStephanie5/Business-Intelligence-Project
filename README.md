
# B2B Lead Prioritization Engine with Clay & Tableau

![Status: Completed](https://img.shields.io/badge/Project_Status-Simulated_/_Educational-brightgreen)
click the link below to view clay automation
(https://app.clay.com/workspaces/1115655/workbooks/wb_0tdj316Yqay3mgiH6xm/tables/t_0tdj316FgFaKY2kwbB6/views/gv_0tdj316Q4Hyr8GGnCNx)

## Project Overview

This project demonstrates an end-to-end **Business Intelligence (BI) pipeline** designed to help sales and marketing teams prioritize outreach efforts. Using **Clay.com** for no-code data enrichment and **Tableau** for interactive visualization, we transform a raw list of company names into a scored, actionable lead list with revenue potential and geographic insights.

**Business Context:**  
A B2B sales team receives hundreds of leads monthly. Without enrichment and scoring, they waste time on low-value accounts. This project automates that qualification process.

---

## Tools & Technologies

| Layer | Technology | Purpose |
|-------|------------|---------|
| **Data Source** | Mock CSV (30 B2B Leads) | Simulated CRM export |
| **Enrichment & Automation** | [Clay.com](https://clay.com) | Company data enrichment, contact discovery, lead scoring |
| **Visualization** | Tableau Desktop | Interactive dashboard for geographic and financial analysis |
| **Version Control** | Git / GitHub | Project documentation and sharing |

---

## Data Pipeline Architecture

┌─────────────────┐     ┌─────────────────────────────────────────┐     ┌─────────────────┐     ┌─────────────────┐
|
leads_raw.csv  │────▶│            CLAY AUTOMATION               │────▶│  Enriched CSV   │────▶│    Tableau      │
│  (30 records)   │     │                                         │     │  (30 records)   │     │   Dashboard     │
│                 │     │ • Domain Cleaning                       │     │                 │     │                 │
│  Columns:       │     │ • Apollo.io Company Enrichment          │     │  + Employee     │     │ • Geographic Map│
│  - Company      │     │   (Revenue, Employees, Industry, City)  │     │  + Revenue      │     │ • Scatter Plot  │
│  - Website      │     │ • Lead Scoring Formula (Hot/Warm/Cold)  │     │  + Industry     │     │ • Priority Table│
│  - Contact      │     │                                         │     │  + Lead Score   │     │                 │
│
└─────────────────┘     └─────────────────────────────────────────┘     └─────────────────┘     └─────────────────┘

---

### About the Author

**Timba Patricia Stephanie**
Business Intelligence Enthusiast | Data Storyteller
GitHub: https://GitHub.com/PatriciaStephanie5

> This project was completed as a simulated end-to-end BI workflow. All data is mock data for educational purposes
