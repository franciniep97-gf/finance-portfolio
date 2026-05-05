# 📦 Project Brief — Inventory Status Tracker

## 🎯 Objective

Track real inventory levels for a 10-product fashion retailer, combining warehouse stock and incoming units to flag reorder priorities.

## 🛠️ Tools Used

* Excel (formulas, conditional formatting)

## 🔄 Process

* Calculated real stock by combining current stock + units in transit
* Compared real stock against reorder point to determine if replenishment is needed
* Used nested **IF** logic to classify each product: **OK**, **CRITIQUE**, or **STOCKOUT**
* Calculated exact units to order based on reorder thresholds

## 🧮 Key Formulas Used

* IF
* Nested IF
* Basic arithmetic across multiple columns

## ✅ Results

* 10 products analyzed
* 2 products in **STOCKOUT**:

  * Zapatos Talla 38
  * Bolso Cuero Café
* 3 products in **CRITIQUE** status requiring urgent reorder
* 📌 Immediate reorder need identified: **146 units** across critical products

