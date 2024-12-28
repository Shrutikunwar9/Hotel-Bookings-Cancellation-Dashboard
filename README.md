# Hotel Reservation Cancellation Dashboard ( Using MS Excel)

## Project Objective
The objective of this Hotel Bookings Cancellation Dashboard project is to create a comprehensive and interactive tool using Microsoft Excel that enables hotel management to analyze and understand cancellation patterns and their impact on operations.

## Dataset used
- <a href="https://github.com/Shrutikunwar9/Hotel-Bookings-Cancellation-Dashboard/blob/main/hotel_bookings%20cancellation%20dashboard.xlsx">Hotel Cancellation Data</a>

## KPIs
-	What is Booking Cancellation Rate? 
-	Booking Type Distribution among Couple, Family and Single.
-	Cancellations due to Room Preference Mismatch.
-	Hotel-Specific Cancellation Rate.
-	Cancellations respect to months.

- Dashboard Interaction <a href="https://github.com/Shrutikunwar9/Hotel-Bookings-Cancellation-Dashboard/blob/main/Screenshot%202024-12-27%20144947.png"> View Dashboard</a>

## Process
Import and clean Data
- Use Power Query to clean and transform raw data (e.g., remove duplicates, handle missing values, remove unnecessary column).
-	Load the cleaned data back into Excel and make some desired column as required (e.g., room_status, guest_type using excel formulas)
Insert Pivot Tables for each KPI: 
- Cancellation Rate: Use is_canceled to calculate the percentage of canceled bookings.
- Booking Type Distribution: Group by guest_type.
-	Room Preference Mismatch: Compare reserved_room_type and assigned_room_type.
-	Hotel-Specific Cancellations: Filter by hotel.
Use charts for a visual representation of KPIs: 
- Bar Charts for categorical data (e.g., guest type).
- Line Charts for trends (e.g., desired and undesired).

## Dashboard 
![Screenshot 2024-12-27 144947](https://github.com/user-attachments/assets/259c9ea3-3738-4afb-8439-bf14fa4e816e)

## Project Insight
-	The overall cancellation rate is 27%.
-	City Hotels have slightly higher cancellations compared to Resort Hotels
-	Couples dominate the guest type, contributing to the majority of bookings.
-	Families and singles cancel less frequently than couples.
-	Room preference mismatch occurs in 15% of bookings, indicating inefficiency.

## Final Conclusion
The hotel booking cancellation analysis reveals critical insights that can guide operational improvements and strategic decisions:
- August and July are peak months for City and Resort Hotels, respectively, with couples being the dominant guest type. Focusing on marketing efforts during these periods can maximize bookings.
- Room preference mismatches (15%) highlight areas for improvement in reservation management and room assignment processes.

## THANK YOU FOR YOUR TIME

  




