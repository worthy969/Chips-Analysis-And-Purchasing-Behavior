# Chips-Analysis-And-Purchasing-Behavior
This Analysis is focused on understanding the type of Customers who Purchases chips and their purchasing behavior within the region.
![chips](img_pringles.jpg)
## PROJECT BRIEF
I am part of Quantium's retail analytics team and have been approached by my client,the Category Manager for chips, who wants to better understand the types of customer who purchases Chips and their purchasing behaviour within the region.
  The insight from this analysis will feed into the supermarket's strategic plan for the chip category in the next half year.

## OBJECTIVE
* **Examine  transaction data** --- look for inconsistencies,missing data across the dataset, outliers, correctly identified category items, numeric data across all tables.
* **Examine customers data**  --- check for similar issues in the customer data, look for nulls and when it's perfect merge the transaction and customer data together so it can be ready for analysis.
* **Data analysis and customer segments** --- in your analysis make sure you define the metrics -- look at total sales,drivers of sales, where the highest sales are coming from etc. Explore the data, create charts and graphs as well as noting any interesting trends  and/or insights you find.
* **Deep dive into customer segments** --- define your recomendation from your insights, determine which segment we should be targeting, if packet sizes are relative and form overall conclusion based on your analysis

## DATA OVERVIEW
This analysis was done using two different tables 
1. The Customer Dataset (QVI_purchase_behaviour.csv) contains 72,637 entries with three columns:
* LYLTY_CARD_NBR: The Customer ID
* LIFESTAGE: Customer life stage, categorical
* PREMIUM_CUSTOMER: premium status, categorical <br>  **THERE ARE NO MISSING VALUES IN THIS DATASET**
  
2. The transaction dataset (QVI_transaction_dataset.xlsx) contains 264,836 entries with eight columns:
* DATE: integer, possibly in excel format
* STORE_NBR: store numbers
* LYLTY_CARD_NBR: customers ID
* TXN_ID: transaction ID
* PROD_NBR: product number
* PROD_QTY: Quantity purchased
* TOT_SALES: Total sales amount <br> **THERE ARE NO MISSING VALUES**

### Key Takeways: 
* Doritos, Smiths, and kettle are the most popular brands across all segments.
* Doritos is especially strong among Young Singles/Couples and Budget shoppers.
* Smiths is dominant among Young Older Families and Retirees.
* Premium customers prefer Tyrrells and kettle, which are positioned as premium  brands.
* Budget-conscious consumers buy more Woolworths and home-brand chips.
* Twisties and CC's have a solid presence in all groups but are more common Young Families.

## Final Recommendations for the Next 6 Months 
1. Target Young Singles/Couples with Doritos promotions (e.g, digital ads,in-store discounts).
2. **Strengthen Smiths marketing for Older Families and Retirees(e.g, bundle deals, family-size packs)**.
3. **Expand premium-brand advertising (kettke, Tyrrells)** for high-income customers.
4. **Offer bulk deals on larger pack sizes (330g+)** to attract Older Families and Retirees.
5. **Reduce focus on small pack sizes (under 110g),** as they have low demand.
