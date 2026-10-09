# PharmaGuard — Data Dictionary

## Project Overview

PharmaGuard is a Power BI analytics solution for pharmaceutical cold-chain compliance, shipment risk, shelf-life monitoring, medicine wastage, incidents, and logistics analysis.

**Analysis Period:** 2023–2025

## Data Model

The project uses multiple related datasets to analyze pharmaceutical shipments and cold-chain operations.

| Table | Purpose |
|---|---|
| `Shipments` | Shipment-level information and delivery status |
| `Sensor_Readings` | Temperature readings and cold-chain excursions |
| `Products` | Medicine and product details |
| `Incidents` | Operational incidents and severity |
| `Routes` | Route and transportation information |
| `Weather` | Weather-related conditions |
| `Warehouses` | Warehouse information |
| `Carriers` | Carrier information |
| `Dim_Date` | Date dimension for time-based analysis |

## Key Analytical Areas

- **Cold-Chain Compliance:** Monitor temperature excursions and deviations.
- **Shelf-Life & Wastage:** Identify expired and at-risk shipments.
- **Logistics:** Analyze shipment delays and delivery performance.
- **Incident Analysis:** Examine incident counts and severity.
- **Warehouse & Route Analysis:** Compare operational risks across locations and routes.

## Data Preparation

Power Query was used to clean and validate data before analysis. The Power BI data model uses relationships between relevant tables, and DAX measures support KPI calculations and interactive reporting.

## Notes

This document describes the intended role of each table at a high level. Refer to the actual dataset and Power BI model for exact column names, data types, relationship details, and business rules.
