# Retail_customer_profile
This project focused on understanding customer purchasing behavior within a retail environment.
## Dataset

This project uses a simulated retail dataset modeled on real-world supermarket purchasing behavior. The data is anonymized and intended for analytical demonstration purposes only.

The analysis is based on two datasets:

### Transaction Data

| Column         | Description                    |
| -------------- | ------------------------------ |
| DATE           | Transaction date               |
| STORE_NBR      | Store identifier               |
| LYLTY_CARD_NBR | Anonymized customer identifier |
| TXN_ID         | Unique transaction identifier  |
| PROD_NAME      | Product purchased              |
| PRICE          | Unit price                     |
| PROD_QTY       | Units purchased                |
| TOT_SALES      | Total transaction value        |

### Purchase Behaviour Data

| Column           | Description                    |
| ---------------- | ------------------------------ |
| LYLTY_CARD_NBR   | Anonymized customer identifier |
| LIFESTAGE        | Customer life-stage segment    |
| PREMIUM_CUSTOMER | Customer spending segment      |

### Data Preparation

Both datasets were cleaned and merged using `LYLTY_CARD_NBR` as the common key, resulting in a consolidated dataset, `merged_data`. This combined dataset was used throughout the analysis to examine purchasing behaviour across different customer segments and life stages.

