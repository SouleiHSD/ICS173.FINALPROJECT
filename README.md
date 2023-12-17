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

