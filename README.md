# Car-Sales-performance-Analysis-Excel-Power-bi
Power BI project analyzing car sales performance and profitability trends across India
# 🚗 Car Sales Performance Analysis (2019–2025)

**Tools:** Power BI | Excel | DAX | Power Query  

## 📊 Overview
This project analyzes car sales performance across India, focusing on:
- Dealer locations, models, fuel types, and safety features
- Revenue trends and profit margins
- Identification of underperforming cities

## ❓ Problem Statement

- Understand sales performance of different car manufacturers (Maruti Suzuki, Tata, Toyota, Hyundai, Volkswagen, etc.) across Indian cities.

- Identify pricing trends by comparing Ex‑Showroom Price vs Manufacturing Cost Price.

- Analyze mileage (City, Highway, ARAI Certified) and its impact on sales volume.

- Evaluate safety features (Airbags, Safety Ratings) and their correlation with customer demand.

- Provide actionable insights for dealers and manufacturers to optimize inventory, pricing, and marketing strategies.

📊 Attribute Details

<img width="631" height="2420" alt="image" src="https://github.com/user-attachments/assets/79016274-7dd4-474f-bdfd-99168579174d" />

## Data Preprocessing Steps:
To make the dataset analysis‑ready, apply the following preprocessing:

- Fix Incorrect Data Types:

  - Convert numeric columns (Cars Sold, Ex-Showroom_Price, Manufacturing Cost Price) to integers/floats.

  - Ensure Sales_Date is in datetime format.

- Standardize Categories:

  - Normalize inconsistent labels (e.g., Manual, manuaL, mAnuaL → Manual).

  - Clean Fuel_Type values (Petrol, Diesel, CNG).

- Handle Missing/Erroneous Values:

  - Replace placeholders like SUMIF, AVERAGIF, CountIF with proper numeric values or impute.

  - Apply mode imputation for categorical attributes (e.g., Airbags).

- Correct Unrealistic Values:

  - Cap engagement metrics (likes, comments, shares) if present beyond impression_count.

  - Validate mileage values (e.g., remove extreme decimals like 18.600000000000001).

- Feature Engineering:

  - Create derived attributes such as Profit Margin = Ex-Showroom Price – Manufacturing Cost Price.

  - Group sales by Make, Model, State for trend analysis.

  - Extract year and month from Sales_Date for time‑series insights.
## 📉 Analysis & Visualizations:
- Developed interactive Power BI dashboards to address the problem statements using:

  - Bar Charts

  - Line Graphs

  - Donut Charts

  - Tree Maps

  - KPI Cards

- Highlights from Car Sales Performance (refer PDF for visuals):

  - Total Cars Sold by Brand – Toyota, Maruti Suzuki, Hyundai, Tata, Mahindra, etc.

  - Profitability – Overall profit reached 212bn with manufacturing cost around 2bn.

  - Mileage Insights – Average city mileage across brands is 15.47 km/l; hatchbacks lead with 21.46 km/l.

  - Price Trends – Ex‑Showroom vs Manufacturing cost analysis shows margins across cities (New Delhi, Bangalore, Chennai, Hyderabad, Kochi, Mumbai, Ahmedabad).

  - Performance vs Sales – High‑performance cars correlate with higher sales volumes.

  - Year & Quarter Analysis – Sales growth tracked from 2021–2025 with quarterly breakdowns.

  - Fuel Type & Safety Ratings – Distribution across Petrol, Diesel, CNG; majority cars rated 3–5 stars.

  - Profit by Brand – Bentley, Toyota, Jaguar, Maserati, Porsche, Audi, BMW, etc. show maximum profit contributions.

  - City‑wise Sales – Chennai, New Delhi, Bangalore, Hyderabad, Mumbai lead in total cars sold.

<img width="847" height="802" alt="image" src="https://github.com/user-attachments/assets/4f07cc50-5cfd-4029-90a2-80baeb7aefc1" />
<img width="1255" height="722" alt="image" src="https://github.com/user-attachments/assets/c55fbfab-215a-4612-bb3b-94516c149743" />

## 🚘 Performance Insights:
 - 🔝 Maruti Suzuki & Toyota lead in total cars sold across India.

 - 💰 Overall profit reached 212bn, with manufacturing costs around 2bn, showing strong margins.

 - ⛽ Petrol cars dominate, but Diesel variants (Toyota Etios, Mahindra KUV100) show consistent demand.

 - 🛡️ Majority of cars sold have 3–5 star safety ratings, with airbags becoming a standard feature.

 - 📈 2024–2025 recorded peak sales volumes, especially in Chennai, New Delhi, and Bangalore.

 - 🚙 Hatchbacks deliver the best mileage (avg. 21.46 km/l) compared to sedans and SUVs.

 - 🏆 Premium brands (Bentley, Maserati, Ferrari) contribute high profits despite lower unit sales.

## 📌 Conclusion:

The integration of Excel preprocessing and Power BI dashboards enabled a comprehensive analysis of car sales performance (2021–2025).
- Key findings include:

- Maruti Suzuki & Toyota dominate the Indian market in terms of sales volume.

- Profit margins are highest in luxury brands, while hatchbacks drive mass adoption.

- City‑wise analysis shows Chennai and New Delhi as top contributors.

- Mileage & safety features strongly influence customer preferences.

- Quarterly trends highlight growth momentum in Q3 and Q4 of 2024.

- This project transformed raw automotive sales data into clear, actionable insights for manufacturers, dealers, and analysts.


