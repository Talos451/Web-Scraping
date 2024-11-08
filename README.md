Weather Data Analysis Project
Project Overview
This project dives into October weather data from 2022 to 2024 for several weather stations in New Jersey, focusing on temperature trends and cumulative precipitation. The goal is to spot extremes, frost dates, and overall precipitation levels, with a look at how elevation might influence weather patterns.

Data Source
All weather data was scraped from Weather Underground. You can check out the source here.

Repository Contents
Jupyter Notebook (web_scraping.ipynb): The main notebook that runs the whole project. This includes:

Generating URLs based on station ID, year, and month.
Web scraping functions to grab weather data from each URL.
Data processing, like calculating cumulative precipitation.
Visualizations that call out key data points like max/min temperatures and cumulative precipitation for each year.
Raw Data Files:

CSV files containing raw data for each station, named by station ID, year, and elevation (e.g., KNJLEDGE1-2024-1030.csv).
I included these, even though you can generate them through the main notebook file.


Project Goals
Find the maximum and minimum temperatures and precipitation amounts each year.
Tag dates with significant weather events, like the first frost.
See if elevation has any connection to the weather data.
Visualizations and Outputs
Each plot shows:

Cumulative precipitation or daily temperatures over the month of October.
Key points like the highest precipitation or frost dates, marked for clarity.
Titles that sum up the primary finding for each year, making trends easy to spot.
How to Use
Data Files: These are here for anyone who wants to dig deeper into the raw data.
Notebook: Run web_scraping.ipynb to see the code, plots, and analysis steps in action.
CSV files are also uploaded in case the website is down and you are unable to scrape new data. 
