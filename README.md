# 📊 Data Analyst Job Market Dashboard

> An interactive Power BI dashboard that transforms thousands of data-job postings into actionable insights on hiring demand, salaries, and market trends.

<p align="left">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiMjE2Y2U4YTctNDYyMC00ZWMxLThiOTAtZGE4YWYzZGFiZDM5IiwidCI6ImQxZjE0MzQ4LWYxYjUtNGEwOS1hYzk5LTdlYmYyMTNjYmM4MSIsImMiOjEwfQ%3D%3D">
    <img src="https://img.shields.io/badge/🔴_Live_Dashboard-View_on_Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Live Power BI Dashboard" />
  </a>
</p>

**▶️ [Explore the live, interactive dashboard here](https://app.powerbi.com/view?r=eyJrIjoiMjE2Y2U4YTctNDYyMC00ZWMxLThiOTAtZGE4YWYzZGFiZDM5IiwidCI6ImQxZjE0MzQ4LWYxYjUtNGEwOS1hYzk5LTdlYmYyMTNjYmM4MSIsImMiOjEwfQ%3D%3D)** — no download required, filter and drill through directly in your browser.

![Executive Overview](images/Screenshot%202026-07-08%20170737.png)

---

## Why I Built This

Job boards hold an enormous amount of valuable information, but it's hard to spot trends by scrolling through thousands of individual listings.

I built this dashboard to answer the questions aspiring data professionals, recruiters, and hiring managers actually ask:

* Which data roles are hiring the most?
* What salaries can candidates expect, by role?
* How does company rating vary across postings?
* Where are these jobs located, and how common is remote work?
* Do employers typically require a degree or offer health insurance?
* Which job platforms attract the most postings?

Instead of manually digging through listings, users can answer these questions in seconds through interactive filtering and drill-through navigation.

---

## Dashboard Highlights

### Executive Overview

The landing page gives a high-level snapshot of the job market, including:

* 📌 Total job postings
* ⭐ Average company rating
* 💰 Median yearly salary
* ⏱ Median hourly salary

Alongside these KPIs, users can explore hiring trends over time, the volume of postings by job title, and a filterable list of job listings.

### Job Title Drill-Through

![Job Title Details](images/Screenshot%202026-07-08%20170848.png)

Selecting any job title opens a dedicated details page with deeper, role-specific insights, including:

* Median annual and hourly salary for that role
* Remote work availability
* Degree and health insurance requirements
* Geographic distribution of postings
* Top hiring platforms
* Employment type breakdown

This lets users move from a broad market view to role-specific insights with a single click.

---

## Key Insights From the Data

Beyond the visuals, the dashboard surfaces findings that are genuinely useful to job seekers, recruiters, and hiring managers:

* **Data Engineers are the most in-demand and highest-paid core role**, with a median yearly salary of **$126K**, ahead of Data Scientists ($125K) and Data Analysts ($90K). Seniority pays off: Senior Data Scientists top out at **$156K** and Senior Data Engineers at **$147K** median yearly.
* **Hiring volume is heavily concentrated in three roles** — Data Engineer, Data Analyst, and Data Scientist together account for the large majority of postings, while senior-level titles make up a much smaller share of the market.
* **Monthly posting volume is volatile, not steadily growing** — postings swung from ~47K in one month to a low of ~12K later in the year before recovering, a signal that hiring demand for data roles is seasonal/cyclical rather than flat.
* **Remote work is the exception, not the norm**: only **13.15%** of postings explicitly offer work-from-home, meaning most data roles still expect on-site or hybrid presence.
* **Health insurance is rarely advertised up front**: just **12.83%** of postings mention it, which is useful context for candidates comparing total compensation, not just salary.
* **A degree isn't always a hard requirement**: **32.52%** of postings don't mention a degree requirement at all, an encouraging signal for self-taught and bootcamp-trained candidates.
* **Hiring is extremely concentrated on one platform**: LinkedIn alone accounts for far more postings than the next several platforms (BeBee, Indeed, ZipRecruiter) combined, making it the clear priority channel for both job seekers and recruiters sourcing candidates.
* **Demand is global but clustered**: the geographic breakdown shows postings concentrated in North America and Europe, with a long tail spread across other regions, useful for candidates weighing relocation or remote opportunities.

## Why This Matters (Business Value)

This isn't just a set of charts — it's a decision-support tool:

* **For job seekers:** benchmark expected pay by role and seniority before negotiating, and set realistic expectations around remote work, degree requirements, and benefits.
* **For recruiters and hiring managers:** see where hiring is most competitive, which platforms actually reach candidates, and how their own postings compare to market medians.
* **For career switchers/bootcamp grads:** the degree-requirement breakdown quantifies how open the market really is to non-traditional backgrounds.
* **For workforce/market analysts:** the trend chart turns scattered job-board noise into a clear read on whether data-role hiring is accelerating or cooling month over month.

The underlying value is turning thousands of unstructured job listings into a handful of numbers that someone can act on in under a minute, instead of scrolling job boards for hours.

---

## Technologies Used

| Tool | Purpose |
| --- | --- |
| **Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPIs, calculated columns, and measures |
| **Data Modeling** | Relationships and optimized reporting |

---

## Skills Demonstrated

* Data Cleaning & Transformation
* Data Modeling
* DAX Calculations
* Interactive Report Design
* KPI Development
* Drill-Through Navigation
* Cross-Filtering
* Geospatial Visualization
* Business Intelligence Storytelling

---

## Repository Structure

```text
Power BI project/
│
├── 01_power_bi_dashboard.pbix
├── README.md
└── images/
    ├── Screenshot 2026-07-08 170737.png
    └── Screenshot 2026-07-08 170848.png
```

---

## Getting Started

**Option 1 — View instantly (no install needed):**
Open the **[live interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjE2Y2U4YTctNDYyMC00ZWMxLThiOTAtZGE4YWYzZGFiZDM5IiwidCI6ImQxZjE0MzQ4LWYxYjUtNGEwOS1hYzk5LTdlYmYyMTNjYmM4MSIsImMiOjEwfQ%3D%3D)** directly in your browser and start filtering right away.

**Option 2 — Open in Power BI Desktop:**
1. Clone or download this repository.
2. Open `01_power_bi_dashboard.pbix` using Microsoft Power BI Desktop.
3. Refresh the dataset if necessary.
4. Explore the dashboard using slicers, filters, and drill-through pages.

---

## Author

**Duncan** ([@DunD514](https://github.com/DunD514))

If you found this project useful, consider giving the repository a ⭐.
