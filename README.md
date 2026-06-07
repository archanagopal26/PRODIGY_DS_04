# PRODIGY_DS_04
TASK 4 IN DATA SCIENCE
# Social Media Sentiment Analysis & Visualization Dashboard

An automated, corporate-grade Excel-based solution designed to analyze and visualize public sentiment patterns across social media data. This dashboard processes raw social listening feeds, groups them into specific sentiment polarities, and aggregates them into macro-level brand equity insights.

The structure and data mapping are modeled after the **Prodigy InfoTech Data Science Track (Task 4)** dataset format.

---

## 📊 Dashboard Architecture

The workbook is systematically organized into two primary tabs, employing a **Slate Gray & Muted Mint** professional color palette that emphasizes clarity and clean data presentation.

### 1. Executive Dashboard (Tab 1)
* **High-Level KPI Summary Cards:** Instant visual tracking for *Total Tweets Analyzed*, *Positive Sentiment Volumes*, *Negative Sentiment Volumes*, and *Muted/Neutral Share*.
* **Dynamic Formula Layer:** Fully automated metric tallies using native Excel functions (`COUNTIF`, `COUNTIFS`, `SUM`) to ensure zero hardcoded summaries.
* **Interactive Data Visualizations:**
  * **Share of Voice (Pie Chart):** Outlines the absolute distribution of general public attitude.
  * **Brand Sentiment Matrix (Stacked Column Chart):** Compares entity-level sentiment side-by-side to pinpoint exactly which brands or products suffer from public relations spikes or technical backlash.

### 2. Social Media Data Feed (Tab 2)
* **Granular Data Log:** Maps unique `Tweet ID`, `Entity / Brand`, `Sentiment Polarity`, and raw `Tweet Content`.
* **Soft-Alert Conditional Highlights:** Utilizes desaturated, professional color mapping across the polarity column for rapid, row-by-row auditing:
  * 🟩 **Muted Green:** Positive consumer feedback / Brand wins.
  * 🟥 **Muted Red:** Negative public outcry / System bugs / Brand complaints.
  * 🟨 **Muted Yellow:** Neutral press releases or corporate news.
  * ⬜ **Soft Gray:** Irrelevant mentions or casual background noise.
visulization.png
