# Red Project
My First Machine Learning Project

**Background Context**

In the pursuit of customer-centric excellence, **Red Car Insurance Company** introduces a groundbreaking machine learning model for examine **Customer Lifetime Value (CLV)** of Red customers. This project strategically to facing issues in retaining customers and wants to advertise promotional offers for Red loyal customers.

Customer Lifetime Value (CLV) is an important metric in the car insurance industry that measures the net present value of a customer over their lifetime. CLV helps insurers to identify high-value customers and optimize the marketing strategies to retain them. Peter Drucker said “The purpose of a business is to create and keep a customer.” Which pretty much sums up the value of Customer Lifetime Value (CLV). CLV helps make important business decisions about strategies of sales, marketing, product development, and customer support.
* Marketing: How much should I spend to acquire a new customer?

* Product: How can I offer products and services tailored for my best customers?

* Customer Support: How much should I spend to service and retain a customer?

* Sales: What types of customers should sales reps spend the most time on trying to acquire?

Their practices to ensure long-term customer happiness and loyalty.

**Problems Statement**

It’s a competitive market for automotive insurance companies, and the insurance premium isn’t the only determining factor in a customer’s decisions. CLV is a powerful base to build upon to retain valuable customers, increase revenue from less valuable customers, and improve the customer experience overall. Using CLV effectively can improve customer acquisition and customer retention, prevent churn, help the company to plan its marketing budget, measure the performance of their campaign in more detail, and much more.

CLV obtained from the difference between the total amount of revenues from a customer and the total cost of servicing them. Red marketers should focus on tracking the customer lifetime value and acquisition costs of the customers by connecting their marketing data to their sales data. The higher CLV of customerts comes mostly through longer retention, and retention of customers is typically the most important factor in the industry. Therefore, Red should focus on retaining customers and making them more valuable to increase their profits.

Calculating customer lifetime value based on its history **takes quite a long time** (calculating the entire time the customer is with the company). By the time the calculation is completed, business strategies may be **too late to implement**, for example, in offering insurance renewals. A method is needed to predict customer lifetime value.

By predicting customer lifetime value, a company can determine which customers are likely to have high value and which are not. The company can focus its marketing activities on customers with high customer lifetime value, making marketing expenses more effective and efficient. Although the usefulness of the prediction will only be beneficial when the prediction is accurate.

**Objective**

Based on the problem statement above, Red need machine learning model to predict **customer lifetime value** of their customers. For this situation regression model can be implement to **predict the customer lifetime** value based on **sales and marketing data of Red customer**.

As a Data Scientist for Red, I gonna choose which regression model that most suits for I use as based of **Red CLV Machine Learning Model**.

**Analytic Approach**

1. First, I do Explantory Data Analysis (EDA) on Red Data Sales. 
2. Then, I do Data Preprocessing on the dataset so it become suitable and can be processed by the model.
3. Next, I do Feature Engineering on the feature if needed.
4. After that, I do model benchmarking from some of existed powerful regression model and choose the best fit model for our dataset.
5. Last, I do some residual analysis to determine how well the model captures the underlying patterns in the data. Because I use linear regression, the residuals should be normally distributed with a mean of zero and constant variance across the range of predicted values. This help us to ensure that the model's performance is consistent across different subsets of the data and that the model is robust enough to generalize well to unseen data.
