# Project-Real-Estate-Analysis

# 🏠 Housing Market Analysis Dashboard

## 📌 Project Overview
This project involves a comprehensive data analysis of the housing market using **Microsoft Power BI**. The goal of this dashboard is to visualize house market trends, Sales Performance, House type analysis and identify key factors influencing property values (such as location, square meter, and amenities).

## 📊 Dashboard Preview
<img width="1377" height="777" alt="Screenshot 2026-02-15 164526" src="https://github.com/user-attachments/assets/2cea838e-708a-4d86-a642-365407902efe" />
<img width="1376" height="773" alt="Screenshot 2026-02-15 171138" src="https://github.com/user-attachments/assets/b9e38b17-95b7-414a-a48a-3758c4a84e6c" />
<img width="1374" height="772" alt="Screenshot 2026-02-15 171200" src="https://github.com/user-attachments/assets/aaf27553-08b5-42b5-91a7-c5716120e6f6" />


## 🎯 Problem Statement
The real estate market is complex, with prices influenced by numerous variables. This project aims to answer:
- What is the median sales price change by different region?
- How is YOY sales growth by sales type?
- What is sum of sales in different region, Average price per SQM by Region?
- What is the correlation between house age and purchase price?
- What is offer and purchase price by house type, Average inflation, interest,yield, SQM and SQM_price by house type?

## 🛠️ Tools & Technologies
- **Tool:** Microsoft Power BI Desktop
- **Data Transformation:** Power Query Editor
- **Data Modeling:** Star Schema
- **Calculations:** DAX (Data Analysis Expressions)

## 🔑 Key Features
- **Interactive Slicers:** Filter data by City, Area, Sales Type, or Region.
- **Key Performance Indicators (KPIs):** Units Sold in latest year and Quarter, Last 12 months sales, Offer vs Purchase Price, YOY sales growth by sales type , Average Price per Sqm. by region, Sales by Region, offer price to SQM price by sales type, offer and purchase by house type, average inflation,interest, yield by house type, average SQM/SQM price by house type.
- **Trend Analysis:** Visuals depicting market movements over time.

## 📂 Dataset
The dataset used for this analysis contains information on housing properties, including:
date - The date when the data was recorded or when the transaction took place.
quarter -	The fiscal quarter in which the event occurred (e.g., Q1, Q2, Q3, Q4).
house_id -	A unique identifier for each house in the dataset.
house_type -	The type of house (e.g., detached, semi-detached, apartment, etc.).
sales_type -	The type of sale, such as "new" or "resale" (indicates if the house is newly built or pre-owned).
year_build -	The year the house was built.
purchase_price -	The price at which the house was purchased.
%_change_between_offer_and_purchase -	The percentage change in the price between the offer and the purchase price.
no_rooms -	The number of rooms in the house.
sqm -	The total area of the house in square meters.
sqm_price -	The price per square meter of the house.
address -	The street address of the property.
zip_code -	The postal code of the property's location.
city -	The city where the property is located, which is an urban area and part of a municipality (e.g., Copenhagen, Aarhus).
area -	The specific district, neighborhood, or part of the city where the property is located (e.g., Vesterbro in Copenhagen).
region -	The broader administrative region of Denmark in which the property is located (e.g., Capital Region of Denmark, Central Denmark).
nom_interest_rate% -	The nominal interest rate on a mortgage loan for the house (expressed as a percentage).
dk_ann_infl_rate% -	The annual inflation rate in Denmark, as a percentage.
yield_on_mortgage_credit_bonds% -	The yield on mortgage credit bonds, expressed as a percentage.
<img width="1583" height="507" alt="image" src="https://github.com/user-attachments/assets/456d0004-f53b-44ad-afb7-8e14511356c9" />

## 🚀 How to Run This Project
1. **Download:** Clone this repository or download the `Housing.pbix` file.
2. **Install Power BI:** Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
3. **Open:** Double-click `Housing.pbix` to launch the report.
4. **Interact:** Use the filters and slicers to explore the data.

## 📈 Insights & Conclusions
- Median Sales Price has increased for 3 region and descreased for 1 region(Bornholm).
- There are some properties where purchase price is very less as compare to offered price
- Year over Year sales growth percentage has increased only in 1 sales type(auction), and decreased in other 3 sales type.
- Bornholm has done least sales as compare to other regions
- Appartment has highest average sqm price per average sqm and Villa has lowest average sqmp rice per average sqm

## 👤 Author
**Amrit Banyal**
- **LinkedIn:** https://www.linkedin.com/in/amrit-banyal-59a0b924b/
