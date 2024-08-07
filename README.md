### PIZZA SALES ANALYSIS

### Dashboard Link :https://app.powerbi.com/groups/me/reports/82eabe1b-0d42-4977-8ece-2accf8e0ebdc/ReportSection2681df53ecf6c16d5dec?experience=power-bi

## STATEMENTS 
 
This dashboard helps the Go-Pizzas understand their customers better. It helps the Business owners understand different patterns and trends in the sales of pizzas through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. 

This Analysis was able to look into the several KPIs which includes 

- Total revenues
- Total Orders and the Order Value
- Avearge Order per day
- Average Pizzas Per Order
- Total Quantity of Pizzas sold  

This Dashbaord was succesfully able to answer detailed questions which includes 
- How many customers bought pizza in a day
- Peak Hours for most pizza sales
- Peak days for most pizza sales 
- Best Selling Pizzas
- Worst Selling Pizzas
- Total Revenue Generated by Size 
- Total Revenue Generated by Size 



## DATA MODELLING

Automatically Derived relationships are adjusted to remove and replace unwanted relationships with the required 

- Date
- Year
- Month No
- Month Name
- Quarter
        
Snap of new calculated table ,

![tABLE](https://github.com/Emmanuel-GO/gotech/assets/106073701/d625138b-7999-4611-8143-b207687180d5)


Hence Our Data Model looks like this
![MODEL](https://github.com/Emmanuel-GO/gotech/assets/106073701/9f21421e-561e-4c0e-8dae-7d474bf9d4a1)


        
Different measures was created to find 

- Total Revenue 

Following DAX expression was written to find Total Revenue
        
     Total Revenue = SUM('Order Details'[Total Price])
        
A card visual was used to represent Total Revenue.

![Measures](https://github.com/Emmanuel-GO/gotech/assets/106073701/6d1ed6bb-1fc1-4f04-a83a-843d678d1874)

        
- Total Orders

 Following DAX expression was written to find Total Orders
 
        Total Orders = DISTINCTCOUNT('Order Details'[order_id])
 
 A card visual was used to represent this Total Orders
 
![Measures 1tr](https://github.com/Emmanuel-GO/gotech/assets/106073701/e3836d4e-e88d-48ad-bf41-5b0b8a96ae6c)

 
 - New measure was created to calculate Average Order Value
 
 Following DAX expression was written to find Average Order Value,
 
         Average Order Value = DIVIDE([Total Revenue],[Total Orders])
    
 A card visual was used to represent this Average Order Value
 
 ![Measures 1acfgg](https://github.com/Emmanuel-GO/gotech/assets/106073701/ed9cf017-3f7d-48dc-8cd2-21147335bc63)

 

 
![Publish_Message](https://user-images.githubusercontent.com/102996550/174094520-3a845196-97e6-4d44-8760-34a64abc3e77.jpg)

# Snapshot of Dashboard 

![MY_PIZZA_PROJECT 1 ,mk_page-0001](https://github.com/Emmanuel-GO/gotech/assets/106073701/f3384501-d2b7-4061-9a54-45db8a2cd89a)




# Insights

Based on the key performance indicators (KPIs) provided in the analysis, several important insights
can be derived which can help stakeholders gain valuable insights into the business's performance,
customer behavior, and areas for improvement. These insights can inform strategic decision-making
and help drive growth and profitability in the pizza business. Below are insights and
recommendations:

- Revenue Trends:
The monthly revenue trend shows that July is the peak month for revenue, followed by March and
November. This insight suggests that there are certain seasonal trends in pizza sales that should be
considered for planning and resource allocation.

- Order Patterns:
Fridays are the peak days for orders, and the peak times for orders are between 12 PM to 1 PM on
weekdays and 5 PM to 8 PM on weekends. Understanding these order patterns can help optimize
staffing and resource allocation to meet customer demand during peak hours.

- Category Performance:
The analysis highlights that the Classic category generates the most revenue, followed by Supreme
and Chicken. This insight can inform marketing and promotional strategies to further capitalize on
the popularity of these categories.


- Size Preferences:
Large pizzas generate the highest revenue, followed by medium and small sizes. Understanding size
preferences can help optimize inventory management and pricing strategies to maximize profitability

   Top and Worst Selling Pizzas:
The top-selling pizzas by revenue are Thai_ckn, Bbq_ckn, Call_Ckn, Classic_dix, and Spicy_ital.
Conversely, the worst-selling pizzas by revenue are Brie_carre, Green_garden, spinach_super,
mediterraneo, and spin_pesto. This insight can inform product development and marketing
strategies to promote top-selling pizzas and improve the performance of low-performing ones.


-  Average Order Metrics:
The average order value is $38.31, and the average number of pizzas per order is 2.32. These metrics
provide insights into customer behavior and spending patterns, which can inform pricing strategies
and promotions to increase average order value and encourage customers to add more items to their orders.
           
# Recommendations

-  Increase Average Order Value:
The average order value is $38.31. To increase this metric, consider implementing upselling or cross-
selling strategies to encourage customers to add more items to their orders. This could include
promoting combo deals, add-ons, or higher-priced items.

- Improve Average Pizza per Order:
The average number of pizzas per order is 2.32. Encouraging customers to add more pizzas to their
orders can help increase this metric. Offering bundle deals or incentives for ordering multiple pizzas
may be effective strategies.

- Promote Low-Performing Pizza Varieties:
Identify and promote the low-performing pizza varieties such as Brie_carre, Green_garden,
spinach_super, mediterraneo, and spin_pesto. Consider running targeted marketing campaigns or
special promotions to increase sales of these pizzas.

- Optimize Size Mix:
Analyse the revenue generated by different pizza sizes and identify opportunities to optimize the size
mix. For example, if large pizzas are generating the most revenue, consider promoting them more
prominently or adjusting pricing to encourage more sales of other sizes.

- Enhance Sales on Off-Peak Months:
Focus on increasing sales during the off-peak months, particularly September and October. Consider
running promotions, launching new menu items, or implementing loyalty programs to attract
customers during slower periods.

- Improve Efficiency During Peak Times:
Since Fridays and lunchtime during weekdays are peak times for orders, ensure that operations are
optimized to handle increased demand efficiently. This may involve streamlining processes, staffing
appropriately, and ensuring sufficient inventory levels.

- Diversify Product Offerings:
Explore opportunities to expand the product offerings to attract a wider range of customers. This
could include introducing new pizza varieties, offering specialty items, or catering to dietary
preferences such as vegetarian or vegan options.

-  Enhance Customer Experience:
Focus on improving the overall customer experience to encourage repeat business and increase
customer loyalty. This may involve providing exceptional customer service, ensuring prompt delivery
times, and soliciting feedback to address any areas for improvement.
