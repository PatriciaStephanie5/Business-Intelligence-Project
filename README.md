
# B2B Lead Prioritization Engine with Clay & Tableau

![Status: Completed](https://img.shields.io/badge/Project_Status-Simulated_/_Educational-brightgreen)

## Project Overview

This project demonstrates an end-to-end **Business Intelligence (BI) pipeline** designed to help sales and marketing teams prioritize outreach efforts. Using **Clay.com** for no-code data enrichment and **Tableau** for interactive visualization, we transform a raw list of company names into a scored, actionable lead list with revenue potential and geographic insights.

**Business Context:**  
A B2B sales team receives hundreds of leads monthly. Without enrichment and scoring, they waste time on low-value accounts. This project automates that qualification process.

---

## 🛠️ Tools & Technologies

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

## 📊 Key Business Insights & Executive Takeaways

### 1. Focus on 12 "Hot" Leads First
- **Finding:** 40% of the enriched leads (12/30) qualified as "Hot" based on revenue >$50M and employee count >500.
- **Business Impact:** These 12 accounts represent an estimated **$9.3B in combined annual revenue**. Prioritizing them maximizes ROI on sales effort.

### 2. Geographic Clustering Enables Territory Planning
- **Finding:** Hot leads are concentrated in **California, New York, and London**.
- **Recommendation:** Align regional sales directors to cover these clusters with targeted, in-person meetings.

### 3. Industry Vertical Alignment
- **Finding:** **Pharmaceuticals** and **Utilities** over-index in both revenue size and employee count among "Hot" leads.
- **Action:** Develop industry-specific pitch decks and case studies for these verticals to shorten sales cycles.

### 4. Technology Stack Signal (Simulated)
- **Finding:** Over 70% of Hot leads show evidence of using **Salesforce CRM**.
- **Partnership Opportunity:** Explore co-marketing campaigns or integration partnerships with Salesforce.

### 5. Data Completeness Drives Actionability
- **Finding:** 85% of Hot leads had a valid **direct email address** for a Director-level or above contact.
- **Result:** Sales team can bypass gatekeepers and initiate high-level conversations immediately.

---

### About the Author

**Timba Patricia Stephanie**
Business Intelligence Enthusiast | Data Storyteller
GitHub: https://GitHub.com/PatriciaStephanie5

> This project was completed as a simulated end-to-end BI workflow. All data is mock data for educational purposes
