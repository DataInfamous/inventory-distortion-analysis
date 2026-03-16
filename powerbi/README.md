# Inventory Distortion Analysis (Power BI)

## Overview

This project analyzes **inventory distortion caused by SSCC receiving errors in warehouse operations**. The goal of the dashboard is to identify the **operational drivers behind inventory discrepancies** and quantify their **financial impact**.

Using **Power BI**, the dashboard visualizes total distortion, error types, and operational relationships between **unreceived units** and **financial loss**.

---

## Key Questions

The dashboard helps answer several operational questions:

- **What is the total financial impact of inventory distortion?**
- **Which error types cause the largest distortions?**
- **Do different site types experience different levels of distortion?**
- **How does operational failure scale with financial impact?**

---

## Dashboard Features

### KPI Summary
Displays the **total inventory distortion value** to provide a high-level view of financial impact.

### Error Type Breakdown
A categorical chart showing which **SSCC receiving errors contribute most to distortion**.

### Site Type Comparison
Compares distortion levels between **standard** and **high-compliance** sites.

### Operational Impact Analysis
A scatter plot visualizing the relationship between:

- **Unreceived units**
- **Financial distortion**
- **Unit cost impact**

### Interactive Filtering
Users can filter results by **site type** to explore how operational environments influence distortion patterns.

---

## Tools Used

- **Power BI** – Data visualization and dashboard design  
- **Data Modeling** – Aggregations and relationships within Power BI  
- **Operational Analytics** – Warehouse process analysis  

---

## Dataset

The dataset represents simulated warehouse receiving data and includes variables such as:

- `error_type`
- `site_type`
- `unreceived_units`
- `unit_cost`
- `value_distortion`
- `correction_minutes_est`

These variables allow analysis of both **financial** and **operational impacts** of receiving errors.
