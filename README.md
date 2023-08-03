# Tableau
Northwind Traders Data Analysis Project 

View dashboard here: [Northwind Traders Tableau Dashboard](https://public.tableau.com/app/profile/sarah.turner4702/viz/NorthwindTraders_16899754828470/Dashboard1)

For this project, I analyzed sales and order data for Northwind Traders, a fictitious gourmet food supplier. I obtained the dataset from [Maven Analytic's Data Playground.](https://app.mavenanalytics.io/datasets) 

The data represents July through December of 2013, all of 2014, and through May 6 of 2015. 

My analysis is focused the performance of Northwind Traders for the current year (the last year of data is 2015, and latest order date is 5/6/2015). I analyzed performance based on sales totals (revenue), customer count, and order count. I looked at these metrics overall, by product category, by specific product, and by customer. Many of the visuals focus on comparing 2015 numbers to 2014, and some of the visuals include metrics from all of the years to show trends and patterns over time. 

## Business Questions
1. How are sales going so far in 2015 as compared to the previous year?
2. Which categories bring in the most revenue?
3. Which products have the highest and lowest sales?
4. Are there any key customers? Has this changed over time? 

## Data Analysis Process
I downloaded the datasets and did some initial cleaning in Excel (changed header names, ensured data types are correct and consistent, checked for missing values or nulls). Then, I uploaded the data to Tableau and created relationships in the data source pane. From here, I used only Tableau to analyze and visualize the data. I did occassionally open the data in Excel to QA my Tableau calculations or search for the data to find certain values or quickly answer a question-- this is much faster and easier to do in Excel. 

### Skills Demonstrated
* Parameters & Parameter Actions
* LOD expressions
* Table calculations
* Calculated fields (aggregations, conditional--If, Case)

## Key Insights
1. As of 5 weeks into Q2 of 2015, sales have reached at least 50% of the sale total for the entire year of 2014, in all categories. For beverages specifically, sales in 2015 have already surpassed 2014.
2. Customer count and order count are also up in 2015 as compared to 2014.
3. Dairy products brought in the most revenue in 2014; in 2015, beverages are in the lead so far
4. There are a few products that are bringing in a large percentage of overall sales and sales in their category. For example, Cote de Blaye (a wine) has brought in 58% of sales in the beverages category so far in 2015. However, a closer look shows that some of the other beverage products have more orders, but cost less, therefore bringing in less revenue (investigate the categories and tool tips in the tree map for more information). So, Cote de Blaye is a well-performing product, but the other products appear to be just as or even more popular, based on number of orders, even though they are bringing in less sales overall.
5. There is year-over-year consistency with top customers that bring in the most sales revenue. Quick Stop, Ernst Handel, and Save-a-lot Markets are the leaders.
6. There is more to explore in the interactive dashboard! 
