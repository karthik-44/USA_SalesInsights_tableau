# USA_SalesInsights_tableau
Design a tableau dashboard to track the year on year KPI.

https://public.tableau.com/app/profile/venkata.r.k.kanna/viz/usa_sales/SalesDashboard  

## Purpose

Companies want to offer better service for their customers and improve their business growth and achieve their respective targets or goals. By analyzing the sales data of the company, one can see how the company is performing. Has the performance improved or declined? Where is the company losing its sales? Many other questions can be answered with the sales analysis.

In many companies, the sales team gets timely updates (daily/weekly/monthly) updates of the sales the company makes in the form of traditional excel sheets. Though analysis can be done using Excel, it has many shortcomings. The BI tools such as Power BI, Tableau offer many advantages which can be seen in this project.

To discover the hidden data insights so as to make better decisions for improving the sales and reduce the time spent on gathering the data for summaries.
  
## To whom it is useful?
This analysis can be used by/for any company which wants to see the overview of the company’s performance and take the business decisions.
  
## Success Criteria

Once automated, the sales team’s time can be saved from data gathering and analysis. The dashboard is created and the workflow is automated. The Sales Analyst’s time on obtaining the data manually in the form of excel sheets and doing the data gathering, cleaning and then doing analysis can be reduced a lot.  

Can get updated information and can take better sales insights. With just a couple of clicks, up to date information can be extracted and analyzed. This helps the stakeholders to make better business decisions.  

The highly interactive dashboards allow users to drill down into the data and explore different views and perspectives which makes it easier to identify trends, patterns, and insights that might be missed in static Excel spreadsheets.

## Advantages of Tableau Dashboards

**Interactive dashboards**: Dashboards are highly interactive, allowing users to drill down into the data and explore different views and perspectives. This makes it easier to identify trends, patterns, and insights that might be missed in static Excel spreadsheets.

**Real-time data updates**: Tableau dashboards can be configured to update automatically as new data is added, ensuring that users always have access to the most up-to-date information.

**Scalability**: Tableau is designed to handle large datasets and can scale to support enterprise-level analytics. This makes it a better option for organizations that need to analyze and visualize large amounts of data.

**Collaboration**: Tableau provides built-in collaboration features that allow users to share their dashboards with others and work together on data analysis. This can help to foster teamwork and improve decision-making across the organization.

## Data Overview
We have the sales data, where each row represents an order/sale made by the company.
The major attributes are:

Orders Table
Order ID	
Order Date	
Ship Date	
Ship Mode (First Class, Second Class, Standard Class, Same day)
Customer ID	
Customer Name	
Segment	(Consumer, Corporate, Home Office)
City	
State/Province	
Postal Code	
Region	
Product ID	
Category	
Sub-Category	
Product Name

People Table
Region
Regional Manager

The column names are self explanatory.

The year on year sales analysis is done for the United States.
Current Year: 2022

## Sales KPI dashboard

Main questions to be included in the dashboard depends on the stakeholder requests. The below are few main aspects to consider:

- Sales CY vs PY
- Profit CY vs PY
- Orders CY vs PY
- Sales and Profit distribution by State.
- Monthly Sales/Profit/Quantity by Segment.
- Sales by location and manager.

## Observations  

### Sales CY vs PY
- Overall Sales of **$733K** were made during the year 2022.
- Compared to previous year the overall sales were **better** with a **20.36% increase** in sales count.
- The sales in months of **May, December** have **declined** compared to previous year. 
- **November** recorded the **maximum** sales with around **$118K**.
- **February** recorded the **minimum** sales with around **$20K**. 

### Profit CY vs PY
- Overall Profits of **$93K** were made during the year 2022.
- Compared to previous year the overall profits were **better** with a **14.24% increase**.
- The sales in months of May, December have declined compared to previous year. But this is not by a large margin.
- **March** recorded the maximum profits with around **$14.7K**.
- **April** recorded the minimum profits with just **$933**.
- The main notable observation is the profits for **October and December** have **declined** substantially compared to previous year. 
For October, there is decline in sales quantity, sales amount with respect to previous year.
**December profits** took a **hit**.

### Orders CY vs PY
- The quantity of products sold the current year is around **12K** and there is **26.83% increase** in the selling rate.
- Every month the number of items sold are more compared to previous year.
- This suggests that even though more products were sold during October, December we had a loss, so **either we sold the products from which we couldn’t make decent profits or sold the high MRP products at lower price.**

### Sales and Profit distribution by State
- The analysis was further breakdown statewise to see the Sales and Profit distribution simultaneously. 
- **California, NewYork** have the **highest** sales and **District of Columbia** have **very low** sales.
- **California, NewYork** have the **highest** profits and **Texas and Illinois** have more losses.
- This gives a quick overview of performance of various states with respect to the overall country market.
- The comparison with respect to the country’s average has been done, which indicates most of the states have done better than the country’s average value.

### Monthly Sales/Profit/Quantity by Segment.
- Analysis was broken down to Customer Segments - Consumer, Corporate, HomeOffice.
- From September, the Total Quantity has been around or more than the average value of across each of the segments.
- Total Sales is less than the average value for most of the months across the segments.
- **Highest profit ($9.68K)** was obtained during March by **Consumer goods.** 
- **Lowest profit (-$2.42K)** was during April by **Home Office goods.** 

### Sales by location and manager.
- The **western** region has the **largest** sales of **250.13K** which is around the sales obtained by south and central regions combined.
- The **southern** region has the **lowest** sales of 122.9K.

## End Result
Highly interactive tableau dashboard is created with proper visualizations that captures the required KPI values.
The above analysis can be even filtered out further based on:
- Region (East, West, Central, South)
- Category (Furniture, Office Supplies, Technology)
- Shipping Mode (First Class, Second Class, Standard Class, Same Day).

For example: We incurred a loss in the Furniture category and most of it occurred in October within the corporate category.


