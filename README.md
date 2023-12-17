# ICS173.FINALPROJECT

Smithsonian_VOTW_Holocene_Volcanoes.csv

![DataVisualization SplatterPot Volcanoes Smithsonian](https://github.com/SouleiHSD/ICS173.FINALPROJECT/assets/143763873/19b74487-ecf6-446b-b9ac-62006a376330)

# Smithsonian VOTW Holocene Volcanoes Dataset

This repository contains a dataset from the Smithsonian Institution's Volcanoes of the World (VOTW) project, specifically focusing on Holocene volcanoes. The dataset provides information about various volcanoes that have been active during the Holocene epoch.

## Overview

The dataset is in CSV format and includes the following columns:

- `Volcano Number`: Unique identifier for each volcano.
- `Volcano Name`: Name of the volcano.
- `Country`: Country where the volcano is located.
- `Primary Volcano Type`: The primary classification of the volcano.
- `Activity Evidence`: Evidence of recent activity.
- `Last Known Eruption`: The date of the last known eruption.

## Data Source

The dataset is sourced from the Smithsonian Institution and is publicly available. You can find the original dataset [here](https://gist.githubusercontent.com/mattkram/9684863843254402942dfede27af2cb7/raw/2590dd8185b833aacf247c0595edbb07a025a6d7/Smithsonian_VOTW_Holocene_Volcanoes.csv).

## Usage

To use this dataset, you can read it into a Pandas DataFrame using the following code:

```python
import pandas as pd

url = 'https://gist.githubusercontent.com/mattkram/9684863843254402942dfede27af2cb7/raw/2590dd8185b833aacf247c0595edbb07a025a6d7/Smithsonian_VOTW_Holocene_Volcanoes.csv'
df = pd.read_csv(url)

# Now you can explore and analyze the data using Pandas

This dataframe appears to describe information about volcanoes, including their names, locations, geological characteristics, and other related details. Here is a brief description of each column:

1. FID: This column is of object type and likely represents a unique identifier for each row in the dataframe.
2. Volcano_Number: This column is an integer and likely represents a unique identifier for each volcano.
3. Volcano_Name: This column is of object type and contains the names of the volcanoes.
4. Primary_Volcano_Type: This column is of object type and describes the primary type or classification of each volcano.
5. Last_Eruption_Year: This column is a float and represents the year of the last eruption for each volcano.
6. Country: This column is of object type and indicates the country where each volcano is located.
7. Geological_Summary: This column is of object type and provides a summary or description of the geological characteristics of each volcano.
8. Region: This column is of object type and represents the region where each volcano is located.
9. Subregion: This column is of object type and provides a more specific subregion within the region for each volcano.
10. Latitude: This column is a float and represents the latitude coordinate of each volcano.
11. Longitude: This column is a float and represents the longitude coordinate of each volcano.
12. Elevation: This column is an integer and indicates the elevation of each volcano.
13. Tectonic_Setting: This column is of object type and describes the tectonic setting or context in which each volcano is located.
14. Geologic_Epoch: This column is of object type and represents the geologic epoch or time period associated with each volcano.
15. Evidence_Category: This column is of object type and categorizes the evidence available for each volcano.
16. Primary_Photo_Link: This column is of object type and contains a link to the primary photo associated with each volcano.
17. Primary_Photo_Caption: This column is of object type and provides a caption or description for the primary photo of each volcano.
18. Primary_Photo_Credit: This column is of object type and credits the source or author of the primary photo.
19. Major_Rock_Type: This column is of object type and describes the major rock type associated with each volcano.
20. GeoLocation: This column is of object type and provides a general geolocation description for each volcano.

Potential use cases for this dataframe include:
1. Volcano Mapping: The latitude and longitude columns can be used to plot the volcanoes on a map, providing a visual representation of their distribution.
2. Eruption Analysis: The last eruption year column can be used to analyze the frequency and patterns of volcanic eruptions over time.
3. Geologic Classification: The primary volcano type and major rock type columns can be used to classify and categorize the volcanoes based on their geological characteristics.
4. Regional Analysis: The region and subregion columns can be used to analyze and compare volcanic activity in different geographic areas.
5. Risk Assessment: The elevation and tectonic setting columns can be used to assess the potential risk and impact of volcanic activity in different regions.
6. Data Visualization: The dataframe can be used to create visualizations such as bar charts, maps, and scatter plots to explore and communicate insights about volcanoes and their characteristics.

