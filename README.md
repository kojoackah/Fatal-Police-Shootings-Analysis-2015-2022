# Fatal-Police-Shootings-Analysis-2015-2022
Data Visualization Project using data from Washington Post

Number of cells per column

Name - 400 (5.22%)
Date - 0
Manner of death - 0
Armed - 209 (2.73%)
age - 468 (6.12%)
gender - 18 (0.235%)
race - 0
city - 0
state - 0
signs of mental history - 0
threat level - 0
flee - 0
body_count - 0
longitude - 821 (10.73%)
latitude - 821 (10.73%)
is geocoding exact - 0

Total dataset size - 7650

MISSING VALUES
Names - column eliminated bcos it provides no analytical value.
Armed - missing values provided 'Blank' values.
Age - average for all groups calculated and used in filling missing values for each group.
Gender - using the proportion of M and F in filled gender column, the empty col were filled.
M - 95.5%
F - 4.5%

Almost all the states had missing longitudinal and latitude coordinates. I downloaded the A.CRE Geocoding Excel Add-in v0.3 to automatically
generate the missing longitude and latitude for each city. 
A Google Geoencoding API Key was created to enable the add-in in Excel.
Since I had to pay for that services I looked for an alternative.

In Google Sheets, there is an add-in called "Geocode by Awesome Table". With a limited number of calls, you can generate the coordinates for any address (in this case, I used the city and state as the combined address).





