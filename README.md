# PRODIGY_DS_01
This Python script demonstrates how to visualize the population density of countries using data from the "world_population.csv" dataset. The script uses pandas for data manipulation and matplotlib for plotting.

## Requirements
1. Python 3.x
2. pandas
3. matplotlib

## Usage
Ensure you have the "world_population.csv" file in the same directory as the script.

## Script Explanation
#### Load the Dataset: 
Reads the "world_population.csv" file into a pandas DataFrame.

#### Data Exploration: 
Displays the information about the DataFrame using df.info() and lists all columns using df.columns.

#### Data Sorting: 
Sorts the DataFrame by 'Density (per km²)' in descending order to find the top 20 countries by population density.

#### Visualization: 
Creates a bar chart using matplotlib to visualize the population density of the top 20 countries. Each bar represents the population density (people per square kilometer) of a country.
