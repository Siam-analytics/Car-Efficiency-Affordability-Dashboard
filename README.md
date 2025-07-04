# 🚗 Car Analysis Dashboard with Power BI

This project explores a vehicle dataset to help consumers and analysts identify the most efficient, affordable, and suitable cars based on price, mileage, fuel type, drivetrain, and engine configuration.

## 📊 Dashboard Overview

The interactive Power BI dashboard answers key consumer questions:
- ✅ What is the **best fuel and cylinder combo** for cost per mile?
- ✅ Which **drive train + engine type** offers the best value?
- ✅ What are the **most fuel-efficient and cost-effective cars**?
- ✅ How close am I to affording my **dream car**?

![Dashboard Screenshot](https://github.com/Siam-analytics/Car-Efficiency-Affordability-Dashboard/blob/main/Screenshot%202025-07-04%20191040.png) 

## 📌 Key Features

- **KPI Cards**:
  - Best value-for-money car
  - Most fuel-efficient car
  - Winning fuel-engine-drive combo
- **Bar Charts**:
  - Price per mile by fuel & cylinder
  - Value per mile by individual car
- **Scatter Plot**:
  - Mileage vs. Price (with trend line)
- **Gauge Chart + Dynamic Message**:
  - Shows your current savings and how far you are from your target car price
- **Slicers**:
  - Filter by engine-drive combo, fuel-cylinder combo

## 📁 Dataset Fields Used

- `car_name`
- `price (USD)`
- `mileage`
- `fuel`
- `cylinders`
- `engine`
- `drivetrain`
- `body`
- `Fuel-Cylinder Combo` *(calculated)*
- `Engine-Drive Train` *(calculated)*
- `price per mile` *(calculated)*

## 🧠 Tools & Skills Applied

- Power BI: Card visuals, bar charts, gauge charts, scatter plots, slicers
- DAX: Custom measures for savings gap, car ranking, and dynamic messaging
- Storytelling design: Clear, user-friendly layout and insights
- Data Cleaning: Removed unnecessary columns, Removed blank rows and nulls

## 💡 Insights Discovered

- The most fuel-efficient car was not the cheapest per mile
- Certain hybrid and electric models offered the best long-term value
- Drive train and cylinder count significantly impact price per mile

## 📂 Files Included

- `VehicleAnalysis.pbix` – Power BI dashboard file
- `README.md` – Project documentation
- `car-dashboard.png` 
- `csv file` - https://www.kaggle.com/datasets/khwaishsaxena/vehicle-price-prediction-dataset

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Explore the report using slicers and visuals
3. Update your savings parameter to personalize the experience

## 📧 Contact

Created by **Siam** –  
📫 Connect on [LinkedIn](www.linkedin.com/in/siam-ahammed-844280336)  
💼 Portfolio: [portfolio-link](https://www.datascienceportfol.io/siamahammed688) 

---

**#PowerBI #DataVisualization #Dashboard #CarData #ConsumerAnalytics #DAX #DataStorytelling #GitHubPortfolio**
