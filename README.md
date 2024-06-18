# Exploratory Data Analysis of Renewable Power Plants in the UK

## 1. Feature Construction and Transformation:

The project consists of meticulous feature construction and transformation to ensure comprehensive analysis. The dataset comprises several essential columns including:

- `electrical_capacity`: The electrical capacity of the power plants.
- `energy_source_level_1`, `energy_source_level_2`, `energy_source_level_3`: Hierarchical classification of energy sources.
- `technology`: The technology utilized in the power generation process.
- `data_source`: Source of the data.
- `region_1`, `region_2`, `region_3`: Geographic regions.
- `longitude`, `latitude`: Geospatial coordinates of the power plants.
- `municipality`, `postcode`, `address`, `region`, `country`: Location information.
- `commissioning_date`: Date when the power plant was commissioned.
- `solar_mounting_type`: Type of mounting used for solar plants.
- `combined_heat_power`: Indicates if the power plant is combined heat and power (CHP).
- `capacity_individual_turbine`, `number_of_turbines`: Details regarding individual turbines.
- `site_name`, `uk_beis_id`, `operator`, `comment`: Additional descriptive information.

## 2. Graphical Representation:

The heart of this project lies in the graphical representation of data, facilitating intuitive interpretation and exploration. Various questions were posed, and corresponding charts were generated to provide insights:

- Total Electrical Capacity recorded in the data.
- Number of sites included in the data.
- Count of Power Plants built from 1992 to 2020.
- Distribution of energy sources across the UK.
- Relationship between the number of power plants and total electrical capacity.
- Average capacity of all energy sources in the dataset.
- Trend analysis of the capacity of individual turbines over the years and its contribution to overall energy capacity.
- Most commonly used renewable energy sources in the UK.

## 3. Summary Report:

- Significant growth in the number of power plants and their electrical capacity from 1992 to 2020.
- Clear trends indicating newer turbines have higher electrical capacity compared to older ones.
- Renewable energy sources, particularly solar and wind, dominate the energy generation landscape in the UK.
- Positive correlation between the number of power plants and overall electrical capacity, indicating a steady increase in renewable    energy capacity over time.
- Country with more land area and territorial sea has more numbers of power plants.

Original dataset can be found on Kaggle at - https://www.kaggle.com/datasets/24842a1a4c389a65d99683099aa3dc9d9f8f2f0e55878a0c85aa775acc9c135c