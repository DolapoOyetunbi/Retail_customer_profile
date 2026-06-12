# Retail Analytics Project: Customer Segmentation & Purchase Behaviour Analysis

## 1. Executive Summary

This project analyzes retail transaction data to understand customer purchasing behaviour across different life-stage and spending segments.

The goal is to identify high-value customer groups and uncover patterns that can support better marketing and inventory decisions.

A detailed business summary, findings, and recommendations are provided in the accompanying presentation deck.

---

## 2. Project Highlights

- Analyzed retail transaction data across multiple customer segments  
- Built customer-level profiles using behavioural attributes  
- Identified high-value segments contributing most to total sales  
- Examined differences in purchase frequency and basket size  
- Conducted brand and pack size affinity analysis for the "Mainstream Young Singles/Couples" segment  
- Delivered business recommendations in an executive slide deck  

---

## 3. Business Problem

Retail businesses need to understand:
- Which customer segments generate the most revenue
- How purchasing behaviour differs across life-stage groups
- Where opportunities exist to increase basket size and customer value

This analysis supports targeted marketing and improved decision-making.

---

## 4. Dataset

This project uses a simulated retail dataset modeled on real-world supermarket purchasing behaviour. The data is anonymized and used for analytical demonstration purposes only.

The analysis is based on two datasets:

### Transaction Data
| Column | Description |
|--------|-------------|
| DATE | Transaction date |
| STORE_NBR | Store identifier |
| LYLTY_CARD_NBR | Customer identifier |
| TXN_ID | Transaction ID |
| PROD_NAME | Product purchased |
| PRICE | Unit price |
| PROD_QTY | Quantity purchased |
| TOT_SALES | Total transaction value |

### Customer Segmentation Data
| Column | Description |
|--------|-------------|
| LYLTY_CARD_NBR | Customer identifier |
| LIFESTAGE | Life-stage group |
| PREMIUM_CUSTOMER | Spending segment |

---

## 5. Data Preparation & Methodology

The datasets were cleaned and merged using `LYLTY_CARD_NBR` as the common key to form a unified dataset.

The analysis includes:

- Aggregation of transaction data to build customer-level purchase behaviour profiles  
- Segmentation of customers by life-stage and spending category  
- Analysis of sales contribution across customer segments  
- Comparative analysis of spend per unit across segments using Welch’s t-tests (`scipy.stats.ttest_ind`, unequal variance)  
- Brand and pack size affinity analysis for the "Mainstream Young Singles/Couples" segment  

---

## 6. Key Outputs from Analysis

The analysis reveals clear differences in purchasing behaviour across customer segments and highlights variation in spending intensity and contribution to total sales.

Full findings and recommendations are presented in the slide deck.

---

## 7. Tools & Technologies

- Python (pandas, numpy, matplotlib, seaborn)
- SciPy (statistical testing: independent t-test)
- Jupyter Notebook
- PowerPoint (business presentation)

---

## 8. Files in This Repository

- [Customer Segmentation & Purchase Behaviour Analysis Notebook](customer-segmentation-purchase-behaviour-analysis.ipynb) → Full analysis workflow  

- [Customer Profile Analysis Presentation](customer_profile_analysis.pdf) → Executive presentation with findings and recommendations

---

## 9. How to Use This Project

1. Review the Executive Summary above for project context  
2. Open the Jupyter notebook to explore the full analysis  
3. View the presentation for business insights and recommendations  
