# Telemetry for Accident Prevenction

This project there is dataset with geolocation data, drivers name and trucks Id  for analisis of trafic infractions and time shift rule break during work jorney
on roads linked among states of Brazil.
It will help to work safety team company minimize traffic accident risks. 

# Life Circle Data Aanalysis Project (IN DEVELOPMENT)

1. BUSINESS ISSUE:
Although every trucks drivers did courses and trainings to avoid accedents risks, there are many traffic infraction during the work jorney of trucks drivers.  

2. UNDERSTANDING THE BUSINESS:
The drivers only work 8 hour a day, respecting all break times to resting and during work jorney, however during the jorney they have GPS truck divice to help them check point
needed attention more, places they can stop do it.
Weekly all drivers trucks did trainings, watching speeches about accident prevenction.     

3. SOLUTION PLANNING:
Get a dataset with trancking information the work jorneies to analisys critical points, date time, how long duration, how is driver, what is truck and 
how many times by drivers and trucks of traffic infractions.  

4. DATA COLLECTION:
By CSV from Microsoft SQL database. 
It did a SQL query from ERP system company, that ERP are integarted with web service to colect data from board computer of trucks and colect data from GPS divece of truck getting temetry data, after, it was export to CSV.

5. DATA CLEANING:
This process it did usisng Python with jupyter notebook.
Check unfilled columns. 
Deleting some inconsistent rows. 
Translantion contents some columns to English.
Tranlation of columns label to English.
Deleting some inconsistent columns. 
Replace some characters.
Changing data types.

6. EXPLORATION OF DATA:
Understand what the data says, create hypothesis maps and hypothesis questions that generate insights for analysis.
New columns created:
** those columuns are filled with API nominatim to get info about address from geo coordinates **
df['region'] 
df['state']
df['city'] 
df['road']
** these columns did create to make calculate KM ran between last odometer and next odometer **
df['odometer2']
df['km_ran']

7. DATA MODELING:
Dataset created with new columns of categories from dataset origin to analysis in the chart.

8. VISUALIZATION AND REPORT:
Developed dashboard in Microsoft Power BI and integrated Google Maps JavaScript API to use Google Street Viwer.

9. CONCLUSION:
Note the analysis are grouped by 3 hypothesis are Branches, Drivers and Location to understand whats happened by differents perspectives and to help better strategy to go action.



   
