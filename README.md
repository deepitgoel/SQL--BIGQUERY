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

## ACTIONABLE INSIGHTS
•	Though the total orders in 2018 are more than 2017, there is a decrease in monthly no. of orders in 2018 against the steady increase observed in the 2017.
•	For 2017 and 2018 we observe after top 7 categories, by sales, the sale is very less for all other categories. Also some categories are redundant with respect to some other, broader categories for example:  Furniture- Room furniture, Art-Art and craft etc.
•	The sales on weekends is least compared to the week days.
•	There is a sharp gap between sales for dawn-morning and afternoon-night time.
•	A heavy majority of orders are from SP state. There is a higly significant difference in orders from other states compared to SP.
•	Similar scenario exists for cities with Sao Paulo have very high orders in comparison to other cities.
•	Though most orders being from SP the highest mean price of order is of PB.
•	Highest mean freight is of RR despite having very low orders and total price along with the longest mean time to delivery. These factors might be a reason for low sales in this state.
•	SP has lowest mean freight value along with fastest average time to delivery , which evidently is a factor for SP having highest sales.
•	Customers heavily prefer credit cards for payments compared to other modes. 
•	A very high percentage of orders have 1 payment installment and only 2 orders have zero installments implying customers are more inclined towards paying for orders in 1 installment

## Recommendations 
•	Find the factors responsible low monthly orders in 2018.
•	Redefine the categories with sub categories for better categorization and tracking.
•	Providing special discounts or offers specifically targeting the low selling categories.
•	Any new launches / schemes / programs must be organized in afternoon/ night due to higher activity during this period.
•	Sale days / offers may start at dawn to increases orders during that time.
•	A deeper study is required for the factors that are resulting in very high sales in specific state/city and very low in others. After that only any valid recommendations can be made.
•	A strategy needs to be developed to reduce time to delivery and the freight values, to attract more customers.
•	Due to higher preference to credit cards, some loyalty programs may be planned in collaborations with card companies to expand the customer base.


  

