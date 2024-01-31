**CTA Database Navigator**

## Project Overview
This Python project is a terminal application designed to allow users to analyze and retrieve information from the CTA2 L Daily Ridership database. Developed as part of the CS 341 course during the Spring 2024 semester at the University of Illinois Chicago, this project provides a set of commands for users to explore various statistics and analytics related to the CTA ridership.

The database file used for this program can be found at:

https://drive.google.com/file/d/1LlVIpJ-m1bfYTGnJRyVu-HZac-xoh0ho/view?usp=sharing

## How to Use
The application offers a menu of commands (1-9) that users can input to perform specific analyses on the CTA L ridership data. Users can enter commands to retrieve information about stations, ridership percentages, plot trends, and more.

## Dependencies
- SQLite3: Used for SQL database queries.
- Matplotlib: Used for dynamic visualization and plotting of data.

## Command List
Find Stations by Name: Allows users to find station names matching a partial name.
Analyze Ridership by Station: Provides the percentage of ridership on weekdays, Saturdays, and Sundays/holidays for a given station.
Total Weekday Ridership by Station: Outputs total ridership on weekdays for each station.
Stops for Line and Direction: Outputs stops for a specified line color and direction.
Number of Stops by Color and Direction: Displays the number of stops for each line color, separated by direction.
Yearly Ridership at Station: Outputs the total ridership for each year for a specified station and allows plotting of the data.
Monthly Ridership at Station: Outputs the total ridership for each month in a specified year for a station and allows plotting of the data.
Compare Daily Ridership for Two Stations: Outputs the total ridership for each day in a specified year for two stations and allows plotting of the data.
Find Stations Within a Mile: Finds all stations within a one-mile square radius of specified latitude and longitude and allows plotting of the stations on an OpenStreetMap of Chicago.

## Database Connection
The application connects to the 'CTA2_L_daily_ridership.db' SQLite database to retrieve and analyze ridership data.

## Notes
- Ensure valid input for latitude and longitude within the bounds of Chicago.
- Some commands offer the option to plot data for visual analysis using Matplotlib.
- Feel free to explore and analyze CTA L ridership data using the provided commands.
