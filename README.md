# Riyadh-Airbnb-Bookings-Analysis

Project Overview

Objective
To analyze an Airbnb dataset for booked properties in Riyadh over the upcoming three months. The analysis provides insights on pricing, property characteristics, and customer preferences to help enhance listing strategies and booking appeal.

------------------------------------------------------------------------------------------------------------------

Key Questions

What are the pricing structures, including discounts and fees, for Riyadh properties?
How do additional costs (service fees, cleaning fees, and taxes) affect total booking amounts?
Which property types and locations offer the most value to customers?

------------------------------------------------------------------------------------------------------------------

Methodology
- Data Exploration
Data Familiarization: Examined data fields covering property listings, reviews, ratings, pricing components, and more.
Geographic Enrichment: Used Python for reverse geocoding of latitude and longitude coordinates to derive full property addresses, enhancing location-based analysis.

- Data Cleaning and Transformation
1- Parsing Pricing Details
Separated out pricing elements such as base rates, service fees, cleaning fees, and taxes using Power BI's M Query transformations for more granular analysis.
2- Discount and Fee Calculation
Calculated applicable weekly and long-stay discounts to get adjusted booking prices.
3- Data Consistency
Standardized and categorized property types, checked for data consistency across columns, and created columns for total price, taxes, and special offers.
4- Image Links
Added manually gathered image links for properties for visual reference in the Power BI dashboard.

- Data Modeling and Analysis
Modeled data in Power BI to support interactive analysis of price components, booking discounts, and property features.
Leveraged DAX functions to calculate total booking prices and identify pricing trends across property types and booking durations.

------------------------------------------------------------------------------------------------------------------

Key Insights
- Pricing Structure
Detailed pricing breakdowns, including service fees, cleaning fees, and taxes, significantly impact the total cost for bookings.

- Discount Effectiveness
Weekly and long-stay discounts are widely applied, providing clear incentives for longer stays and better value per night.

- Property Categorization and Value
Certain property types offer competitive pricing in popular locations, making them attractive for budget-conscious travelers.

------------------------------------------------------------------------------------------------------------------

Recommendations
- Enhanced Property Listings
Emphasize total price transparency by breaking down additional fees and discounts in property descriptions.

- Leverage Discount Options
Optimize discount strategies based on booking duration to attract extended-stay bookings during off-peak seasons.

- Focus on High-Demand Areas
Listings in popular neighborhoods or near attractions should be prioritized and enhanced to maximize occupancy and revenue.
