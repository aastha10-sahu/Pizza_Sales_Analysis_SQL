# Pizza_Sales_Analysis_SQL

Basic Questions:

1. Retrieve the total number of orders placed.


**<img width="292" alt="Basic 1" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/a1204e89-c8e6-43c4-9011-83c715afe9c6">
**


The result we got were:- 

**<img width="86" alt="Result B1" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/fec8d220-09fa-4542-afb1-f70b1c5af35d">
**

2. Calculate the total revenue generated from pizza sales.


**<img width="355" alt="Basic 2" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/0b804964-826c-454b-957a-ebf3fb53e841">
**

The result we got were:-

**<img width="85" alt="Result B2" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/c774a2c4-6fb0-4feb-ae7d-5758fa59480f">
**

3. Identify the highest-priced pizza.


**<img width="388" alt="Basic 3" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/abd16ddc-9605-4bed-b6be-c14aef02d4db">
**

The result we got were:- 

**<img width="133" alt="Result B3" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/7f33b14c-889a-4e0e-a0ce-14449d743e4a">
**

4. Identify the most common pizza size ordered.

**<img width="379" alt="Basic 4" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/8ad5f578-1d8f-4a92-9dd3-6e6170c501e1">
**

The result we got were:- 

**<img width="112" alt="Result B4" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/01f32d52-1c24-47a5-9824-33f676895d77">
**

The chart shows that large is the most popular size, with 18,526 pizzas sold.  Medium pizzas are the second most popular, with 15,385 sold.  Small pizzas are the third most popular, with 14,137 sold. Extra large pizzas are not very popular, with only 544 sold.  Extra extra large pizzas are the least popular, with only 28 sold.


5. List the top 5 most ordered pizza types along with their quantities.

**<img width="377" alt="Basic 5" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/ac7ee01a-b499-4bde-8564-d67c3f14bc80">
**

The result we got were:- 

**<img width="183" alt="Result B5" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/4942d7d9-b06f-4e68-be6d-7c2b6d32e15a">
**

The table shows "The Classic Deluxe Pizza" was the most popular pizza, with 2453 pizzas sold. "The Barbecue Chicken Pizza" was the second most popular at 2432, followed by "The Hawaiian Pizza" at 2422.  These were the only pizzas to sell over 2400.



Intermediate Questions:

1. Join the necessary tables to find the total quantity of each pizza category ordered.

**<img width="389" alt="Inter 1" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/c081a473-cdbf-400b-8d72-f9c7cfecd76f">
**

The result we got were:- 

**<img width="116" alt="Result I1" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/1b8a886c-693e-41d9-9646-a249599416f3">
**

Classic: 14888
Supreme: 11987
Veggie: 11649
Chicken: 11050
Classic pizzas are the most popular category, with nearly 15,000 pizzas sold. It is followed by Supreme, Veggie, and Chicken pizzas.


2. Determine the distribution of orders by hour of the day.

**<img width="365" alt="Inter 2" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/001e0bb0-63d7-4478-8fb5-9b5647b81b2e">
**

The result we got were:- 

**<img width="117" alt="Result I2" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/39f40ab9-fac7-4f03-b15a-82477509a1da">
**

According to the table, 8 orders were placed at 9 am and 1231 orders were placed at 11 am.  Lunchtime seems to be the busiest time for orders, with the most orders placed between 11 am and 2 pm. There is a significant drop in orders in the late afternoon and evening hours.


3. Join relevant tables to find the category-wise distribution of pizzas.

**<img width="258" alt="Inter 3" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/5ba2cd7e-f7ca-486f-a93b-13b9a0925278">
**

The result we got were:- 

**<img width="137" alt="Result I3" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/c428b217-25ef-4ee1-9df2-d3c60fc1e247">
**

This data suggests that Supreme and Veggie pizzas are the most popular categories, each with 9 pizzas sold. Classic pizzas follow closely behind with 8 pizzas sold, while Chicken pizzas are the least popular category, with only 6 pizzas sold.


4. Group the orders by date and calculate the average number of pizzas ordered per day.

**<img width="398" alt="Inter 4" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/facc7e8e-0274-4579-84a3-9abf93806446">
**

The result we got were:- 

**<img width="146" alt="Result I4" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/750a590e-d8ed-417d-a5f0-f1a8c903de11">
**

The average number of pizzas ordered per day is 138 pizzas. 


5. Determine the top 3 most ordered pizza types based on revenue.

**<img width="391" alt="Inter 5" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/2412cd3b-73b5-4832-8efc-35fa91b8e233">
**

The result we got were:- 

**<img width="185" alt="Result I5" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/452095b3-e182-4db7-803a-97f0589618c4">
**

The table shows that the Thai Chicken Pizza was the most popular pizza, generating $43,434.25 in revenue. The Barbecue Chicken Pizza was the second most popular at $42,768, followed by the California Chicken Pizza at $41,409.50.


Advanced Questions:- 

1. Calculate the percentage contribution of each pizza type to total revenue.

**<img width="452" alt="Advanced 1" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/c2d56445-8f19-437d-b9e4-eb5db6325d4f">
**

The result we got were:- 

**<img width="121" alt="Result A1" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/81f3bd69-19b1-4999-876d-b8bd4ff9905f">
**

Classic pizzas contribute 26.91% to the total revenue. Here's a breakdown of the percentage contribution of each pizza type listed in the table:

Classic: 26.91%
Supreme: 25.46%
Chicken: 23.96%
Veggie: 23.68%


2. Analyze the cumulative revenue generated over time.

**<img width="341" alt="Advanced 2" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/5c11a8e2-6174-4749-a4bb-8bc4781ccf40">
**

The result we got were:- 

**"C:\Users\AASTHA\OneDrive\Desktop\SQL pizza sales Project\Screenshots\Result A2.csv"**


3. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

**<img width="381" alt="Advanced 3" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/08f464a0-5276-4c13-9fef-17126ce8a8d7">
**

The result we got were:- 

**<img width="227" alt="Result A3" src="https://github.com/aastha10-sahu/Pizza_Sales_Analysis_SQL/assets/152705482/ccbd17c0-f26c-4637-bc43-e7470128937f">
**

The table shows that the top 3 revenue generating pizzas in the Chicken category are:

Thai Chicken Pizza: $43434.25
Barbecue Chicken Pizza: $42768
California Chicken Pizza: $41409.50
