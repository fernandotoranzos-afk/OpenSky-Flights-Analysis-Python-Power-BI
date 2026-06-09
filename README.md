<img width="1920" height="1080" alt="dashboard_opensky" src="https://github.com/user-attachments/assets/b657fae8-ab2e-491a-a952-67623e2cbe85" />
# OpenSky-Flights-Analysis-Python-Power-BI
OpenSky Flights Analysis using Python, OpenSky API data, and Power BI.
OpenSky Flights Analysis
About this project

This is my first aviation data analysis project using real flight data from the OpenSky API.

The objective was to learn how to work with APIs, JSON files, timestamps, data cleaning and dashboard creation. I used Python to extract and transform the data and then Power BI to build the visualizations.

Tools
Python
Pandas
Requests
Jupyter Notebook
Power BI
OpenSky API
GitHub
What I did
Connected to the OpenSky API using OAuth2 authentication.
Requested flight data from the API.
Converted the JSON response into a Pandas DataFrame.
Cleaned and organized the data.
Converted Unix timestamps into readable dates.
Calculated flight duration in minutes.
Exported the final dataset to CSV.
Created a dashboard in Power BI.
Main columns
icao24
callsign
estDepartureAirport
estArrivalAirport
firstSeen_dt
lastSeen_dt
fecha_salida
hora_salida
duracion_minutos
Dashboard

The dashboard includes:

Total flights analyzed
Departure airports
Arrival airports
Flight duration groups
Average duration by departure airport
Results
798 flights analyzed
321 departure airports
Average duration: 25.83 minutes
Maximum duration: 58.48 minutes
What I learned

This project helped me understand:

How APIs work
JSON structures
Date and time transformations
Data cleaning with Pandas
Basic Power BI dashboards
Working with real aviation data
Future improvements

For this project I only analyzed one hour of flight data. In future versions I would like to:

Analyze 24 hours of operations
Compare several days
Create route analysis
Add more aviation KPIs
Build more advanced dashboards
Author

Fernando Matías Toranzos

English Teacher, Aviation Professional and Data Analyst in training.
Focused on aviation data, Python, SQL and Power BI.
