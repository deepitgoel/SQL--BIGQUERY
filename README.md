# SQL--BIGQUERY
Analysis of Data from database of one of the largest retail chains in America to generate Actionable Insights and Recommendations

## Overview of the dataset
![Untitled](https://user-images.githubusercontent.com/91094796/191203311-561964a1-1353-4812-930a-1cd5fdbba7bf.png)

•	There are 8 tables in the dataset:
i.	Customers: 5 columns and 99441 rows
ii.	Geolocation : 5 columns and 1000163 rows
iii.	order_items : 7 columns and 112650 rows
iv.	payments : 5 columns and 103886 rows
v.	reviews: 6 columns and 99224 rows
vi.	orders: 8 columns and 99441 rows
vii.	products: 9 columns and 32951 rows
viii.	sellers: 4 columns and 3095 rows

•	There are no Null values in any column of Customers, Geolocation, Order items, payments and sellers.
i.	Order_reviews have 87675 nulls in review_comment_title
ii.	Orders have 160 nulls in order_approved_at, 1783 nulls in order_delivered_carrier_date and 2965 nulls in order_delivered_customer_date.
iii.	Products have 610 nulls in product_category, name_length , description_length and photos_qty each and 2 nulls in weight, length, height width each.

## Some questions and their answers based on the analysis:
•	Is there a growing trend on e-commerce in Brazil? How can we describe a complete scenario?
  - We can observe a substantial increase in the number of order per year and also per month of every year except for June and December for 2016. 
  - Number of orders per month in 2018 are less than the previous months of 2017 but total orders are greater. 
  - Therefore we can conclude that there is a growing trend on e-commerce.
  - When observing top 3 most bought product_categories every year we see that there is a trend of buying from Furniture Decoations, Health Beauty and bed table bath categories as compared to other categories.
  -  ![image](https://user-images.githubusercontent.com/91094796/191206174-25829987-30d8-4562-9eab-7244273a74b9.png)
  - ![image](https://user-images.githubusercontent.com/91094796/191206247-daecca1b-fa0d-491a-9e10-aa90e3669366.png)
  - ![image](https://user-images.githubusercontent.com/91094796/191206308-5553decd-28b0-430e-b6ed-552fac23cb8c.png)
  - ![image](https://user-images.githubusercontent.com/91094796/191206269-5593d5bd-4fef-43dd-ad15-762eb301266d.png)
 
•	On what day of week brazilians customers tend to do online purchasing?
  - The Brazilian customers tend to do most online shopping on Monday (1), Tuesday (2) and Wednesday (3) and least on Saturday (7).
  - The sales on weekends, Saturday and Sundays are the least.
  - ![image](https://user-images.githubusercontent.com/91094796/191206047-9090192f-f009-4e80-ac31-7c7373c1b048.png)

•	What time do Brazilian customers tend to buy (Dawn, Morning, Afternoon or Night)?
  - Customers tend to buy most during Afternoon followed by Night. They buy least during the Dawn, which is expected. 
  - ![image](https://user-images.githubusercontent.com/91094796/191206486-e6eae05d-107a-4f1c-8447-76e3a0ada8fc.png)



  

