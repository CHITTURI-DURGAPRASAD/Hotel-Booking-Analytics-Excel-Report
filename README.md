Hotel Booking Analytics Excel Report

Overview :-
A comprehensive Microsoft Excel dashboard analyzing hotel booking data across multiple properties, focusing on revenue generation, booking patterns, and platform performance. The project leverages Excel's advanced features including Power Query for data cleaning and Power Pivot for data modeling to create meaningful insights.

Features :-
- Week-wise booking analysis across different platforms
- Property performance comparison
- Revenue tracking and analysis
- Customer rating analysis
- Booking source distribution

Datasets used :-

[fact_bookings](https://drive.google.com/file/d/1-41m3wxOc321UO40aj8aqIP4SNHagJBN/view?usp=sharing)
[dim_properties](https://drive.google.com/file/d/1OsLuGxCDCQB9Ulg_VBL5J9n8cYQMUH-j/view?usp=sharing)

Data Processing Steps :-
1. **Data Cleaning (Power Query in Excel)**
   - Standardized data formats
   - Removed duplicates and null values
   - Formatted currency values
   - Created calculated columns as needed

2. **Data Modeling (Power Pivot in Excel)**
   - Created relationships between tables fact_bookings and dim_properties
   - Implemented DAX measures for calculations
   - Built hierarchies for better data organization

Key Metrics Analyzed :-
- Total Bookings: 765
- Total Revenue Generated: ₹10,972,075
- Average Rating: 3.87
- Platform-wise booking distribution
- Weekly booking trends

Property Analysis :-
The Excel dashboard covers 5 properties:
- Atliq Blu
- Atliq City
- Atliq Exotica
- Atliq Grands
- Atliq Seasons

Booking Platforms :-
Analysis covers various booking sources:
- Direct Offline
- Direct Online
- Journey
- LogTrip
- MakeYourTrip
- Tripster
- Others

Time Period :-
The analysis covers data from:
- June (Weeks 23, 24)
- July (Weeks 27, 28)

Tech Stack :-
- Microsoft Excel
- Excel Power Query
- Excel Power Pivot

Requirements :-
- Microsoft Excel 2016 or later (with Power Query and Power Pivot enabled)

Usage :-
1. Open the Excel workbook
2. Enable Power Pivot add-in if not already enabled:
   - File → Options → Add-ins → Manage Excel Add-ins → Go
   - Check 'Microsoft Power Pivot for Excel'
3. Use the Power Pivot window to view data model
4. Refresh data using the Refresh All button when needed
5. Use Excel's built-in filters and slicers to analyze specific segments


