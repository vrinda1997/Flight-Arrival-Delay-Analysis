# Flight-Arrival-Delay-Analysis
This project aim to represent flight arrival delays for 18 airlines in the United States

## Libraries 
 Pandas, matplotlib and Basemap libraries
 
 ## Dataset
 Contains 40,000 records, which represent flight arrival delays for 18 airlines in the United States. Each row in the dataset represents a summary of delay data for a     carrier-airport pair for the specified month. 
 The dataset was created in January 2021 and contains data from January 1, 2018 to December 31, 2019 sourced from the Bureau of Transportation Statistics.

## Data Analytics Tasks
Perform the following tasks in Python using the delays_2018.csv, delays_2019.csv and airport_coordinates.csv datasets available from this GitHub repo.
 1. Read the CSV files containing the airline delay data into a single DataFrame. Then displayed the total number of rows imported.
 2. Changed the date column to date format YYYY-M . Then performed exploratory data analysis on the imported dataset to identify invalid data — written code to                 remove the impacted rows. Finally, displayed the number of rows remaining.
 3. Displayed a list of all Tennessee airports that appear in the dataset.
 4. Imported the coordinates dataset and merged it with the existing dataset. Plotted the coordinates of all airports on a map using Matplotlib and Basemap.
 5. Displayed the number of diverted flights for each carrier-airport pair.
 6. Displayed how many arrivals into JFK in 2019 encountered both weather and carrier delays.
 7. Displayed the airline with the most flight cancellations as a percentage of total arriving flights.
 8. Determined the overall average number of delays per airport.
 9. Displayed the three carriers with the lowest number of delayed flights.
 10 Requested that the user input an airline. Then plotted the monthly number of national air system (NAS) delay minutes for that airline. Displayed whether the trend is increasing or decreasing over the last 2 months.
