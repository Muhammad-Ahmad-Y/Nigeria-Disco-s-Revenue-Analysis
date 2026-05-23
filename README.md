# Nigeria DisCos & KEDCO Loss & Revenue Recovery Analysis

**Author:** Muhammad Ahmad Yusuf
**Location:** Kano, Nigeria

## Project Overview
This project is a comprehensive data analysis and business intelligence solution evaluating the operational and commercial performance of Nigerian Electricity Distribution Companies (DisCos), with a deep-dive focus on the **Kano Electricity Distribution Company (KEDCO)**. By leveraging 2025 performance data, this analysis investigates energy losses, billing efficiency, revenue collection performance, and Aggregate Technical, Commercial and Collection (ATC&C) losses.

The primary goal is to benchmark nationwide DisCo performance, identify the major drivers of revenue loss across the value chain, and highlight specific operational bottlenecks within the Kano region.

## Dashboards

### 1. National DisCos Overview
![Discos Dashboard](<Insert-Path-To-Discos-Dashboard.png>)
*Provides a macro-level view of all Nigerian DisCos, comparing Billing Efficiency, Collection Efficiency, and ATC&C Losses.*

### 2. KEDCO Specific Performance
![KEDCO Dashboard](<Insert-Path-To-KEDCO-dashboard.png>)
*A localized deep-dive into KEDCO's specific revenue recovery challenges, highlighting the severe disparity between billing capabilities and actual revenue collection.*

## Data Sources & Methodology
* **Datasets:** Energy Billed & Received, Revenue Billed & Collected (Values in Billions of Naira - ₦).
* **Methodology:** * ETL processes performed in Power Query (Unpivoting, Data Cleansing, Time-Series Structuring).
  * Relational Data Modeling in Power BI.
  * Custom DAX measures engineered for calculating Efficiencies, Revenue Losses, and Variances.

## Key Findings: National DisCos Overview
* **The Nationwide Revenue Gap:** Across all DisCos, out of ₦3.64 Trillion in Energy Received and ₦3.0 Trillion Billed, only ₦2.32 Trillion was collected. This translates to an industry-wide **Billing Efficiency of 81.94%** and a **Collection Efficiency of 77.65%**.
* **Total National Revenue Loss:** The sector suffered a massive ₦1.33 Trillion in lost revenue. Notably, this loss is split almost evenly nationwide: ₦667.97 Billion lost to collection failures, and ₦658.29 Billion lost to billing inefficiencies.
* **Top vs. Bottom Performers (ATC&C):** Eko and Ikeja DisCos lead the nation with the lowest ATC&C losses (27.98% and 27.99% respectively) and the highest collection efficiencies (~87.9%). Conversely, Kaduna (62.58%), Jos (62.23%), and Kano (49.71%) sit at the bottom, suffering the most severe aggregate losses.

## Key Findings: KEDCO (Kano) Deep-Dive
* **The Efficiency Paradox:** Kano displays a phenomenal **Billing Efficiency of 92.57%**, making it the 2nd best in the nation (trailing only Eko DisCo) and performing 10.63% above the national average. However, KEDCO's **Collection Efficiency sits at a critical 61.38%** (ranking 9th out of 11), sitting 16.27% below the national average.
* **The 80/20 Revenue Loss Profile:** Unlike the national average (which is a 50/50 split), KEDCO's revenue loss is highly skewed. Out of its ₦85.40 Billion total revenue loss, a staggering **82.3% (₦70.28 Billion) is due to collection failure**, while only 17.7% (₦15.12 Billion) is lost to billing. 
* **ATC&C Target Deficit:** KEDCO recorded an ATC&C Loss of 43.18%, leaving a massive 22.60% gap from the regulatory MYTO target of 20%. While Kano can successfully invoice for the energy it distributes (₦188.45B billed from ₦204B received), the lack of revenue recovery (only ₦111.70B collected) cripples its commercial viability.

## Repository Contents
* `doc.txt`: Original project methodology and notes.
* `Model Measures.csv`: Complete list of DAX measures and formatting.
* Dashboard images for visualization.
