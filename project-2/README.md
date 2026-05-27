# 📊 Project Brief — Product Profitability Analysis

## 🎯 Objective
Analyze Q1 sales data to understand which products are actually making money and which ones are eating into margins, using the clean dataset from the previous project.

## 🛠️ Tools Used
- Excel  
- Power Query  

## ⚙️ Process
1. Merged the clean sales table with a cost structure table in Power Query (COGS, marketing costs, warehouse costs)  
2. Calculated revenue, total costs, profit, and margin % per order in Excel  
3. Built a summary table using `SUMIF` and `AVERAGEIF` to aggregate by product  
4. Identified top 5 products by profit using `LARGE`  
5. Used `XLOOKUP` to find the highest-margin product  
6. Used `FILTER` with `IFERROR` to flag problematic products  

## 📈 Key Metrics
- **Total Revenue:** $2,603  
- **Total Profit:** $933  
- **Average Margin:** 35.4%  
- **Highest Margin Product:** Polo Manga Larga (39%)  
- **Most Profitable Product:** Pantalón Denim Azul ($125.37)  

## 🔍 Insights
- **Chaqueta Denim Clásica** has the highest marketing cost per unit ($7) but only sold 3 units. Budget is being wasted on a low-volume product.  
- **Camiseta Básica Blanca** moves the most volume (11 units) but has a below-average margin, likely due to free shipping absorbing profit. A minimum order value could fix this.  
- **Polo Manga Larga** has the best margin and low discounting. It's the strongest candidate for scaling with paid marketing.  

## 💡 Business Impact
Identified over **$150 in recoverable profit** through two specific policy changes:
- Reallocating marketing spend
- Adjusting shipping thresholds

![Project Screenshot](profitability-analysis.png)

<img width="1200" height="627" alt="profitability-" src="https://github.com/user-attachments/assets/609c61a0-b54b-4a88-a0d6-64b75bb285d3" />

