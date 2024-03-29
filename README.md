 ## Wixsin Sales Analysis 


## Project Overview

This Data Analysis project aim to provide insight into the sales performance of their products and revenue of the year. After proper analysis of sales data of wixsin company, data driven insights and KPIs was generated with adaquate recommendation and deeper understanding of the company performance.


### Data Sources 

The dataset was a cvs excel file containing different tables information such as the location, maunfacturuer, sales, products made by the company. All the tables were consolidated together into one table. The dataset has some mising vlaues and columns which analysed and created by me.

### Tools

The tools used was Ms. Excel to cleaning data, analyse the data and for creating piovt table and dashbaord. 


### Data Cleaning/preparation

The dataset was loaded on Ms.Excel and steps was taken to inspect the dataset. The Excel spreadsheet consisted of different spreadsheets/tables which had to be merged together by consolidate the all as one spreadsheet. The spreadsheet was structured into a table called sales_table. some column were not included in the spreadsheet such as Month, Week which was created by me but extrated from Date column. The dataset has a total number of 1412 rows, total number of 14 columns, total Revenue of $ 9,826,183 and total units of 1430. 

### Data Exploratory and Analysis

The questions are:
- What is the contribution of each state in canada to revenue?
- What is the proportion of category to Revenue?
- What is the Top 5 Best selling Projects?
- How does the revenue of company performance Monthly?
  
The data analysis that was done in this dataset was creating consolidated which means common columns betweeen the tables.
common column between the zip and country table is (Location table & Sales table). The common columns between the Maunfactuer ID and Product ID are ( Product table).
Functions was used to bring (state, Maunfactuer name, products name, caterogry, segment) which is INDEX-MATCH functions:

- product name
  = index(product_table[product name], match[product ID], product_table[products ID],0))
  the above function was used to bring all the table into the consolidate table. 

The piovt table was created with some charts such as bar chart, pie chart and line charts.
[Pivot table](https://github.com/Smitholabisi/Excel-Project-/blob/main/Screenshot%20(11).png)


### Recommedation 


The WIXSIN Company Sales Dataset was Analysis and Excel Dashboard created by me. After Analysis this Dataset above, I discovered some the following: 
- The company sales revenue were performing better in catergory like urban and in state like ontario and Alberta.
- More sales strategy should be implemented in the regions, sectors and states not performing very well.
The following sales strategies below should be considered:
- The company can target the low revenue states as well as sectors(Rural, mix and youth) in their Advertisment promotions go forward and also add new products or services that targets their audience.
- Wixsin Company can also give discount on some of their products or services.
- The Company can create a survey form for their customers to fill online or in-store, sometimes that won't take more than 5mins of their customers time.
- They can also do buy one get one half price promotion sales.
- They can also check and study the areas and category doing well by checking the month doing well, in term of weather, seasons and location of stores.
