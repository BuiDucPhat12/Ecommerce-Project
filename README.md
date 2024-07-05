# Ecommerce-Project
Using Big Query platform to solves problems such as Data mining and Data exploration, joining data from separate spreadsheets on Ecommerce data.
## 1: Introduction
### 1.1: Google Bigquery
In the realm of modern data analytics, leveraging robust platforms like Google BigQuery has become indispensable for organizations aiming to extract actionable insights from vast datasets. BigQuery, a fully managed data warehouse solution on the cloud, offers unparalleled scalability and speed, making it ideal for complex data mining and exploration tasks.
### 1.2: Dataset
dataset includes 1 public table ga_sessions_20170801 on Bigquery
Fields that need attention
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/d505727b-35ff-4228-a0bc-9d2d0408c592)
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/dfb18df7-e397-4974-aac3-22ba4c30d49b)

### 1.3: Question and Result
1. calculate total visit, pageview, transaction for Jan, Feb and March 2017 (order by month)
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/b5655248-cfd1-4085-9878-72f326786262)

2. Bounce rate per traffic source in July 2017 (Bounce_rate = num_bounce/total_visit) (order by total_visit DESC)
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/1a0e1651-1729-4f09-a462-7ca283498e86)

3. Revenue by traffic source by week, by month in June 2017
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/9239e12d-7db1-4454-bf96-bda63fcfec04)

4. Average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/a10be902-e838-4ed9-b23c-dcbdd0279fc2)

5. Average number of transactions per user that made a purchase in July 2017
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/aea90927-8ec9-479a-a480-210de131b1f2)

6. Average amount of money spent per session. Only include purchaser data in July 2017
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/47c8c782-f040-4b86-9db3-fc10b05b9d9f)

7. Other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017. Output should show product name and the quantity was ordered.
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/00d6b0b6-6149-475e-8938-492834d34b9d)
  
8. Calculate cohort map from product view to addtocart to purchase in Jan, Feb and March 2017. For example, 100% product view then 40% add_to_cart and 10% purchase.
![image](https://github.com/BuiDucPhat12/Ecommerce-Project/assets/174614831/cbb491cf-080b-4f3c-bc0b-e135d4131e63)
