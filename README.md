# 📊 Sales Analysis Dashboard (Excel)

## Overview

This project is an **interactive Sales Analysis Dashboard built in Microsoft Excel** using **Power Query, Power Pivot (Data Model), DAX, and Pivot Charts**.
It demonstrates an end-to-end analytics workflow—from raw data cleaning and modeling to a dynamic, presentation-ready business dashboard.


## Data Cleaning & Preparation

* Cleaned and transformed raw sales data using **Power Query**
* Fixed inconsistent and mixed date formats and converted them into valid dates
* Ensured logical consistency between **Order Date** and **Ship Date**
* Extracted **Year** and **Month** from Order Date for time-based analysis
* Loaded the cleaned dataset into the **Excel Data Model**


## Data Modeling & DAX

* Created calculated columns:

  * **Delivery Days** = Ship Date − Order Date
  * **Discount Band** using DAX
* Built DAX measures for:

  * Total Sales
  * Total Profit
  * Total Orders
  * Average Delivery Days
  * Profit Margin %

## Dashboard Features

* KPI cards for **Total Sales, Total Profit, Total Orders, and Avg Delivery Days**
* Sales and Profit trend analysis by Year
* Category-wise and Ship Mode-wise sales performance
* Region, Segment, and State-level analysis
* Discount impact on Profit Margin
* Top 5 Sub-Categories and Top 10 States by Sales
* Interactive slicers for Region, State, City, Year, and Month


## Business Insights (Quantified)

* **Standard Class shipping contributes ~59% of total sales**, outperforming First Class (~15%), Second Class (~20%), and Same Day (~6%).
* **Technology ($836K) and Furniture ($742K) together generate ~69% of total revenue**, making them the strongest revenue-driving categories.
* **Profit margins turn negative beyond ~40–50% discount levels**, revealing the risk of aggressive discounting.
* **West and East regions account for over 60% of total sales**, largely driven by the Consumer segment.
* **California ($458K) and New York ($311K) contribute ~34% of top-state sales**, indicating strong geographic concentration.
* **Average delivery time is ~4 days**, with longer delivery durations associated with reduced profitability.


## Recommendations

* **Optimize discounting strategy:**
  Cap discounts at **30–35%** and shift toward targeted promotions on high-margin products to prevent margin erosion.

* **Enhance Standard Class fulfillment:**
  Since it drives **~59% of sales**, improving cost efficiency and delivery speed in Standard Class can significantly improve overall profitability.

* **Prioritize high-performing categories:**
  Increase focus on **Technology and Furniture**, while reviewing pricing and cost structures in lower-margin Office Supplies.

* **Leverage regional strengths:**
  Expand targeted marketing and inventory planning in the **West and East regions**, especially **California and New York**.

* **Review underperforming sub-categories:**
  Reassess low-profit sub-categories with high sales volume and explore bundling, repricing, or cost optimization strategies.

---

## Tools & Technologies

* Microsoft Excel
* Power Query
* Power Pivot (Data Model)
* DAX
* Pivot Tables & Pivot Charts

<img width="1868" height="675" alt="image" src="https://github.com/user-attachments/assets/07c7de82-abc8-46f2-8ccb-3210f431d767" />

