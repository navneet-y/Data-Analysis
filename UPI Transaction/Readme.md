# UPI Transaction Analysis Dashboard

This repository contains the Power BI project files and related assets for a dashboard that analyzes Unified Payments Interface (UPI) transaction data. The dashboard provides insights into transaction volume, value, payment methods, demographics, and geographic distribution.

## Problem Statement

The rapid growth of digital payments in India, particularly through UPI, has generated a wealth of transaction data. Analyzing this data is crucial for understanding user behavior, identifying trends, optimizing payment systems, and making informed business decisions. This project aim to address the need for a comprehensive visualization tool to provide actionable insights from UPI transaction data.

## Objectives

*   Visualize key performance indicators (KPIs) related to UPI transactions, such as total transaction amount, average transaction amount, and success ratio.
*   Analyze transaction distribution by payment method (UPI ID, Phone Number, QR Code).
*   Understand transaction patterns across different age groups and genders.
*   Map transaction activity geographically to identify regional trends.
*   Track transaction trends over time to identify seasonal patterns or growth areas.
*   Analyze transactions by bank, device type, transaction type, status, and purpose.

## Data Sources

The data used for this dashboard is synthetic/sample transaction data. The dataset includes the following columns:

*   TransactionID
*   TransactionDate
*   Amount
*   BankNameSent
*   BankNameReceived
*   RemainingBalance
*   City
*   Gender
*   TransactionType
*   Status
*   TransactionTime
*   DeviceType
*   PaymentMethod
*   MerchantName
*   Purpose
*   CustomerAge
*   PaymentMode
*   Currency
*   CustomerAccountNumber
*   MerchantAccountNumber

## Dash Board

![Image](https://github.com/user-attachments/assets/87069f47-946e-4b40-b020-b4c19e49370a)

![Image](https://github.com/user-attachments/assets/82ccfd1a-4aa0-4ed8-b3ae-da7fe7e27731)

## Dashboard Features

The Power BI dashboard includes the following visualizations:

*   **KPI Cards:** Displaying key metrics like total transaction amount, average transaction amount, success ratio, and total transactions. (Note: The original dashboard had a discrepancy between the total transaction amount and total transactions. This should be addressed in the data.)
*   **Donut Charts:** Showing the distribution of transactions by payment method, age group, payment mode, and gender.
*   **Geographic Map:** Visualizing transaction activity across different cities in India and surrounding regions.
*   **Line Chart:** Tracking transaction amounts over 12 months.
*   **Bar Charts:** Comparing transaction volumes across different banks, device types, transaction types, status, and purposes.


## Technologies Used

*   Power BI Desktop
*   Power Query
*   GitHub


Thanks For visiting :)


