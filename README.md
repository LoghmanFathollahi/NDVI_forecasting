# Global NDVI Forecasting 3 from Air Temperature, Soil Moisture and Precipitation Using a Deep Neural Network
# This code includes two phases. In the first phase, we load and prepare the data stored in the 'monthly_features.csv' file. This data will be used to create train-test datasets for subsequent analysis. The 'monthly_features.csv' file contains these data:
# The monthly mean of soil moisture (m3/m3), the aggregate of monthly precipitation in (mm), the Monthly mean of temperature, the Monthly mean of NDVI, and the difference between the monthly mean of NDVI in the current month and the previous month. This data comes from 
# CYGNSS soil moisture: https://podaac.jpl.nasa.gov/dataset
# Precipitation: PERSIANN-CDR
# Temperature: https://www.copernicus.eu/en/access-data
# After normalizing the data we move to the second phase. The second phase includes defining the deep learning structure, building the model, training the model, and evaluating the model.
# Note: The current file 'monthly_features.csv' just includes the year 2018 of the whole dataset.
