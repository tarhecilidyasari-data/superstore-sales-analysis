# Superstore Sales & Performance Analysis (2015–2018)

## Business Overview
This project provides an end-to-end sales analytics dashboard built with *Excel* and *Power Query*. It processes multi-year transactional data from a global Superstore retailer to extract actionable business insights regarding revenue, regional performance, and product categories.

---

## Data Pipeline & Workbook Architecture
The Excel workbook is structured systematically to ensure data integrity, clean transformation, and smooth reporting:

1. *Raw*: Preserved original transactional dataset (2015–2018) without manual edits to maintain data integrity.
2. *Processed (Excel)*: Transformed dataset using Excel formulas and feature engineering:
   - *Date Extraction*: Engineered Year and Month columns from standardized order/shipping dates.
   - *Custom Categorization*: Created dynamic transaction tags (Value Category, Diskon Tiers).
   - *Data Mapping*: Implemented VLOOKUP logic to map regional states (State2).
3. *Pivot*: Aggregated statistical data used as the underlying calculation engine for visualization.
4. *Report*: Structured multi-year sales summary in clear tabular format for business review.
5. *Dashboard*: Interactive visual canvas equipped with dynamic Slicers and KPI Cards.
6. *Power Query*:
   - Handled DD/MM/YYYY date formatting via UK Locale settings.
   - Imputed missing Postal Code values to "Unknown".
   - Engineered custom features: Shipping Duration (Ship Date - Order Date).
8. *Scribble*: Dedicated scratchpad for formula drafting, logic testing, and preliminary data validation.

---

## Key Business Insights
- Top Category: *Technology* leads total sales generated (*$827,455.87*), driven by high demand in office tech hardware.
- Top Performing Region: *West Region* outperforms other zones with *$710,219.68* in total revenue.
- Customer Segment: *Consumer* segment accounts for the largest proportion of sales across all regions.

---

## Skills & Tools Applied
- *Data Transformation*: Power Query, M Code logic, Locale Settings, Type Casting.
- *Excel Modeling*: Pivot Tables, Slicers, Report Connections, KPI Cards, Advanced Charting.
- *Shortcuts & Efficiency*: Keyboard-driven workflow for navigation and formatting.

