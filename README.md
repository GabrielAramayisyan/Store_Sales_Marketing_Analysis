# Store Sales Marketing Analysis  

## Overview  
Analysis of sales transactions (2014–2016) to identify profitable customer segments, measure the effectiveness of discount campaigns, uncover seasonal trends, and evaluate shipping mode preferences.  

**Tools Used:** Excel, Power BI  

---

## Power BI Dashboards

[Dashboard_1](Power_BI/Screenshots/Dashboard_1.png)
[Dashboard_1](Power_BI/Screenshots/Dashboard_2.png)
[Dashboard_1](Power_BI/Screenshots/Dashboard_3.png)
[Dashboard_1](Power_BI/Screenshots/Dashboard_4.png)

---

## Problem Statement
A retail company wanted to answer key marketing questions:
- Which customer segments are most profitable and should be targeted more aggressively?
- What products or sub-categories respond best to discount campaigns?
- Are there seasonal sales patterns by region or category that can guide promotions?
- Do specific cities or customer groups respond differently to shipping modes?

---

## Workflow
1. **Data Cleaning**
   - Removed duplicates in Excel
   - Created unique IDs by combining row information for customers and products to fix the data entry errors (e.g., same product ID for different products, same order ID for different customers).
   - Normalized the table to nearly the 2nd normal form by splitting it into "Customers" and "Products" dimensions, and "SalesTransactions" facts table  
3. **Visualization in Power BI**  
   - Built interactive dashboards for segment profitability, discount effectiveness, seasonal trends, and preferred ship mode.
   - Used DAX to create measures such as sales lift, price change from the previous to the last quarter, average units sold in a day with/without discount.

---

## Key Insights  

- **Customer Segments**  
  - Consumer: historically most profitable (**$88K profit, 46% of total**).  
  - Corporate: surged **+430% in Q3–Q4 2016**, surpassing Consumer by 59%.  

- **Discount Campaigns**  
  - Positive response: Envelopes (+20%), Fasteners (+10%), Chairs (+5%).  
  - Negative response: Copiers (−24%), Accessories (−15%), Machines (−11%).  

- **Seasonality**  
  - November peaks: Office Supplies (+457%), Furniture (+326%), Technology (+472%).  

- **Shipping Modes**  
  - Standard Class dominated across all segments and cities.  
  - Same Day adoption consistently <6%.  

---

## Recommendations  
- Leverage Corporate’s recent profit growth while maintaining Consumer engagement.  
- Focus discounts on price-sensitive items; reconsider discounts for Copiers, Accessories, Machines.  
- Prioritize **Q4 (November)** promotions in Office Supplies, Furniture, Technology.  
- Test Same Day delivery promotions in top cities or optimize existing shipping classes.

View the whole findings and recommendations in the [Word file](Head of Marketing.docx) 

---

## Project Files  
- [Power BI Dashboard](Power_BI/Power_BI_Report.pbix)
- [Excel Data Wrangling](Excel_Normalization)
- [Raw Data](Raw_Data.csv)
