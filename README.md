# 🏨✨ Atliq Grands Hospitality Analysis – Python Project

![Python](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-black?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-purple?style=for-the-badge)
![Data Cleaning](https://img.shields.io/badge/Data%20Cleaning-Preprocessing-red?style=for-the-badge)
![Feature Engineering](https://img.shields.io/badge/Feature%20Engineering-Transformation-teal?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Insights-green?style=for-the-badge)

![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

# 🏢 Company Overview
AtliQ Grands is a leading hotel chain operating across major Indian cities like  Mumbai, Delhi, Bangalore and Hyderabad, with diverse hotel types such as AtliQ Seasons, AtliQ Exotica, AtliQ Bay and AtliQ Palace.
With over 20 years of experience in the hospitality industry, the company has recently faced declining revenue and market share, highlighting the need for data-driven strategies to enhance operational efficiency, maximize revenue and maintain a competitive edge.

# 🎯 Project Objective
The primary objective of this project is to leverage data analytics on historical booking records from both the official website and third-party platforms. By analyzing patterns in bookings, revenue, occupancy and customer behavior, the project aims to:
- Identify high-performing and underperforming properties.
- Optimize revenue generation across platforms and cities.
- Inform strategic decision-making for marketing, pricing, and operational improvements.
- Provide actionable insights to drive growth and competitiveness in the market.

# ⚠️ Problem Statement
AtliQ Grands is facing declining revenue and market share across its hotels. The challenge is to analyze booking data from both official and third-party platforms to uncover insights, optimize revenue, and support data-driven decisions.


# 🛠️ Tools used
- Python (pandas, matplotlib)
- Jupyter Notebook

# 📊 Datasets
- dim_date.csv
- dim_hotels.csv
- dim_rooms.csv
- fact_aggregated_bookings.csv
- fact_bookings.csv
- new_data_august.csv

# 📈  Methodology
- Dataset Review: Conducted a thorough examination of the dataset to understand its structure and identify inconsistencies or missing values.
- Invalid Data Correction: Corrected or removed erroneous entries, such as negative guest counts, to ensure data reliability.
- Outlier Handling: Detected and addressed outliers that could distort analysis.
- Created New Column: Added calculated fields, such as occupancy percentage (successful bookings divided by total capacity), to provide deeper insights into hotel performance.
                     Concatenating and merging datasets for furthur analysis.
- Validation: Verified the cleaned and enriched dataset for accuracy and readiness for further analysis.

# 💡 Key Insights

- Room Class Performance:
The Presidential Suite (RT4), despite its premium pricing, achieved the highest occupancy rate (59.3%), highlighting strong demand for luxury offerings.

- City-Level Occupancy:
Delhi recorded the highest average occupancy (60.4%), outperforming other cities, while Bangalore lagged at 55.3%, indicating potential for market or service improvements there.

- Weekend vs. Weekday Trends:
Occupancy rates were consistently higher on weekends, suggesting opportunities to leverage dynamic pricing, weekend-specific promotions, and tailored marketing campaigns.

- Seasonal Demand Patterns:
Occupancy peaked in June (Delhi at 60.4%), while Hyderabad followed at 56.9%. Revenue was strongest in May 2022 (₹408.4M) and July 2022 (₹389.9M), underscoring the importance of seasonal demand planning.

- Revenue by City:
Mumbai emerged as the largest revenue contributor (₹668.6M), solidifying its role as a critical growth driver for the chain.

- Property-Level Performance:
AtliQ Exotica led with ₹219M in revenue, while AtliQ Seasons underperformed with only ~₹46M, indicating heavy dependence on top-performing properties and opportunities to optimize underperformers.

- Customer Satisfaction:
Delhi hotels received the highest average customer rating (3.78), whereas Bangalore (3.40) fell behind, highlighting the need for improved guest experience in weaker markets.

- Booking Platform Contribution:
A significant share of revenue comes from “Others” (40.9%), followed by MakeMyTrip (19.8%), pointing to the potential to diversify platform strategies and reduce reliance on a single channel.

# Recommendations
- Fix weak properties & cities: Improve underperformers like AtliQ Seasons and Bangalore hotels.
- Leverage high-demand periods: Use dynamic pricing and promotions on weekends and peak months.
- Diversify booking channels: Reduce reliance on “Others” and expand OTA/direct bookings.
- Enhance guest experience: Boost satisfaction in low-rated locations through service and amenities improvements.

----The End----
