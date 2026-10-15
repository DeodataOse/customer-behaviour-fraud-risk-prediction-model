# Customer Behaviour Fraud Risk Prediction Model

## Project Overview

Fraud detection is challenging because fraudulent transactions are relatively rare and a transaction cannot always be judged by its value alone.

This project explores whether understanding a customer's normal transaction behaviour can provide additional insight into potential fraud risk.

Rather than looking at each transaction in isolation, the project considers the transaction in relation to the customer's previous activity, including spending patterns, transaction frequency, timing, country and device behaviour.

The project also explores unusual transaction behaviour and provides explanations for the factors that influence the model's risk assessment.

## Project Objective

The main objective of this project is to investigate whether customer behavioural patterns can help identify and prioritise transactions that may require further fraud investigation.

The project aims to:

- Understand patterns in legitimate and fraudulent transactions.
- Develop features that describe customer behaviour.
- Compare different approaches to fraud-risk prediction.
- Investigate unusual transaction behaviour.
- Understand which factors influence model predictions.
- Present the results through an interactive Streamlit dashboard.

## Key Findings

The analysis identified a clear relationship between transaction amount and the customer's previous spending behaviour.

Transactions that were more than three times the customer's previous average transaction amount had an observed fraud rate of approximately **4.59%**, compared with approximately **1.5%–1.6%** for transactions closer to the customer's historical average.

This suggests that customer-relative spending behaviour can provide useful context when assessing transaction risk.


> Can understanding what is unusual for a customer provide useful information for assessing fraud risk?
