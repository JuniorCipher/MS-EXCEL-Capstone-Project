# Sales Analysis Project

## Table of contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)
- [Recommendations](#recommendations)

### Project Overview

This project focuses on analyzing sales performance over a specific period to uncover insights that can guide better business decisions.

The main objectives were to:

- Analyze overall sales performance and trends.

- Identify high and low-performing products and regions.

- Understand customer purchasing patterns.

- Provide actionable, data-driven recommendations.

- Visualize findings using Power BI dashboards and Excel charts.

### Data sources

- Spreadsheet: MS Excel and SQL Server.

This dataset captures key details such as Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Total Amount. These fields enable a broad view of sales performance and customer behavior.

### Tools

- Excel - Used for data cleaning and basic analysis.
  - [Download here](https://microsoft.com)
- Power BI – Used for visualization and report creation

### Data Cleaning and Preparation

Before starting the analysis, I ensured the dataset was well-structured and consistent.

Steps taken:

- Defined the main goal of the project and reviewed the data structure.

- Collected the dataset and saved it as an Excel file.

- Transformed the data by removing duplicates, trimming spaces, and correcting text inconsistencies.

- Checked and corrected column names, mixed cases, and formatting errors.

- Converted the dataset into a table and used pivot tables for summary and organization.

- Used charts to make the data more visually appealing and easier to interpret.

- The business generated over 353 million in revenue with nearly 8,000 items sold, indicating strong market performance and customer demand

### Exploratory Data Analysis (EDA)

From the analysis, I observed that the business generated over ₦353 million in revenue, with nearly 8,000 items sold — indicating strong performance and customer demand across multiple product categories.

### Data Analysis

Some of the Excel functions used during analysis include:

1. These functions helped in cleaning customer names and counting the total number of items sold.
```Excel
=Trim(PROPER(Table1[Customer ID))

=COUNTA(Table5[Quantity sold])
```

2. Converts text that looks like a number into a real numeric value.
```
=VALUE(D2)
```

3. Combines text from multiple cells.
```
=CONCAT(A2, " ", B2)
```

4.Counts rows based on multiple criteria.
```
=COUNTIFS(Category,"Clothing",Region,"North")
```

### Results and Findings

1. Regional Performance:
The company’s strongest markets are in the NE and SW regions, while NW and SE may require targeted marketing strategies to increase revenue.

2. Product Performance:
Coca-Cola led the product line in revenue, followed by Five Alive and Eva Water. Focusing on Fanta and Sprite could help balance the product portfolio.

3. Customer Insights:
A small group of top customers — especially Vaughn, Harlon, and Owen Robert — contribute a large portion of revenue. Maintaining strong relationships with these customers can help sustain growth.

<img width="1120" height="883" alt="image020" src="https://github.com/user-attachments/assets/2379c7f0-5dcc-41e1-9264-47fc08745cdb" />


### Recommendations

Based on the analysis, I recommend the following actions:

1. **Strengthen Key Account Relationships:**
Offer loyalty programs or special deals to top customers like Vaughn, Harlon, and Owen Robert.

2. **Upsell to Mid-Tier Customers:**
Encourage customers generating ₦26M–₦32M to buy more through bundle deals or discounts.

3. **Boost Low-Performing Regions:**
Focus on the NW and SE regions with targeted campaigns and region-specific promotions.

4. **Promote High-Performing Products:**
Increase marketing for Coca-Cola and Five Alive, while improving visibility for Sprite and Fanta.

5. **Personalize Marketing:**
Use purchase data to send personalized offers and retain customers with declining purchase patterns.

### Limitatiions

During this project, I experienced some Excel-related challenges such as formula errors, text case inconsistencies, duplicate records, and repeated columns. These issues were corrected during the data cleaning stage.

### Conclusion

This project demonstrates how Excel and Power BI can be combined to clean, analyze, and visualize sales data effectively. The insights gained can support better business planning, product promotion, and customer relationship strategies.

 ### References

1. Microsoft. (2024). Microsoft Excel [Computer software](https://microsoft.com)

2. Microsoft. (2024). Power BI [Computer software](https://powerbi.microsoft.com)


 😆
 
 💻

|Heading1|Heading2|
|--------|--------|
|Content|Content|
|Python|SQL|
