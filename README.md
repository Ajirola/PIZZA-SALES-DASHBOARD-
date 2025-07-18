# PIZZA-SALES-ANALYSIS-
# 🍕 Pizza Sales Dashboard

## 📑 Table of Contents
- [Description](#description)
  
- [Overview](#overview)
  
- [Problem Statement](#problem-statement)
  
- [Objective](#objective)
  
- [Tools Used](#tools-used)
  
- [Dashboard](#dashboard)
  
- [Insights Gained](#insights-gained)
  
- [Recommendation](#recommendation)
  
- [Contact](#contact)

## 📌 Project Overview
This Power BI dashboard was built to analyze a pizza company's sales data. It uncovers which pizzas are the most and least popular, when customers are most likely to order, and what size and flavor categories are preferred. It supports smarter business decisions based on clear visual insights.

## 📄 Description
A pizza company wanted to better understand customer preferences and improve business decisions using sales data. This dashboard brings their data to life revealing key patterns across products, time, and customer choices.

## ❓ Problem Statement
The business lacked visibility into:
📍 Which pizzas perform best or worst

📍Customer preferences for pizza sizes and flavors

📍The best days and months for sales

📍Performance comparisons across categories (e.g., Veggie vs Chicken)

This made it difficult to plan production, pricing, staffing, and promotions.


## 🎯 Objective
1️⃣ Identify top and bottom-selling pizzas

2️⃣ Analyze sales by pizza **category** and **size**

3️⃣ Discover best-performing **days** and **months**

4️⃣ Support business decisions through easy-to-understand visuals

## 📊 Key Areas Analysed
📍Top 5 and Bottom 5 pizzas by sales

📍 Daily sales patterns (Sunday to Saturday)

📍 Monthly sales trends

📍 Pizza sales by size (S, M, L, XL, XXL)

📍 Pizza sales by category (Classic, Supreme, Chicken, Veggie)

## 📚 Data Source

The dataset was obtained from kaggle website

Here's the link to the dataset: https://www.kaggle.com/datasets/nextmillionaire/pizza-sales-dataset

## 📦 Dataset Description
The dataset provides detailed information about pizza orders over a given period.

Column Name        | Description |
|--------------------|-------------|
| **pizza_id**       | A unique identifier for each distinct pizza variant available for order. |
| **order_id**       | Unique ID for each customer order. One order may include multiple pizza variants. |
| **pizza_name_id**  | Identifier that maps to a specific pizza name (useful for joining or grouping). |
| **quantity**       | Number of units ordered for a specific pizza variant in a given order. |
| **order_date**     | The date the customer placed the order (used for trend analysis). |
| **order_time**     | The exact time the order was placed (useful for time-based patterns). |
| **unit_price**     | The price of a single unit of the specific pizza variant. |
| **total_price**    | Total cost of all units of a pizza variant within the order (`unit_price × quantity`). |
| **pizza_size**     | Size of the pizza ordered (e.g., Small, Medium, Large, XL, XXL). |
| **pizza_category** | Category of the pizza (e.g., Classic, Veggie, Supreme, Chicken). |
| **pizza_ingredients** | List or description of ingredients used in the pizza. |
| **pizza_name**     | The actual name of the pizza variant (e.g., Thai Chicken Pizza, Barbecue Chicken Pizza). |
