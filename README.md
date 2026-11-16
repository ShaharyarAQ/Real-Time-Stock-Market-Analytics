# Real-Time-Stock-Market-Analytics

Project Overview 
This project focuses on analysing real-time stock market data using Apache Spark 
Streaming. The goal is to create a dashboard that shows statistics in real time about what’s 
at the stock market. The analysis is based on a historical dataset (stock.csv) containing 
multiple stock entries, where each row represents a stock name and its corresponding 
price. A Kafka producer (kafkastocks.py) streams this dataset as if it were real market data, 
continuously sending events 
