# Bank Card Portfolio Dashboard

## 🎯 Project Objective
The objective of this project is to analyze bank card data using Microsoft Excel. The analysis focuses on card types, card brand availability, card issuance, account opening dates, and other relevant card attributes to generate meaningful business insights.

## 🗂️ Dataset Description
The dataset contains bank card information for different clients. Each row represents a card record and includes information such as credit limit, chip availability, number of cards issued, account opening date, and card security information.

## 📋 Dataset Columns
| Column | Description |
| :--- | :--- |
| **Card ID** | Unique identifier for each card |
| **Client ID** | Unique identifier for each client |
| **Card Brand** | Brand of the card (e.g., Visa, Mastercard) |
| **Card Category** | Type of card, such as Credit or Debit |
| **Card Number** | Unique 16-digit card number |
| **Expiration Date** | Card expiration date |
| **CVV** | Card verification value |
| **EMV Chip Enabled** | Indicates whether the card has a secure EMV chip |
| **Card Issued No.** | Total number of physical cards issued for the account |
| **Credit limit** | Financial credit limit associated with the card |
| **Account Open Date** | Date when the client's account was opened |
| **Last Pin Update Year** | Year when the account PIN was last changed |

---

## 🛠️ Tools & Technologies
* **Microsoft Excel**
* **Pivot Tables & Pivot Charts**
* **Interactive Slicers**
* **Dashboard Design & Layout**
* **Data Cleaning & Aggregation**

## 📊 Dashboard Features

**Key Performance Indicators (KPIs)**
* **Total Cards:** 9,238
* **Average Credit Limit:** ₹14,347.49
* **Total Client:** 6,146
* **Maximum Credit Limit:** ₹1,51,223.00
* **Minimum Credit Limit:** ₹500.00

**Visual Charts & Analytics**
* **Card Issued Per Year:** Line chart tracking historical card issuance volume.
* **Total Credit Limit by Brand:** Horizontal bar chart comparing portfolio value across networks.
* **Credit vs. Debit Card Ratio:** Pie chart showing the primary product mix.
* **Total Card by Brand:** Column chart detailing card volume per network.
* **Credit vs. Debit by Brand:** Clustered column chart breaking down product types within each specific brand.
* **EMV Enabled Adoption:** Doughnut chart tracking security compliance.
* **Client per Brand:** Pie chart showing customer distribution across networks.
* **PIN Change Per Year:** Column chart highlighting customer security hygiene and update frequency.
* **Expiration Year:** Column chart forecasting upcoming card renewal cycles.

**Interactive Filters (Slicers)**
* Card Brand (Amex, Discover, Mastercard, Visa)
* Year
* Month
* Card Category (Credit / Debit)
* EMV Chip Enabled Status (Yes / No)

## 🖼️ Dashboard Preview
![Screenshot 2026-11-19 211911.png]


## 🔍 Key Insights

**Financial Overview**
* The bank manages a substantial credit portfolio with a **Total Credit Limit of ₹8.81 Crores**.
* The **Average Credit Limit** extended per card account stands at **₹14,347.49**.
* **Mastercard** represents the largest segment of the total credit limit portfolio, significantly outpacing Visa, Discover, and Amex.

**Brand & Product Distribution**
* The user base of **6,146 clients** holds **9,238 cards**, indicating a healthy multi-card ownership rate among the customer base.
* Mastercard and Visa dominate both the sheer volume of cards issued and the total client distribution, making up the vast majority of the pie charts.

**Security & Compliance Trends**
* **EMV Adoption:** The portfolio shows strong security compliance, with **80%** of all active cards being EMV Chip enabled.
* **PIN Updates:** There is a massive spike in PIN changes recorded in recent years (around 2019/2020), which may correlate with a bank-wide security push or a mass card re-issuance event.

**Operational Forecasting**
* **Issuance & Expiration:** The "Card Issued Per Year" line chart shows a recent sharp upward trend in new cards. Consequently, the "Expiration Year" chart maps out significant future spikes, allowing the operations team to accurately forecast printing and mailing costs for upcoming renewal cycles.
