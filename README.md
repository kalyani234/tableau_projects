
# Sales Insight

### MySQL to Tableau

- The Dataset of transactions,markets,products, date, customers taken into the MySQL and performed some quering.


### Tableau
- Data cleaning is performed using Tableau 
   * Currency changed USD to INR columns in transactions table 
   * Indian states selected from markets Table
   * Cost price included greater than 1 in transactions table
   * New Normalised Sales Amount column is calculated using IF [Currency]== 'USD' THEN [Sales Amount]*74 ELSE [Sales Amount] END

- Charts performed:
   * Total Sales
   * Total Revenue
   * Profit by markets
   * Sales quantity by markets
   * Top 5 customers
   * Top 5 products
   * Revenue by year
   * year
   * month

### Dashboard created: https://public.tableau.com/app/profile/navya.kalyani/viz/Sales_Insight_17118154895250/Dashboard1?publish=yes

### Second Dashboard created of Profit margin and profit margin percentage

* Profit margin is calculated
* Profit margin percentage is calculated


## Charts created
* Profit 
* Profit Trend  SUM([profit_margin])/SUM([Normalised Sales Amount])
* Piechart of Customer Type and profit_margin %
* Customer Table

### Dashboard link:
https://public.tableau.com/app/profile/navya.kalyani/viz/Sales_Insight_2/Dashboard-ProfitAnalysis2?publish=yes
