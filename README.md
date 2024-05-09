# Hotel-Booking-EDA

## Project Overview
In this exploratory data analysis project, we delve into a comprehensive dataset detailing over 100,000 hotel bookings to uncover patterns and insights that can inform strategic business decisions. The dataset includes a variety of metrics such as booking cancellation rates, average daily rates (ADR), the number of nights stayed, and guest geographical distribution across two distinct hotel categories: City and Resort hotels.

## Dataset
The dataset hotel_bookings.csv is a rich compilation of booking information that includes:

Guest demographics
Stay durations
Booking cancellations
Room prices
Special requests and more

The initial data cleaning involved handling missing values, removing erroneous entries, and preparing subsets of data for detailed analysis. For example, entries with zero guests were removed, and missing values in columns like 'country', 'agent', and 'company' were appropriately filled or replaced.

## Key Analyses
Guest Geography Analysis: Identifies where guests are coming from, highlighting key markets and potential areas for marketing focus.

Price Analysis per Room Type and Hotel Type: Examines how pricing varies between different room types and between City and Resort Hotels.

Seasonal Price Variations: Tracks how room prices fluctuate throughout the year, giving insights into demand cycles.

Cancellation Trends: Investigates cancellation rates monthly and identifies patterns that could help improve booking policies.

Length of Stay Trends: Analyzes guest preferences for length of stay, which differ significantly between City and Resort Hotels.

## Insights Gained
Market Strategy Development: The geographical guest analysis helps in tailoring marketing strategies to target key demographics.

Pricing Strategy Optimization: Detailed pricing analysis assists in setting competitive prices while maximizing revenue.

Operational Planning: Understanding peak times and guest stay preferences aids in operational and staff planning.

## Technologies Used
Python: For data manipulation and analysis, using libraries like Pandas and NumPy.

Matplotlib & Seaborn: For creating static plots.

Plotly: Initially used for interactive visualizations, later adapted to static plots for the report.

## How to Use This Repository
Data Folder: Contains the raw CSV file and any processed data files.
Scripts Folder: Python scripts used for analysis.
Notebooks Folder: Jupyter notebooks with detailed analysis steps and visualizations.
Output Folder (PDF) : Generated reports and visual outputs.
This project provides a deep dive into the dynamics of hotel booking demands, offering a detailed narrative that supports strategic business decision-making through data-driven insights. Whether you are a stakeholder in the hospitality industry, a data scientist, or a student learning about data analysis, this repository offers valuable resources and findings.
