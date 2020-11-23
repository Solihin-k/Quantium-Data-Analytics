# Quantium-Data-Analytics
Tasks completed during virtual internship @ Quantium

## Task 1 - Data Preparation and Customer Analytics

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region. <br>
The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.


<img src="https://bwmarija.files.wordpress.com/2012/08/chips-at-supermarket.png" width="400" height="350"/>

### Data

#### Purchase Behaviour

- LYLTY_CARD_NBR (numeric, unique customer identifier)
- LIFESTAGE (OLDER FAMILIES, YOUNG FAMILIES, OLDER SINGLES/COUPLES, RETIREES, MIDAGE SINGLES/COUPLES, NEW FAMILIES, YOUNG SINGLES/COUPLES)
- PREMIUM_CUSTOMER (Budget, Mainstream, Premium)

#### Transaction Data

- DATE (date of trasaction)
- STORE_NBR (store of purchase)
- LYLTY_CARD_NBR (numeric, unique customer identifier)
- TXN_ID (numeric, unique transaction identifier) 
- PROD_NBR (numeric, unique product identifier) 
- PROD_NAME (str, product name)
- PROD_QTY (quantity of product solde per transaction)
- TOT_SALES (total sales)

### Category Analysis

#### Largest Sales Contributor

![sales_breakdown](/charts/"Sales Breakdown.png")
