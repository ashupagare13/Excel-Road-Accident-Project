# Excel-Road-Accident-Project

Dataset - https://docs.google.com/spreadsheets/d/1R_uaoZL18nRbqC_MULVne90h3SdRbAyn/edit?usp=sharing&ouid=116890999875311477003&rtpof=true&sd=true
The dataset is downloaded from the Kaggle website.

Steps involved in this Project:
1. Data Cleaning:- 
- Added filter to all the columns.
- Checked for duplicates and blanks, and spelling mistakes.
-  Using the find and replace option, replace the typo with its correct form.

2. Data Processing:-
- Created a new monthly column from the Accident Date column using the text function.
- Created a new year column from the Accident Date column using the text function.

3. Data Analysis & Visualization:-

KPI

Primary KPI 
- Created a pivot table.
- Created a 1st KPI using accident severity and no of casualties columns.
- Calculated the percentage of casualties for each severity against the total no of casualties.
- Based on the percentage calculation, a doughnut chart shows the percentage of casualties for each severity against the total number of casualties.
- Adjusted the chart size as per the box on the dashboard and changed the color according to the theme.
- Created a second pivot table based on vehicle type and the no of casualties.
- Using a calculated item option from the fields, items, and sets options in the Pivot table, Analyze grouped the similar vehicle types into a single field and hide the fields which are grouped already.
- Maximum no of casualties happened by the car vehicle type.
- Created the doughnut chart based on the percentage of car casualties against the total no of casualties.

Secondary KPI
- Inserted an icon related to the different vehicle types based on the second pivot table.
- Using cell reference, inserted the no of casualties as per the vehicle type.

Monthly trend:-
- Inserted a new pivot table into a new sheet and created a table using the month and number of casualties columns and year column as a filter.
- Extracted the month and year-wise casualties from the table and created a line chart using the information.
- Added the line chart to the dashboard and adjusted the size, color, and shape.

Road Type:-
- Created a new pivot chart based on road type and number of casualties.
- Based on the pivot chart, created a horizontal bar graph.
- Added the line chart to the dashboard and adjusted the size, color, and shape.

Road Surface:-
- Created another pivot chart based on the road surface and number of casualties.
- Grouped the similar surface into a single field and hide the unwanted fields.
- Extracted the values out of the pivot chart.
- Using the chart, created a treemap and added it to the dashboard.

Location and Light:-
- Created 2 different pivot tables based on the rural or urban & number of casualties and light types and number of casualties.
- Grouped the similar fields from the light types into a single field,
- Created a doughnut chart for both tables and added it to the dashboard.

Filter Panel:-
- Created the filters based on the rural or urban and the timeline.
- Adjusted the color of the filter according to the theme of the dashboard.
