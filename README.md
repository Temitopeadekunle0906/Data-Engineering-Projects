# Data-Engineering-Projects
Telios Autos Case study
Telios is an electric car company. The company has decided to expand its portfolio and enter the automated driving market 
and has just just announced the launch of their brand new line of self-driving car that relies primarily on an artificial intelligence model. 
The new product will be tested in the five locations where the assembly factories are situated - Brussels, New York, Tokyo, Sydney, and Paris


To design this model, the data science team have requested weather metrics data from the five cities in which the product will be initially tested. 
Weather metrics data is required to build an AI model for the vehicle that can address and react accordingly to various weather conditions as picked 
up from sensors in the vehicle.The weather data must include but not limited to:
* Date: Date which the data is captured from.
* Max. temp(C): Maximum daily temperature in celsius
* Avg. temp(C): Average daily temperature in celsius
* Min. temp(C): Minimum daily temperature in celsius
* Wind speed: Wind speed in kph
* Rainfall: Daily rainfall measure in millimeters
* Visibility: Daily average optical clarity or visibility measured in kms
* Humidity: This refers to the daily average humidity 
* Description: Short descrition of the daily weather

You have been tasked to prepare a dataset fetched from an external API, processed and stored in a PostgreSQL database. The API provides JSON data that 
you will need to parse and transform before inserting it into the database. You will also need to write scripts to perform CRUD operations on the database, 
and batch load data into your database.

You are to use the WeatherAPI API provision to extract your data
Your database should have 5 tables, one for each of the testing locations
Brussels, Belgium
New York City, United States
Tokyo, Japan
Sydney, Australia
Paris, France
Collect daily historic data from June 2022 to March 2023, ie one table row per day.


