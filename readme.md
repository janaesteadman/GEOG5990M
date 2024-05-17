# Background

This project aims to explore the relationship between the availability of green spaces and various demographic variables across the London boroughs. Urban green spaces are vital for the well-being of city residents, providing numerous health, environmental, and social benefits (World Health Organization. Regional Office for Europe, 2016). Understanding how these green spaces correlate with different demographic factors such as education levels, age groups, and employment status can inform urban planning and policy-making, helping to create healthier and more equitable urban environments.

# Data

The GitHub repository contains the following datasets and files:
London Boroughs Data: This is a spatial dataframe that contains information on London boroughs. 
The dataset is provided in the shapefile format, which includes .shp, .shx, .dbf, and .prj files.
Green Spaces Data: This dataset includes the percentage of green spaces in each London borough.
Economic Activity: Number of residents employed, unemployed, and economically inactive in London LSOAs.
Qualifications: Number of residents with different education levels in London LSOAs.
Age: Number of residents in different age groups in London LSOAs.

# Code

The code in this repository aims to:
Clean and Process Data: Ensure the datasets are in the correct format for analysis.
Perform Correlation Analysis: Calculate and interpret correlation coefficients to quantify the relationships between green spaces and demographic variables.
Generate Bivariate Choropleth Maps: Create visualizations that illustrate the relationships between green spaces and various demographic variables with strong correlations across London boroughs.

# Further Information

To successfully run the code and reproduce the analysis, users should ensure they have the necessary Python environment set up, including all required libraries specified in the code. 
Users should verify that they have appropriate data files in the correct format and directory structure as outlined above. 

Additionally, the install system dependencies command to generate the bivariate chloropleth map is used for Debian based systems such as google colab. 
The code provides different commands for alternate operating systems.

# References

World Health Organization. Regional Office for Europe 2016. Urban green spaces and health. iris.who.int.
