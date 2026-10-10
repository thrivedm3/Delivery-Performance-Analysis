# 🚚 Delivery Performance Analysis Dashboard

## 📝 Short Description
An interactive Power BI dashboard built on 43K+ Amazon deliveries that shows how traffic, weather, area and distance affect delivery time. It exists to help operations teams find what causes delays and which orders are most at risk.

## 🛠️ Tech Stack
- 🗄️ **MySQL**: Cleaned the data, created new columns and built a risk score view
- 📊 **Power BI**: Built a Interactive dashboard with DAX measures, charts and slicers

## 📂 Data Source
- 🔗 Amazon Delivery Dataset (Kaggle) : https://www.kaggle.com/datasets/sujalsuthar/amazon-delivery-dataset

## ✨ Highlights

### ❗ Business Problem
Delivery times vary a lot, from under an hour to over 3 hours. The business does not know whether delays come from traffic, weather, area, distance, pickup waiting or product category, so it cannot decide what to fix first.

### 🎯 Goal of the Dashboard
- ⏱️ Measure overall delivery performance (average time and share of slow orders)
- 🔍 Find the biggest drivers of delay
- 📅 Identify the busiest hours and days
- 🚨 Flag high-risk orders so delays can be reduced

### 🖼️ Walkthrough of Key Visuals

**📄 Page 1: Overview**
- 🔢 Cards for total orders, average delivery time, average distance and slow order %
- 🍩 Donut chart of Fast, Normal and Slow deliveries
- 📈 Orders by hour of day and average delivery time by day
- 🎚️ Slicers for Area and Category

**🚦 Page 2: Delay Drivers**
- 📊 Average delivery time by traffic, weather, area and product category
- 📊 Average delivery time by distance band
- 🔥 Heatmap of traffic and weather combinations, showing the worst conditions

**🚨 Page 3: High-Risk Orders**
- 🔢 High-risk order count and %
- ✅ Average delivery time by risk band, which proves the risk score works
- 📍 High-risk % by area and by time of day

### 💡 Business Impact and Insights
- 🚦 **Traffic is the biggest driver of delay.** Heavier traffic means clearly longer deliveries, and Jam conditions are the slowest.
- 🌧️ **Bad weather slows deliveries down.** Stormy and low-visibility conditions take longer than clear weather.
- 🚨 **The risk score works.** High-risk orders take longer than Medium-risk orders, and Medium-risk orders take longer than Low-risk ones.
