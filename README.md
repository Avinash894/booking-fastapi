LLM-Powered Booking Analytics & QA System

The project is a FastAPI-based application that provides hotel booking analytics and natural language query processing.

Users can ask questions in simple language like:
"What is the total revenue for July 2017?"
"Which country had the highest booking cancellations?"
"What is the average price of a hotel booking?"

The API provides important business insights, including:
Total revenue generated
Cancellation rate (%)
Most booked country
Average Daily Rate (ADR)

Uses FAISS (Facebook AI Similarity Search) to handle natural language queries efficiently.
Embeddings are generated to match user queries with relevant data from the dataset.

Works with hotel_bookings.csv, containing over 120,000 booking records.
The dataset includes fields like total_revenue, is_canceled, country, adr, lead_time, etc.

Built using FastAPI, which is lightweight, fast, and supports asynchronous processing.
Uses Uvicorn as the ASGI server for handling multiple requests simultaneously.

Hotels & Resorts can analyze bookings, revenue, and customer behavior.
Business Analysts can extract insights from hotel data.
Data Scientists can use the API for ML model training & analytics.
Developers can integrate it into booking management applications.

The API has an accuracy of 100% and a response time of 0.31 seconds.
