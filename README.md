ETL Pipeline Using OpenWeather API – Real-Time Weather Data Analysis for Selected Nigerian Cities

Project Overview

This project demonstrates the development of a simple ETL (Extract, Transform, Load) pipeline using the OpenWeather API. The pipeline automatically retrieves real-time weather data for selected Nigerian cities, cleans and transforms the data into a structured format using Python and Pandas, stores the processed data as a CSV file, and performs basic exploratory analysis.

The project was completed as part of the AnalystLab Africa Data Analytics Internship – Week 7 Project.

Business Problem

Organizations in sectors such as agriculture, transportation, logistics, aviation, and disaster management rely on accurate and timely weather information for effective decision-making. Raw weather data obtained from APIs often requires extraction, cleaning, transformation, and storage before it can be used for analysis. This project addresses that challenge by building an ETL pipeline that automates the collection and preparation of weather data.

Project Objectives

* Connect to the OpenWeather API using Python.
* Extract real-time weather data for Kaduna, Lagos, and Abuja.
* Clean and transform the extracted data using Pandas.
* Store the processed data as a CSV file.
* Perform basic analysis by comparing temperature, humidity, weather conditions, and wind speed across the selected cities.
* Generate insights to support weather-related decision-making.

Data Source

* OpenWeather API
* https://openweathermap.org/api

Tools Used

* Python
* Pandas
* Requests
* Matplotlib
* Jupyter Notebook
* OpenWeather API

ETL Process

Extract

* Connected to the OpenWeather API using an API key.
* Retrieved weather data for Kaduna, Lagos, and Abuja.
* Extracted temperature, humidity, weather condition, wind speed, and date/time.

Transform

* Converted the API response into a Pandas DataFrame.
* Renamed columns for better readability.
* Converted the DateTime column into the appropriate format.
* Checked for missing values.
* Rounded numerical values where necessary.

Load

* Saved the cleaned dataset as a CSV file for future analysis.

Basic Analysis

The project compares:

* Temperature across cities
* Humidity levels
* Wind speed
* Weather conditions

Simple visualizations were created using Matplotlib to support the analysis.

Key Findings

* Weather data was successfully extracted for Kaduna, Lagos, and Abuja.
* Kaduna recorded the highest temperature among the selected cities.
* Lagos had the highest humidity level.
* All three cities experienced cloudy weather during data collection.
* Lagos recorded the highest wind speed.
* The ETL pipeline successfully extracted, transformed, and stored the data for future analysis.

Recommendations

* Expand the ETL pipeline to include additional cities.
* Automate data collection at regular intervals to build historical weather datasets.
* Store processed data in a database such as SQLite or PostgreSQL.
* Develop an interactive dashboard using Power BI or Tableau.
* Integrate additional weather variables such as rainfall and atmospheric pressure.
* Schedule the ETL pipeline using Task Scheduler, Cron, or Apache Airflow for continuous updates.

Repository Structure

├── weather.ipynb
├── weather_data.csv
├── requirements.txt
├── README.md

Author

Gloria C. Ubah

Data Analytics Intern – AnalystLab Africa

LinkedIn: www.linkedin.com/in/gloria-c-ubah

GitHub: https://github.com/GloriaUbah
