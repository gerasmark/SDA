# Reporting Service 
## Project Overview
Our web application is a comprehensive system designed to manage and retrieve sensor readings of temperature, humidity, and acoustic data. It seamlessly integrates MongoDB Cloud Atlas for data storage and MongoDB Compass for efficient database management. The backend server is powered by Python with Django, providing robust functionality and a user-friendly API.There are three REST API endpoints. The first one gives you all the sensor readings. The second one filters the database with fields:sensor type, sensor location, time. The third one gives you important metrics about the sensor: mean value,min value, max value, range of values and the maximum and minimum ten recorded values.
## REST API Endpoints
Retrieve All Sensor Readings
Endpoint: sensorReadings/, Get Requet
Description: Access all available sensor readings, providing a comprehensive view of your data.
Filtered Data Retrieval
Endpoint: /sensorReadings, Post Request
Description: Easily filter data based on specific criteria, including sensor type, location, and time, allowing you to retrieve relevant information tailored to your needs.
Sensor Metrics
Endpoint: /sensorMetrics/
Description: Obtain vital metrics for your sensor data, including mean value, minimum value, maximum value, range of values, and the top ten recorded values. This feature simplifies data analysis and decision-making.
