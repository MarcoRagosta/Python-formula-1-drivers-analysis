# F1 Analytics - 2008 Formula 1 Driver Performance Analysis

## Project Description

The **F1 Analytics** project aims to analyze the performance of drivers and teams in the 2008 Formula 1 World Championship, using data from the file `formula1_data.csv`. This dataset contains detailed information on drivers, constructors, race locations, and the results (finishing positions) of each Grand Prix.

Based on the provided data, various functions will be implemented to provide a comprehensive analysis of points, wins, and podiums both at an individual level for drivers and at a team level for constructors.

## Dataset

The dataset `formula1_data.csv` (downloadable from [here](https://proai-datasets.s3.eu-west-3.amazonaws.com/formula1_data.csv)) contains the following columns:

1. **Driver**: Name of the driver.
2. **Team**: Name of the constructor/team for which the driver competes.
3. **Race**: City where the Grand Prix took place.
4. **Country**: Country where the Grand Prix took place.
5. **Position**: The position the driver finished in (0 means the driver did not finish in the top 8 and thus did not earn points).

## Scoring System

At the end of each Grand Prix, points are awarded to the drivers based on their finishing position as follows:

- **1st place**: 10 points
- **2nd place**: 8 points
- **3rd place**: 6 points
- **4th place**: 5 points
- **5th place**: 4 points
- **6th place**: 3 points
- **7th place**: 2 points
- **8th place**: 1 point
- **9th place or lower**: 0 points

## Project Objectives

This project includes the following key functionalities:

### 1. **Driver Performance Analysis**

A function that takes the name of a driver as input and returns a list with the following key information:
- The total points accumulated by the driver throughout the championship.
- The number of wins (how many times the driver finished in 1st place).
- The number of podiums (how many times the driver finished in the top 3).

This function will help analyze individual driver performance and provide a clear overview of their positions throughout the season.


### 2. **Final Driver Standings**

A function that generates a dictionary with driver names as keys and their total points as values. The dictionary will then be used to create a general driver standings table.


### 3. **Constructor Standings**

A function that creates a dictionary with team/constructor names as keys and their total points as values. The points for each team are calculated as the sum of the points scored by the drivers who competed for that constructor.

This function is crucial to assess the overall performance of teams during the season.


## Delivery Mode

- A public Google Colab notebook link will be provided for executing the project and running the analysis.

---

**Feel free to explore the project and analyze the performance of F1 drivers and teams in the 2008 season!**

