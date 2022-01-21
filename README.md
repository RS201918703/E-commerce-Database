# An Insight into an E-Commerce Database 
### Overview and motivation
We wanted to mimic a database of a huge e-commerce site like Amazon. We identified how a huge database like Amazon's could be broken down into operations and insights. We decided to focus on the insights portion because there is more room to interpret results. So, this database serves both customers and producers with insights into products. Our final product was our query outputs. This is an academic project for ST207.

![Image1](https://github.com/RS201918703/ST207-Database-Project/blob/main/figs/DBBrowser%20fig.png)

### Description
The entire project was written with SQLite on DBBrowser. We established a connection from our ST207Database.ipynb file to do this. The dataset here has already been cleaned before inserting into the database, you can find the original dataset here: https://app.datastock.shop/?site_name=Amazon.com_Product_Reviews (You will need an account to download this). We have also added additional data from here: https://www.kaggle.com/promptcloud/amazon-product-reviews-dataset

### How to run
- Run the code in ST207Database.ipynb on Google Colab
- Before running, import amazon.csv into the environment

### Improvements
- Deletion rules: Realistically, the database should've allowed for deletions. Especially for ethical reasons, customers may not want their data stored there forever to be used by others
- Extra restrictions: For instance, in the Products table, a restriction to ensure Categories and Subcategories would have been useful
- Dropping information: For the database to work, we had to drop a lot of data with NULL values. But in reality, data often have these kinds of gaps and an improvement we could've made is to find another way to work around it
- Reviews interpretations: We could have scanned through review contents to make new analyses 

### Conclusion
With our initial goal in mind, our database did a good job at serving customers and producers with insights. Evidence is shown in all the query outputs. However, we did see that there were a couple of things that would become a problem if brought into a real-life setting.

### Team members
- Chris Twomey: https://github.com/christwm201914523
- Rafay Butt: https://github.com/raf201920011

### References
1. [Database designing](https://thedigitalskye.com/2020/12/19/8-practical-guidelines-for-designing-databases-that-dont-land-you-in-hot-water/)
2. [Entity-relationship modelling](https://www.guru99.com/er-diagram-tutorial-dbms.html)
3. [SQL Rank functions](https://www.sqlshack.com/overview-of-sql-rank-functions/)
4. [An explanation of view](https://www.sqlshack.com/sql-view-a-complete-introduction-and-walk-through/)
5. [Pandas Dataframes](https://pandas.pydata.org/docs/reference/api/pandas.read_sql_query.html)
6. [Subqueries](https://mode.com/sql-tutorial/sql-sub-queries/)
