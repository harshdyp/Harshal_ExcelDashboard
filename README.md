# Pizza Delivery Performance & Operational Analytics

An end-to-end operational analytics project built in **Microsoft Excel** to evaluate pizza delivery efficiency, SLA compliance, restaurant turnaround times, seasonal bottlenecks, and customer payment behavior across major U.S. markets (2024–2026).

---

## Business Problem & Objective

In last-mile food delivery, high delay rates directly erode customer retention and increase refund costs. Raw order logs alone make it difficult for operations teams to pinpoint whether delays are driven by specific restaurant chains, seasonal demand spikes, or order complexity.

**Objective:** Transform granular order-level delivery records into an interactive, single-page executive dashboard that enables stakeholders to:
* Monitor core SLA and fulfillment KPIs in real time.
* Benchmark delivery speed across competing restaurant chains.
* Identify seasonal congestion windows and payment channel trends.
* Dynamically slice performance by **Order Time (2024–2026)** and **Pizza Size (Small, Medium, Large, XL)**.

---

## Executive KPI Snapshot

> **Active Filter:** `Pizza Size = Medium` | `Order Time = All Periods (2024–2026)`

| KPI | Value | Operational Interpretation |
| :--- | :---: | :--- |
| **Total Orders** | `429` | Total fulfillment volume under the active filter |
| **Delayed Orders** | `210` | **49.0%** of orders exceeded expected delivery time |
| **Avg. Delivery Duration** | `28 min` | Mean end-to-end fulfillment time |
| **Avg. Distance** | `4 km` | Mean travel distance per delivery |

---

## Key Analytical Findings

### 1. Restaurant Turnaround Benchmarking
Average delivery duration varies by **6.35 minutes** between the fastest and slowest chains—a substantial gap in food delivery SLAs:

| Restaurant | Avg. Delivery Duration (min) | Variance vs. Fastest | Performance Tier |
| :--- | :---: | :---: | :--- |
| **Little Caesars** | 23.80 | Baseline | Top Performer |
| **Domino's** | 25.00 | +1.20 min | Above Average |
| **Marco's Pizza** | 26.87 | +3.07 min | Moderate |
| **Papa John's** | 29.19 | +5.39 min | Below Average |
| **Pizza Hut** | 30.15 | +6.35 min | Needs Optimization |

### 2. Payment Channel Behavior
* **Digital Dominance (79%):** Nearly four out of five orders are paid digitally—led by **Card (29%)**, **Wallet (29%)**, and **UPI (21%)**.
* **Offline Cash Share (20%):** Cash-on-delivery still accounts for one-fifth of order volume, requiring cash-handling protocols for drivers.
* **Loyalty Underutilization (1%):** Proprietary reward currencies (**Domino's Cash at 1%** and **Hut Points at 0%**) see minimal adoption, signaling an untapped retention lever.

### 3. Seasonal & Monthly Delivery Trends
* **Peak Congestion Windows:** Average delivery times spike above **29 minutes** in **May** and during the **November–December** holiday period.
* **Peak Efficiency:** Turnaround times reach their annual low in **July (~25.2 minutes)**, reflecting smoother dispatch flow or lower traffic congestion.

---

## Analytical Workflow

```mermaid
flowchart LR
    A[1. Data Ingestion] --> B[2. Feature Engineering]
    B --> C[3. Pivot Modeling]
    C --> D[4. Interactive Dashboard]
    D --> E[5. Strategic Insights]
