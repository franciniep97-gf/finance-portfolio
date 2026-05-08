# 📊 Project Brief — Sales Data Cleaning

## 🎯 Objective

Clean and standardize a messy Q1 sales dataset so it could actually be used for analysis.
The raw data had multiple formatting issues that made it unreliable.

## 🛠️ Tools Used

* Power Query
* Excel

## 🔄 Process

* Removed 2 duplicate records
* Standardized product names using **PROPER** case
* Unified 4 different date formats into **YYYY-MM-DD** using custom Power Query logic
* Fixed decimal separators (commas vs periods)
* Created a custom column to convert incorrectly stored values into proper percentages

  * Example: `250% → 2.5%`
* Replaced 1 missing customer name with **"Unknown"** to preserve record integrity

## ⚠️ Key Challenge

The **discount column** had values stored incorrectly as whole numbers instead of decimals.
Catching this required understanding what the data *should* look like, not just what it looked like.

## ✅ Result

* 40 clean records
* 0 duplicates
* 0 errors

✔️ Dataset ready for financial analysis.

## 📈 Insights from Clean Data

* 🇨🇷 Costa Rica had the highest order volume (**40%**) but the lowest average discount (**2.1%**)
* 🇵🇦 Panama had the lowest average shipping cost (**$6.20**)
* 👥 Top customers by volume:

  * Diego Morales (4 units)
  * Raul Aguilar (4 units)

![Project Screenshot](sales-data-cleaning.png)

<img width="1200" height="627" alt="sales-data-cleaning" src="https://github.com/user-attachments/assets/7879888b-93af-4c32-a1f7-ec635100b0a1" />
