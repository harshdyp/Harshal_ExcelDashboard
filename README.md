# Pizza Delivery Performance Analysis

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-0A66C2?style=for-the-badge&logo=googlesheets&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-2EA44F?style=for-the-badge)

An end-to-end operational analytics project built in Microsoft Excel to evaluate pizza delivery efficiency, delay rates, restaurant turnaround times, seasonal trends, and customer payment behavior across 2024–2026.

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Dashboard Preview](#dashboard-preview)
- [Analytical Workflow](#analytical-workflow)
- [Key Findings](#key-findings)
- [Dataset & Feature Engineering](#dataset--feature-engineering)
- [Business Recommendations](#business-recommendations)
- [Repository Structure](#repository-structure)
- [How to Use](#how-to-use)

---

## Executive Summary

Delivery speed and on-time reliability directly drive customer retention in food delivery. This dashboard consolidates order-level delivery records across major U.S. cities into an interactive single-page view, enabling stakeholders to isolate bottlenecks by **Order Time (2024–2026)** and **Pizza Size (Small, Medium, Large, XL)**.

### Performance Snapshot *(Filter: Medium Pizza | All Periods)*

| Metric | Value | Operational Context |
| :--- | :---: | :--- |
| **Total Orders** | `429` | Total order volume under active filter |
| **Delayed Orders** | `210` | **49.0%** of deliveries exceeded expected time |
| **Average Delivery Time** | `28 min` | Mean end-to-end fulfillment duration |
| **Average Distance** | `4 km` | Mean distance from restaurant to customer |

---

## Dashboard Preview

<p align="center">
  <img src="assets/dashboard_preview.png" alt="Pizza Delivery Performance Dashboard" width="100%">
</p>

---

## Analytical Workflow

```mermaid
flowchart LR
    A["1. Data Ingestion<br/>Raw Order & Delivery Logs"] --> B["2. Data Preparation<br/>Cleaning & Feature Engineering"]
    B --> C["3. Aggregation<br/>Pivot Tables & KPI Measures"]
    C --> D["4. Dashboard Design<br/>PivotCharts, Timeline & Slicers"]
    D --> E["5. Decision Support<br/>Insights & Recommendations"]
