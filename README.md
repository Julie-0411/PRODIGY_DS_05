# Traffic Accident Analysis

This repository contains data and analysis related to traffic accidents in various states/union territories (UTs) of India. The dataset includes information such as the number of accidents per month for each state/UT, spanning several years.

## Dataset

The dataset consists of the following columns:

- **STATE/UT**: Name of the state or union territory.
- **YEAR**: Year of the data record.
- **JANUARY** to **DECEMBER**: Number of accidents in each month of the respective year.
- **TOTAL**: Total number of accidents for the year.

## Analysis

### Visualizing Accident Hotspots

To visualize accident hotspots, latitude and longitude coordinates were generated for each state/UT using geocoding (with fallback to random values for missing data). A scatter plot was created to represent accident hotspots across different regions.

![image](https://github.com/Julie-0411/PRODIGY_DS_05/assets/156679415/7d4c5306-71b5-4394-95bd-3c3c2e9b248c)


### Generating a Map of Accident Hotspots

Additionally, a map was generated using `folium` to display the accident hotspots based on the generated latitude and longitude coordinates.

![image](https://github.com/Julie-0411/PRODIGY_DS_05/assets/156679415/c3b13327-8811-42bf-9dba-b05339cac835)


## Usage

You can use this dataset and analysis to:

- Identify patterns and trends in traffic accidents over time.
- Explore accident hotspots across different states/UTs.
- Conduct further analysis to understand contributing factors to accidents.

## Dependencies

- Python 3
- pandas
- numpy
- matplotlib
- folium
- geopy
