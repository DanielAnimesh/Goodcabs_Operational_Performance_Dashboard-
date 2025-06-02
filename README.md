## 🚖 Goodcabs Passenger & Trip Insights – Power BI Dashboard

## 📌 Project Overview
**Goodcabs**, founded two years ago, is a fast-growing cab service company operating in Tier-2 cities across India. Its mission is to empower local drivers while ensuring quality service for passengers. With ambitious growth and service goals for 2024, the operations team wanted to **track key performance indicators** to improve decision-making and customer experience.

When the Chief of Operations, Bruce Haryali, urgently needed insights, the task was passed to Peter Pandey, the company’s curious data analyst, who created a performance dashboard in **Power BI** that visualizes key trends and passenger behavior across cities.

---

## 🎯 Dashboard Objective
This dashboard is designed to help the Goodcabs team:
- Track **trip volume**, **fare trends**, and **ratings**
- Identify **behavioral patterns** between **new** and **repeat** passengers
- Compare city-wise performance and highlight **key areas of growth or concern**
- Support decision-making for 2024 strategic targets

---

## 🗂️ Data Overview
The dataset powering the Goodcabs performance dashboard was built from two primary sources: trips_db and targets_db, enriched with supporting dimension tables to enable time-based, city-level, and behavioral insights.

📦 trips_db – Trip & Passenger Metrics
This database captures both granular and aggregated operational data across tier-2 cities. It supports deep-dive analysis into trip activity, passenger behavior, and repeat usage patterns.

Key Tables:

fact_trips: Individual trip-level data including:

trip_id, date, city_id, passenger_type, distance_travelled, fare_amount, passenger_rating, driver_rating

Enables analysis of ride quality, pricing trends, and daily trip details.

fact_passenger_summary (Aggregated):

Monthly summary of passenger types per city, including:

total_passengers, new_passengers, repeat_passengers

Helps track acquisition and retention trends across cities.

dim_repeat_trip_distribution (Aggregated):

Monthly breakdown of repeat passengers by trip frequency (1 to 10 trips), enabling insights on customer loyalty and stickiness.

dim_city:

Maps city_id to city_name (e.g., RJ01 → Jaipur), allowing for clear location-level grouping and filtering.

dim_date:

Time dimension supporting:

date, month_name, start_of_month, and day_type (Weekday/Weekend)

Enables seasonal trend analysis and weekday-vs-weekend comparisons.

🎯 targets_db – Performance Benchmarks
This database outlines monthly targets set by Goodcabs leadership, used to track performance against key business objectives like customer satisfaction and trip volume.

Key Tables:

monthly_target_trips:

Targeted total trip count per city and month.

monthly_target_new_passengers:

Goals for new passenger acquisition, city-wise and monthly.

city_target_passenger_rating:

Desired average passenger rating per city, supporting customer experience evaluation.

Power BI's data model was used to build relationships between dates, city, and passenger types. 

![image](https://github.com/user-attachments/assets/e4a58581-2eb7-421f-ace0-f3f4e2e79c29)

---

## 📄 Dashboard Pages

### 🏙 City Insights

![image](https://github.com/user-attachments/assets/8f0ffc52-e1c9-48ef-96c6-5f760d45d9fe)


### 🧍 Trip Insights

![image](https://github.com/user-attachments/assets/9e826ace-2dc7-4257-97b7-4789ec516581)

![image](https://github.com/user-attachments/assets/a574b3fb-af1c-403e-8ba1-7f528ede1e8d)



---

## 💡 Recommendations & Key Insights

### Headline: 📉 New Passenger Count Continues to Decline
> Focused marketing strategies may be needed as the share of **new passengers has been steadily falling** month over month.
> Focus on cities with lower target achievement
> Optimize resources for weekday vs weekend demand shifts
> Conduct driver training and feedback programs to improve service quality.

### Other Insights:
- Cities like **Surat and Lucknow** are consistently outperforming on repeat passenger engagement.
- **Passenger ratings** are relatively stable, with occasional dips tied to long-distance or high-fare trips.
- **Trip volume** and **fare per km** trends suggest the need to optimize pricing strategies in underperforming cities.

---

## 📊 Live Dashboard
🔗 **[Power BI Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNzNiYTM3N2MtZTQwYi00NjgxLWFmNmQtZGE4NTIzZTUzMjFhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

## 💻 Project Files
📂 **[View Code & Files on GitHub]([#](https://github.com/DanielAnimesh/Goodcabs_Operational_Performance_Dashboard-.git))**

---

## 🙏 Thank You
Thanks to the Codebasics team for providing the data for this project, This dashboard is a step toward making operations **data-driven**, **passenger-focused**, and **scalable** in Tier-2 cities.

---

## 🔗 Let's Connect
**Animesh Daniel**  
📧 piyushdaniel@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/animeshdaniel)

---
