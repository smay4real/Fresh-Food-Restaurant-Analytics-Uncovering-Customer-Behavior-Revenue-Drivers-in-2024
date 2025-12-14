# Fresh-Food-Restaurant-Analytics-Uncovering-Customer-Behavior-Revenue-Drivers-in-2024

<img width="1200" height="534" alt="1_jJZUmb5QdhWTiVcAmZ7GfA" src="https://github.com/user-attachments/assets/9dccc2fe-a7e9-4e19-8920-fe5cadfb2fba" />


Introduction
In the competitive landscape of the restaurant industry, data-driven decision-making has become paramount to success. This portfolio project presents an in-depth analysis of Fresh Food Restaurant’s operations for the year 2024, examining customer behavior, revenue patterns, and operational efficiency across five major restaurant chains: Subway, Pizza Hut, KFC, Burger King, and McDonald’s operating in Pakistan’s major cities.

The analysis leverages a comprehensive dataset of 6,000 customer transactions spanning multiple dimensions including demographics, order patterns, payment preferences, delivery performance, and customer satisfaction metrics. This project demonstrates end-to-end data analytics cap abilities from data exploration to actionable business insights.

The Data Story
The Setting:
Fresh Food Restaurant operates across five major Pakistani cities: Multan, Lahore, Peshawar, Islamabad, and Karachi, representing diverse demographic and cultural markets. With a portfolio of five renowned restaurant brands, the company serves a wide customer base ranging from teenagers to seniors.

The Numbers That Matter
Total Revenue Generated: $4.8 Million
Customer Base: 6,000 unique customers
Order Volume: 6,000 transactions
Geographic Footprint: 5 major cities
Restaurant Brands: 5 (Subway, Pizza Hut, KFC, Burger King, McDonald’s)
Menu Diversity: 5 categories (Italian, Fast Food, Continental, Chinese, Dessert)
The Challenge
Despite impressive revenue figures, the business faces critical challenges:

Alarming Churn Rate: 49.7% customer inactivity
Delivery Concerns: Only 34.3% successful delivery rate
Customer Satisfaction: Average rating of 3.01/5.0
Missing Feedback: 32.8% of orders lack customer ratings
These metrics paint a picture of a business at a crossroads, strong revenue potential tempered by operational and customer retention challenges.

WHAT SUCCESS MEANS TO THE COMPANY

What success means to this restaurant are High customer ratings on dishes and service, Strong sales across restaurants and food categories, Repeat orders and loyal customers with high points, Low churn rate (few customers leaving), Fast and reliable deliveries and Growth in new signups and order frequency over time.

Objective of the Project
Revenue Analysis: Identify top-performing restaurants, cities, and menu categories driving revenue
Customer Behavior Profiling: Understand ordering patterns across demographics (age, gender, location)
Operational Efficiency Assessment: Evaluate delivery performance and identify bottlenecks
Churn Reduction Strategy: Analyze factors contributing to customer inactivity
Customer Satisfaction Optimization: Investigate rating patterns and satisfaction drivers
Methodology
1. Data Collection & Understanding
Approach: Comprehensive exploration of the dataset structure, dimensions, and business context

Activities:

Loaded Excel dataset containing 6,000 records with 20 features
Identified primary entities: Customers, Orders, Restaurants, Menu Items
Documented feature definitions and business rules
Reviewed dashboard visualizations for business context
Tools: Excel

2. Data Cleaning & Preprocessing
Approach: Systematic data quality assessment and transformation

Activities:

Missing Value Treatment:
Analyzed 1,968 missing ratings (32.8%)
Decision: Retain for delivered orders analysis, flag for follow-up
Data Type Conversions:

Convert date columns to datetime format
Standardize categorical variables
Ensure numeric fields are properly typed
Outlier Detection:

Validate price range ($100.30 — $1,499.95)
Check order frequency distribution (1–50 orders)
Identify anomalous rating dates (2025 entries)
Data Standardization:

Normalize city names
Standardize category labels
Consistent status classifications
Tools: Excel.

 

Data Splitting Strategy
Given the nature of this dataset (cross-sectional snapshot rather than time series), traditional train-test splits for predictive modeling aren’t the primary focus. However, for various analytical purposes, here’s the proposed data segmentation:

1.Category One: Independent Values

Gender

Age

City

Restaurant_name

Dish_name

Category

Churned

Customer_id

Delivery_status

Price

Signup_date

Rating_date

Order_id

Order_date

Payment_method

Last_order_date

2. Category Two: Dependent Values

Quantity

Order_frequency

Loyalty_points

Rating

 

POTENTIAL ANALYSIS / QUESTIONS

1. How does order frequency vary by city?

2. Does customer loyalty (loyalty points) impact churn rate?

3. Which payment method is most popular among customers?

4. How does rating vary by category of dishes?

5. Is there a correlation between order quantity and price?

6. Do customers from different cities have different preferences for dishes?

7. How does delivery status impact customer churn?

8. Which restaurant has the highest average rating?

9. Is there a seasonal trend in order frequency?

10. Does customer age impact order frequency or quantity?

 

POTENTIAL INSIGHT

1. Certain cities have significantly higher or lower order frequencies, indicating potential differences in customer behavior or market saturation.

2. Customers with higher loyalty points are less likely to churn, suggesting that the loyalty program is effective in retaining customers.

3. The majority of customers prefer a specific payment method, which could inform payment processing decisions and user experience improvements.

4. Certain categories of dishes receive higher or lower ratings, indicating potential areas for improvement or opportunities for differentiation.

5. There is a positive or negative correlation between order quantity and price, which could inform pricing strategies and menu engineering.

6. Customers from different cities have distinct preferences for certain dishes, which could inform targeted marketing and menu customization.

7. Customers who experience issues with delivery status are more likely to churn, highlighting the importance of reliable logistics and communication.

8. Top-rated restaurant: One restaurant consistently receives high ratings, which could inform quality control and customer satisfaction initiatives.

9. Seasonal ordering trends: Order frequency varies by season, which could inform marketing campaigns, inventory management, and staffing decisions.

10. Age-related ordering habits: Customer age is correlated with order frequency or quantity, which could inform targeted marketing and menu development strategies.

 

IN-ANALYSIS:


1. CITY BY REVENUE — Pie Chart

<img width="752" height="452" alt="1_zbRiIrCTYfjFFHLHlYF54Q" src="https://github.com/user-attachments/assets/4b92cfbe-69c9-4f47-a2ed-ce2b79454693" />


Observation:

1. Multan leads with $1,009,003.67 (highest revenue)

2. Peshawar follows at $985,111.46

3. Lahore generates $965,086.48

4. Islamabad produces $943,770.85

5. Karachi has the lowest at $900,176.82

6. Revenue spread: $108,826.85 difference between highest and lowest

Pre-Insights:

- Despite being a smaller city, Multan outperforms major metropolitan areas like Karachi and Lahore, suggesting strong local market penetration or higher customer spending

- The relatively tight clustering 10.8% variation indicates balanced market performance across cities

Karachi’s underperformance presents growth opportunity given its large population base
 

 2. RESTAURANT REVENUE PERFORMANCE— Donut Chart


<img width="750" height="452" alt="1_Ke-U2Ins7Oj7MCK70_jUOg" src="https://github.com/user-attachments/assets/ba8d333d-2b25-4cb9-9e9a-2656b5d3978b" />


Observations:

1. Subway dominates with $1,009,983.25

2. KFC follows at $989,184.73

3. Pizza Hut close behind at $988,412.17

4. Burger King generates $913,130.23

5. McDonald’s lowest at $902,438.90

6. Revenue gap: $107,544.35 between leader and last

Pre-Insights:

- Subway’s leadership suggests successful menu diversification and health-conscious positioning

- KFC and Pizza Hut are virtually tied, indicating intense competition in this segment

- McDonald’s underperformance is surprising given global brand strength, suggesting local market adaptation issues

 

3. ORDER FREQUENCY PER AGE - Column Chart


<img width="752" height="452" alt="1_BYU1n3Z50zuGcrulgqhD6w" src="https://github.com/user-attachments/assets/2e514df0-1f51-453c-ba2f-7d0e3ad8e6f0" />

Observations:

1. Teenagers lead with 51,783 orders

2. Adults follow with 50,172 orders

3. Seniors at 49,873 orders

4. Total order spread: 1,910 orders (3.8% variation)

5. Relatively even distribution across age groups

Pre-Insights:

- Teenagers’ slight lead aligns with higher digital adoption and food delivery usage

- Even distribution suggests broad market appeal across demographics

The narrow gaps indicate potential for targeted campaigns to boost engagement in adult and senior segments
 

4. RESTAURANT NAME BY CATEGORY —  Bar Chart

<img width="606" height="382" alt="1_AyhZAyrltgomk-95Fu2OzQ" src="https://github.com/user-attachments/assets/9fd7060d-6978-4c9a-85fc-b54f734deec9" />

Observations:

1. Subway offers 1,260 categories (most diverse)

2. Pizza Hut and KFC tied at 1,224 categories each

3. Burger King provides 1,151 categories

4. McDonald’s has 1,141 categories (least diverse)

5. Range: 119 categories difference between most and least diverse

Pre-Insights:

- Menu Strategy: Subway’s category leadership reflects its customizable sandwich model and diverse offerings

- Standardization vs. Variety: McDonald’s lower category count suggests focus on standardized, efficient operations

Competition Parity: Pizza Hut and KFC’s identical counts may indicate similar market positioning strategies
 

5. SALES BY CATEGORY — Column Chart


<img width="641" height="382" alt="1_hJnC2oe-2WM2m3FhYIwnXw" src="https://github.com/user-attachments/assets/8ebdba00-a0f1-490f-ad27-229e891aa455" />

Observations:

1. Italian cuisine leads at $1,005,523.03

2. Continental follows at $972,879.11

3. Fast Food generates $969,636.78

4. Chinese cuisine at $965,982.53

5. Dessert lowest at $889,127.83

6. Revenue spread: $116,395.20 between highest and lowest categories

Pre-Insights:

- Premium Positioning: Italian cuisine’s leadership suggests customers willing to pay premium for perceived quality

- Market Saturation: Close clustering of Continental, Fast Food, and Chinese indicates competitive equilibrium

- Growth Opportunity: Dessert category’s lower performance suggests potential for menu expansion or marketing focus

 

6. CHURN RATE BY CITY  — Stacked Bar

<img width="528" height="382" alt="1_Po1cZ9kiRa93DxAQDHJY-A" src="https://github.com/user-attachments/assets/a99157d9-786b-44ad-8e54-2526b973df65" />

Observations:

1. Peshawar: Only city with more active (623) than inactive (572) customers

2. Multan: 608 active vs 648 inactive

3. Lahore: 586 active vs 631 inactive

4. Islamabad: 602 active vs 585 inactive

5. Karachi: 597 active vs 548 inactive

Pre-Insights:

- Market strength: Peshawar’s positive active-to-inactive ratio indicates strong customer retention and market strength

- Retention Challenge: Most cities show higher churn, suggesting need for improved customer retention strategies

Regional Variations: City-specific factors influencing retention require localized approaches
 

7. PAYMENT METHOD BY LOYALTY — Bar Chart

<img width="528" height="382" alt="1_wsw8jGiK6ETBNa6MJ_MwBg" src="https://github.com/user-attachments/assets/836bd4f8-364f-4b27-a860-12f6cba68975" />


Observations:

1. Cash payments show highest loyalty: 506,474

2. Wallet payments: 499,354

3. Card payments lowest: 495,214

4. Difference: 11,260 between highest and lowest (2.2% variation)

Pre-Insights:

- Traditional Preference: Cash loyalty leadership suggests customer comfort with traditional payment methods

- Digital Adoption: Close clustering indicates successful digital payment integration without alienating cash users

Market Maturity: Small variations suggest payment method doesn’t significantly impact loyalty


8. DELIVERY STATUS BY DISHES — Stacked Bar

<img width="526" height="382" alt="1_c-N4mhWmWMToQUSSc_FODg" src="https://github.com/user-attachments/assets/e25d51ac-9c76-41a2-92c4-55ef2671f11a" />


Observations:

1. Pasta: 443 delivered, 412 cancelled, 407 delayed

2. Sandwich: 426 delivered, 418 delayed, 399 cancelled

3. Pizza: 398 delivered, 407 cancelled, 395 delayed

4. Fries: 403 delivered, 378 delayed, 371 cancelled

5. Burger: 390 delivered, 379 cancelled, 374 delayed

Pre-Insights:

- Operational Excellence: Pasta shows best delivery success rate, suggesting efficient preparation/delivery processes

- Challenge Items: Pizza has highest cancellation rate, possibly due to preparation complexity or demand forecasting issues

Service Optimization: Relatively balanced status distribution across dishes indicates consistent operational challenges requiring systematic improvement.
 

POST ANALYSIS : OBSERVATIONS AND RECOMMENDATION

OBSERVATIONS

•Pasta has the highest number of delivered orders (443), followed closely by Sandwich (426).

•Fries record the lowest delivery figures (403 delivered), indicating lower preference compared to other dishes.

•Cash is the most used payment method (506,474), slightly ahead of wallet (499,354) and card (495,214).

•Teenagers are the highest order frequency group 51,783, higher than adults 50,172 and seniors 49,873.

•Italian dishes generate the highest revenue of $1,005,523.03, followed by Continental with $972,879.11.

•Desserts generate the lowest sales revenue $889,127.83.

•Subway is the most popular restaurant (1,260 orders), followed by Pizza Hut and KFC (1,224 each).

•McDonald’s has the lowest order count (1,141) among the listed restaurants.

•Multan generates the highest revenue by city ($1,009,003.67), while Karachi has the lowest ($900,176.82).

•Subway contributes the highest revenue ($1,009,983.25) among restaurants.

•McDonald’s generates the least revenue ($902,438.90).

•Churn rate is highest in Multan (648 inactive customers), showing a high risk of losing customers despite strong revenue.

•Lahore shows lower churn inactivity (631) compared to Multan, though still significant.

•Islamabad and Karachi show relatively lower churn inactivity (585 and 548), suggesting more stable customer loyalty.

•Across cities, active customers are almost equal to inactive customers, highlighting an ongoing churn management challenge.

 

RECOMMENDATIONS

Short-Term Recommendations (Quick Impact):

•Promote Fries and Burger deals to quickly increase their popularity.

•Introduce combo meals or discounts on low demand items like Fries.

•Encourage more digital payments through wallet/card cashback offers.

•Youth-focused loyalty programs targeting teenagers (top ordering group).

•Introduce health-conscious menu options for adults and seniors.

• dessert sales with new flavors, limited-time offers, and bundling.

•Support McDonald’s and Burger King with targeted promotions to increase volume.

•Conduct customer satisfaction surveys to detect churn causes in Multan and Lahore.

Long-Term Recommendations (Strategic Impact):

•Expand Subway’s delivery reach and strengthen its market leadership.

•Invest more in Italian and Continental dishes, leveraging their high revenue performance.

•Implement customer retention strategies in Multan and Lahore (loyalty bonuses, reactivation discounts).

•Re-engage inactive customers with personalized rewards programs.

•Increase revenue in Karachi by expanding marketing campaigns and delivery network.

•Maintain consistent quality assurance and delivery efficiency across all cities.

Develop an integrated churn management system to continuously track and reduce inactive customers.
Conclusion: The Path Forward
Fresh Food Restaurant stands at a critical juncture. The business has achieved initial success in revenue generation and market presence, but operational weaknesses threaten long-term viability.

The Good News: All identified issues are solvable. Delivery operations, churn prevention, and satisfaction improvement are well-understood problems with proven solution playbooks.

The Challenge: Requires sustained focus, investment, and organizational commitment. No silver bullet, must execute across multiple fronts simultaneously.

The Opportunity: Fixing these fundamentals will not only stabilize the business but position Fresh Food as category leader. In a market where everyone struggles with delivery and retention, the company that solves it first wins disproportionate market share.

Success Scenario (18 months):

Delivery success: 85%+

Churn rate: <20%

Average rating: >4.0

Revenue: $8M+ (67% growth)

NPS: >40 (promoter territory)

Market position: #1 or #2 in each city

This is achievable. The data shows the problems clearly. The recommendations are actionable. The market opportunity is real. Now it is all about execution.


Final Thought: 

In restaurant business, consistency is the ultimate competitive advantage. Customers will choose reliable mediocrity over unreliable excellence every time. Fresh Food must become boringly consistent in delivering good experiences. That’s how trust is built, loyalty is earned, and sustainable businesses are created.

 

Project Completed: December 2025
Analyst: Isau A. Shittu
Portfolio Project: Fresh Food Restaurant Business Analytics
Contact: Teejaypumpey@gmail.com
