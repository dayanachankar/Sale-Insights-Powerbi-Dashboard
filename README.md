# Sale Insights Data Analysis Project
## Data Analysis Using SQL
#### 1.Show all customer records
SELECT * FROM customers;
#### 2.Show total number of customers
SELECT count(*) FROM customers;
#### 3.Show transactions for Chennai market (market code for chennai is Mark001
SELECT * FROM transactions where market_code='Mark001';
#### 4.Show distrinct product codes that were sold in chennai
SELECT distinct product_code FROM transactions where market_code='Mark001';
#### 5.Show transactions where currency is US dollars
SELECT * from transactions where currency="USD"
