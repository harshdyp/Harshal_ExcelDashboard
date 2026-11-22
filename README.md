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

## Analytical Workflow

```mermaid
flowchart LR
    A["1. Data Ingestion<br/>Raw Order & Delivery Logs"] --> B["2. Feature Engineering<br/>Delays, Efficiency & Flags"]
    B --> C["3. Data Modeling<br/>Linked Pivot Tables & KPIs"]
    C --> D["4. Dashboard Architecture<br/>Charts, Timeline & Slicers"]
    D --> E["5. Decision Support<br/>Benchmarks & Strategy"]
