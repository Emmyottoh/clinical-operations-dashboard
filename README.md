# 🏥 Clinical & Hospital Operations Executive Insights Report

## 📌 Executive Summary
An end-to-end data audit, data cleansing, and multi-dimensional analysis were conducted across **5,000 unique patient records** to evaluate hospital operational efficiency, bed capacity, patient acuity, and resource allocation.

The primary objective was to eliminate data quality issues, aggregate operational metrics into structured Pivot Table frameworks, and build a dynamic **Executive Dashboard** that drives data-informed decisions for hospital management.


## 🛠️ Phase 1: Data Engineering & Cleansing Lifecycle

### Key Cleansing Interventions:
* **Deduplication & Integrity:** Removed duplicate entries to establish a clean, verified baseline of 5,000 unique patient admissions.
* **Standardization & Text Normalization:** Consolidated redundant categorical labels across patient demographics, admission types, and disease classifications to avoid fragmented reporting.
* **Missing Value Treatment:** Imputed missing values with business logic rules (replacing non-applicable/blank numeric fields with 0 and missing categoricals with "Unknown") to preserve sample size while avoiding bias.
* **Metric Derivation:** Formatted and structured fields for Length of Stay (LOS), ICU Bed Occupancy, and Oxygen Demand to enable precise KPI card and chart aggregation.


## 📊 Phase 2: Pivot Table Mapping & Multi-Dimensional Aggregation

| Analysis Focus | Core Metrics Aggregated | Business Value Delivered |
| :--- | :--- | :--- |
| Demographics & Acuity | Patient Count, Gender, Age Distribution | Identifies primary care demographic profiles |
| Bed Utilization & LOS | Avg Length of Stay (Days), ICU Bed-Days | Highlights capacity bottlenecks by severity grade |
| Intake Volatility | Admissions by Season & Admission Type | Informs dynamic seasonal staffing models |
| Resource Consumption | Oxygen Consumption (Units/Patient) | Pinpoints emergency allocation & inventory needs |


## 💡 Key Strategic Business Insights
1. **High-Acuity Bed Bottlenecks:** Critical patients average **20.0 days per stay** (4x baseline). Combined with Severe intake (~29% of volume), they consume **over 65% of total bed-days**.
2. **Summer Intake Surge:** Summer recorded **2,077 admissions (41.5% of annual intake)**, indicating urgent demand for seasonal surge capacity.
3. **Emergency Resource Allocation:** Emergency admissions consumed nearly **2x more oxygen per capita (~72.2 units/patient)** than standard inpatients (~38.1 units/patient).
