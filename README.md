# Sales Analysis Project

## Table of contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

## Project Overview

- To analyze sales performance over a specific period. 
- To identify trends and patterns in customer purchases. 
- To detect high and low-performing products or regions.
- To provide data-driven insights for better decision-making. 
- To visualize results using charts and dashboards in Excel.


### Data sources

Spreedsheet: MS Excel and SQL Server.

### Tools

- Excel - Data Cleaning.
  - [Download here](https://microsoft.com)
- SQL Server - Data Analysis.
- PowerBI - creating report.

### Data Cleaning/Preparation

1. Define the key problem of the data.
2. collect the data from the database and save it as excel file.
3. Transform the data by analyzing, filtering and using function command to add, trim and count. I also remove duplicate, repeated columns and mixed cases for the strings.
4. I visualize the data by converting my data into a table, using pivot table to separate and merge columns and rows. I also use m chartr to make them look presentable.

### Exaploration Data Analysis

The business generated over 353 million in revenue with nearly 8,000 items sold, indicating strong market performance and customer demand

### Data Analysis

  Including some interesting functions/features worked with,

```Excel
=Trim(PROPER(Table1[Customer ID))

=COUNTA(Table5[Quantity sold])
```

### Results/Findings

  1. The company’s strongest markets are in the NE and SW regions, while NW and SE may require targeted strategies to boost revenue. This regional performance insight can guide future resource allocation and regional campaigns.
  2. Coca-Cola leads the product line in revenue, followed closely by Five Alive and Eva Water. Focusing on increasing Fanta and Sprite sales could balance the product portfolio and boost overall revenue.
  3. A small group of top customers (especially Vaughn, Harlon) account for a large portion of the revenue. Strategic focus should be placed on retaining high performers while nurturing mid and low-tier customers for growth.

<img width="1120" height="883" alt="image020" src="https://github.com/user-attachments/assets/2379c7f0-5dcc-41e1-9264-47fc08745cdb" />


### Recommendations

  Based on the analysis, we recommend the following actions:
   1. Strengthen Key Account Relationships Prioritize top customers like Vaughn, Harlon and Owen, Robert with loyalty programs or exclusive offers.
   2. Upsell to Mid-Tier Customers Target customers generating ₦26M–₦32M with bundle deals or product upgrades to increase their spend.
   3. Boost Underperforming Regions Focus marketing efforts on NW and SE regions where revenue is lower, using region-specific promotions.
   4. Promote High-Performing Products Increase marketing for Coca Cola and Five Alive, which drive the most revenue, while improving visibility for Sprite.
   5. Data-Driven Customer Engagement     Use customer purchase data to personalize marketing and improve retention, especially for customers with declining revenue.


### Limitatiions

During this analysis, I encountered excel misinterpretation of function. the data came with a lot of errors, mixed cases, double columns and duplicates.
 
 ### References

1. MicroSoft Excel.
2. PowerBI.


 😆
 
 💻

|Heading1|Heading2|
|--------|--------|
|Content|Content|
|Python|SQL|
