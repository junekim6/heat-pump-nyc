# Heat Pump Adoption in New York State
Read the full story here: [From Icy to Spicy: Heat Pumps Are The Hottest Thing in Sustainable Energy, But New York Lags Behind The Trend.](https://junekim6.github.io/heat-pump-nyc/)

## Overview
Heat pumps have been receiving increased attention among scholars and advocates for their astonishing energy efficiency and promising potential to address climate concerns. However, survey data from U.S. Energy Information Agency shows that New York State, despite potential benefits, lags behind other states in heat pump adoption.

The story examines the current global and U.S. market sales of heat pumps over the years and explains why New York has been slow to adopt heat pumps as means for heating homes.

In order to make the mundane topic more visually engaging, I have hand drawn all illustrations and graphs. All charts are first created with ggplot and then traced afterward, to ensure the integrity of the data represented.

## Data Sources and Definitions
- **Heat pump shipments in the U.S.** - [Air Conditioning, Heating and Refrigeration Institute.](https://www.ahrinet.org/)
    - While this represents not sales, but shipments of heat pumps, it was used to represent sales of heat pumps within the United States. It is assumed that shipments closely track sales, thereby a useful proxy measure to assess sales. However, this does not distinguish between residential or commercial usage.
    - Data can be found in the `data` folder under file name `heat-pump-national-shipment.csv`
- **Breakdown of New York City's greenhouse emissions** - [New York City GHG Inventory](https://nyc-ghg-inventory.cusp.nyu.edu/)
    - "Stationary emissions" was translated to "buildings" in the graph to assist in better understanding from readers.
    - Data can be found in the `data` folder under file name `NYC_GHG_Inventory`.
- **Heatpump usage by state** - [U.S. Energy Information Administration 2022 Residential Energy Consumption Survey (RECS)](https://www.eia.gov/consumption/residential/)
    - RECS data from EIA is the only national-level survey data that shows the rate of heat pump adoption in each state. However, data was withheld from 16 states "because either the relative standard error (RSE) was greater than 50% or fewer than 10 households were in the reporting sample." Therefore, these states were excluded from the analysis.
    - More comprehensive data is needed to accurately assess each state's progress in heat pump adoption.
    - Data can be found in the `data` folder under file name `states_heat_pump.csv`
    <img src="/docs/hp_map.png" width="80%" height="80%"/>

## People Interviewed
- Sam Calisch, head of special projects at Rewiring America.

## Folders
The `data` folder includes all notebooks for data cleaning and exploratory visualizations.

## Contact
Please reach out to mk4672@columbia.edu with any questions or concerns.
