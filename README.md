# Canada Hydro Data Visualization

This project consists of an automated process to download individual station hydrometric (water flow) data from the 
Government of Canada Water info website <a href="https://dd.weather.gc.ca/hydrometric/csv/">[https://dd.weather.gc.ca/hydrometric/csv/](https://dd.weather.gc.ca/hydrometric/csv/)</a> and to display the results in the form of interactive charts for each
province.

Multiple .csv files from the Hydrometric .url directory are downloaded using the wget command.

Duplicate readings (overlapped dates of readings) are dropped allowing new data to be added to older
time-series data.

This project was a good template to understand ETL processes as well as Real-time data management.
Additionally, it helped understand trends in water flow rate in rivers across Canada.


