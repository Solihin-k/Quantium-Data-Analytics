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

### Customer Analysis

![sales_breakdown](/charts/Sales_Breakdown.png)

![units per transaction](/charts/Units_per_Transaction.png)

![customer_breakdown](/charts/customer_breakdown_new.png)

- Mainstream Young Singles & Couples are the primary shopper of chips
- Young and Older Families make up 26% of Chips shoppes and on average purchase larger baskets (more opportunity)

- Affluence appears consistent across each individual life stage profile
- Older and Young Family shoppers purchase the highest avg units per transaction

- Mainstream Young Singles & Couples make up the largest proportion of Chips shoppers
- Mainstream Retirees also have a significant share


## Task 2 - Experimentation and uplift testing

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, has asked us to test the impact of the new trial layouts with a data driven recommendation to whether or not the trial layout should be rolled out to all their stores.


### Data

#### Full Data

- DATE (date of trasaction)
- STORE_NBR (store of purchase)
- LYLTY_CARD_NBR (numeric, unique customer identifier)
- TXN_ID (numeric, unique transaction identifier) 
- PROD_NBR (numeric, unique product identifier) 
- PROD_NAME (str, product name)
- PROD_QTY (quantity of product solde per transaction)
- TOT_SALES (total sales)
- PACK_SIZE	(packaging size)
- BRAND	(chips brand)
- LIFESTAGE (OLDER FAMILIES, YOUNG FAMILIES, OLDER SINGLES/COUPLES, RETIREES, MIDAGE SINGLES/COUPLES, NEW FAMILIES, YOUNG SINGLES/COUPLES)
- PREMIUM_CUSTOMER (Budget, Mainstream, Premium)

#### Trial Analysis

Control stores was determined based on the similarity in terms of:
- Monthly overall sales revenue
- Monthly number of customers

![control_sales](/charts/control_sales.png)

![control_customers](/charts/control_customers.png)

#### Trial Results

![control_sales_results](/charts/control_sales_results.png)

![control_customers_results](/charts/control_customers_results.png)

During the trial period of Feb to May 2019, the trial store outperformed the control store highlighting the success of the new store layout.
