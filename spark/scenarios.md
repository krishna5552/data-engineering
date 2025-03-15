1. Log Analysis
Scenario: You have a large dataset of web server logs. Each log entry contains information such as timestamp, IP address, URL requested, response code, and response time.

Tasks:
Parse the log file and extract relevant fields.
Calculate the number of requests per IP address.
Identify the top 10 most requested URLs.
Calculate the average response time for each URL.
Identify the URLs that resulted in a 404 error.

2. Real-time Stream Processing
Scenario: You are receiving a stream of data from IoT devices. Each device sends temperature readings every second.

Tasks:
Set up a Spark Streaming job to process the incoming data.
Calculate the average temperature for each device over a 1-minute window.
Detect and alert if any device reports a temperature above a certain threshold.
Store the processed data in a database for further analysis.

3. Data Enrichment
Scenario: You have a dataset of user transactions and a separate dataset of user profiles. Each transaction contains a user ID, and each profile contains user details such as name, age, and location.

Tasks:
Join the transactions dataset with the user profiles dataset to enrich the transaction data with user details.
Calculate the total transaction amount for each user.
Identify the top 5 users with the highest transaction amounts.
Group the transactions by location and calculate the total transaction amount for each location.

4. Machine Learning Pipeline
Scenario: You have a dataset of customer reviews for products. Each review contains a text review and a rating (1-5 stars).

Tasks:
Preprocess the text data (e.g., tokenization, stopword removal).
Convert the text data into feature vectors using TF-IDF.
Train a machine learning model to predict the rating based on the review text.
Evaluate the model's performance using appropriate metrics.
Use the trained model to predict ratings for new reviews.

5. Data Aggregation and Reporting
Scenario: You have a dataset of sales transactions for a retail store. Each transaction contains information such as product ID, quantity sold, and sale amount.

Tasks:
Calculate the total sales amount for each product.
Identify the top 10 best-selling products.
Calculate the total sales amount for each day.
Generate a report showing the daily sales trend over the past month.