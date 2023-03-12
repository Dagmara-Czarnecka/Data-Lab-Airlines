# Data-Lab-Airlines
 Simulation of commercial airlines project

About Dataset
Context
Classification dataset with detailed airline, weather, airport and employment information. Optional cancellation and delay reasons for multiclass applications.

Content
This is a classification dataset with detailed airline, weather, airport and employment information. If using the included train/test precombined data, the problem is a binary classification evaluating a delayed departure. All raw data files are also included for customization of the dataset, including adding cancellation, specific delay reasons, and/or arrival delays in order to create a multiclass problem. Note: Raw files for weather include only the top 90% of airports for passenger traffic, as all weather data was downloaded manually.

Monthly data is included for 2019. The train/test sets include target encoded fields of my own addition (see the cleaning notebook in code section).

Acknowledgements
Sources:

Bureau of Transportation statistics: https://www.transtats.bts.gov/databases.asp?Z1qr_VQ=E&Z1qr_Qr5p=N8vn6v10&f7owrp6_VQF=D
National Centers for Environmental Information (NOAA): https://www.ncdc.noaa.gov/cdo-web/datasets
Banner image: Photo by Kevin Woblick on Unsplash

Inspiration
This dataset has potential for binary classification work or multiclass work. The train/test sets provided include a binary classification problem of whether a flight is delayed for departure. Raw data is provided to create a multiclass problem that could include cancellations, reasons for delay, arrival delays, and other potential studies.

Possible questions:

Perform an Exploratory Data Analysis on the data set. Which carriers are most and least reliable for on-time departure? Which airports are best and worst for on-time departures? Which features in the data set are most correlated with a departure delay?

Use the dataset to make predictions. Can you accurately predict a departure delay?

Use the raw data files to re-tool the dataset and make your own prediction problem. Can you predict the reason for departure delay? Can you predict arrival delay?
