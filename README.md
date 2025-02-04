<p align="center"><img src= "https://www.roberthilllaw.com/wp-content/uploads/sites/1101645/2013/08/big-box-store.jpg" alt ="trends" style='width:600px;'></p>


# 🎯 Superstores Sales Report  #


In this project I will be using Python (for EDA, predictive analysis) and Power BI to show several information of the Store orders made in four consecutive years from different countries.

---
# 🎯 Context #

A superstore is a very large store often offering a wide variety of merchandise for sale. Superstores typically charge anywhere from 15 to 45 percent less than their smaller counterparts. 
As the decision maker for a superstore company, we will give some insights into what works best to understand which products, regions, categories, and customer segments they should target or avoid.

We will try to find out the weak areas and see where Superstores can make more profit.
Using the dataset, we will also do an EDA and try to build a Regression model to predict Sales or Profit.

The dataset will include Products,Sales, Profit, Country, Region and all sales order details for reporting.

---
# 🎯 Use #

* The data will be used to help management decide which stores are performing well and which are underperforming based on sales and profits.

---

# 🎯 Objective #

* To investigate the top performing products and countries, as well as the factors influencing performance.
* Analyzing top 10 consumer countries. 
* Analyzing top 10 counsumer countries orders as per categories and sub-categories.
* Analyzing the top products of the Top 10 countries as per Coustomer Segment.
* Growth Over the years.
* Show the customer segment in each market.
* Various Analysis:

    1. Analysis of various business entities like :
    - Customer Analysis.
    - Sales Analysis.
    - Order Analysis.
    - Product Analysis etc.
    
    2. Analysis of the above entities across dimensions like :
    - Time Hierarchy.
    - Geographical Hierarchy.
    - Product Hierarchy etc.
    
    3. Analysis of KPIs (Key Performance Indicators) like :
    - Sales.
    - Profits.

---

# 🎯 Scope of this project #

1. Data Preparation
    *  This includes data cleansing. In this project the data was not that clean and to be able to have a good visual presentation and analysis we need to make sure we have a clean data in our database. 
    
    * I have encountered that the state column has a special character, and in order for me to fix it I have saved the csv file again and used utf-8 before importing it again to our database.

2. Create Dimensions
    * As a rule, it would be best to create an appropriate dimension that follows the Dimensional Modeling Techniques by Kimbal. These guide helped me in creating a solid dimension for this project. 
    
   [Kimball Dimensional Modeling Technique] 
   (https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques/dimensional-modeling-techniques/)
   
   * Upon creating the dimensions I used some simple techniques in SQL and used case statements, and CTEs. I made sure that each dimension will have a unique Identifier or ID to be included in our Fact table which will only contain numbers. This will help us make a good star schema design.
   
 3. Visualization
    * I'm using Jupyter Notebook to create a simple Visualization that will show how to answer the objectives we aimed.
    * I also used power BI to have a more interactive report that shows the objectives we want to answer.
    
    <p align="center"><img src= "![Alt text](gifs/PowerBI%20Snipet.gif)" alt ="trends" style='width:600px;'></p>

    
    



---

# 🎯 About the Data #

* Original Dataset source: https://www.kaggle.com/datasets/aditisaxena20/superstore-sales-dataset
* Superstore definition: https://www.merriam-webster.com/dictionary/superstore#:~:text=%3A%20a%20very%20large%20store%20often,variety%20of%20merchandise%20for%20sale
* Superstores/Bigbox stores by country: https://en.wikipedia.org/wiki/List_of_superstores



