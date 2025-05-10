# Project Outline
---
## Title:
Atliq Supply Chain Delivery Performance Dashboard – (March — August) 

---
## Objective:
To evaluate the end-to-end delivery performance of our products across cities and customer segments within the months of March to August. This analysis aims to identify delays, fulfillment gaps, and potential improvement areas in order accuracy, delivery timing, and inventory fulfillment.

---
## Problem Statement
- How can we improve order and inventory fulfillment rates?
- What factors are contributing to low On-Time(OT)  and In-Full(IF) performance?
- Which cities, products, and customers show the highest deviation from targets?
- How can logistics and supply chain processes be optimized to meet OTIF (On Time In Full) goals?

---
## Tools Used
Power BI (for Data Integration, DAX Measures, and Visual Analysis)

---
## Visualization Approach
- Cleaned and modeled data using Power Query Editor in Power BI.
- Developed a DAX Measures Table for KPI calculations such as OT %, IF %, OTIF %, LIFR %, and VOFR %.
- Created KPI Cards for key metrics:
   - On-Time Target: 57.14% (Goal: 86.09%, -33.62%)
   - In-Full Target: 53.97% (Goal: 76.51%, -29.47%)
   - On-Time In-Full (OTIF): 23.81% (Goal: 65.91%, -63.88%)
   - Total Orders Delivered: 32K
   - Total Orders: 57K
   - Total Quantity Delivered: 12.97M
   - Total Quantity Ordered: 13.43M
   - LIFR % (Line Item Fill Rate): 65.96%
   - VOFR % (Volume Fill Rate): 96.59%
- Implemented matrix tables and heatmaps:
   - Customer-level performance breakdown for OT %, IF %, OTIF %, LIFR %, and VOFR %.
   - Product-level tracking of LIFR/VOFR trends across months.
   - City-wise comparison vs targets for OT %, IF %, and OTIF %.
- Added filters for: City, Category, Product Name, Week Number, and Month

---
## Key Observations
- Overall OTIF performance (23.81%) is significantly below the target (65.91%), indicating a major challenge in delivering orders both on time and in full.
- On-Time % (57.14%) and In-Full % (53.97%) also underperform, far below respective targets.
- VOFR remains strong at 96.59%, suggesting volume shipped is largely consistent with orders placed, despite low fulfillment precision.
- LIFR is weak (65.96%), indicating poor performance at the line-item level, possibly due to stock-outs or process delays.
- Top-performing customers (based on OTIF %) include:
    - Propel Mart (40.92%)
    - Logic Stores (38.78%)
    - Expression Stores (38.39%)
- Lowest-performing customers:
    - Coolblue (13.75%)
    - Acclaimed Stores (15.47%)
    - Info Stores (25.52%)
- City Performance:
   - All cities (Ahmedabad, Surat, Vadodara) underperform in OTIF (range: 27.78%–30.07%) vs their targets (~65%).
   - Surat leads slightly in OTIF (30.07%) and IF % (52.55%) among cities.
- Product Trends:
   - Consistently high VOFR % across products (>96%), suggesting packaging and dispatch volumes are maintained.
   - LIFR for some items like AM Butter 250 (63.52%) and AM Ghee 250 (65.25%) indicates bottlenecks in certain SKUs.

---
## Summary of Findings
- Major gap exists in combined On-Time In-Full metrics—highlighting systemic supply chain inefficiencies.
- Volume fulfillment is not the issue; the challenge lies in timing and SKU-level accuracy.
- Several customer accounts show significantly low OTIF, affecting reliability and satisfaction.
- City-wide performance is below expected benchmarks, with no region exceeding 31% OTIF.
- Despite underperformance in other KPIs, VOFR is consistently strong, which is a key foundation for fixing other metrics.

---
## Recommendations
1. Improve OT and IF performance:
  - Implement tighter SLAs for warehouse picking and dispatch scheduling.
  - Identify stockout patterns by SKU and strengthen replenishment cycles.

2. Address Root Causes of Poor OTIF:
  - Audit high-delay customers (e.g., Coolblue, Acclaimed Stores) for recurring issues.
  - Set up alert systems for line-item shortages at the order acceptance stage.

3. Focus on City-wise Optimization:
  - Launch targeted process improvements in Ahmedabad and Vadodara, which show the weakest OTIF vs goal gap.

4. Leverage Strong VOFR:
  - Since VOFR is robust, develop SKU-level logic to distribute shipment volumes more strategically based on fulfillment likelihood.

5. Data-Driven Capacity Planning:
  - Use LIFR data per product (e.g., butter, curd) to prioritize SKU adjustments in planning and supplier coordination.

---
## Data Source
CodeBasic Competition

---
## Technical Details
- Tool Used: Power BI
- Visuals Used: Card KPIs, Line Graphs, Matrix Tables, Heatmaps
- Techniques Displayed : Power Query Cleaning, DAX Measures, Filter Slicers
- Timeframe: March – August

