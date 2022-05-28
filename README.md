# Smart-Farming
Smart Farming System is an IOT project which predicts the weather conditions using ML, provides mobile notification to the farmer about the water level in the soil and detects fire in the farm.

In this project we are using MQ2 Gas Sensor Module, DHT11 Temperature & Humidity Sensor Module, Soil Moisture Sensor Module with Raspberry pi 3b.
By getting humidity and temperature from DHT11 module we are predicting the weather conditions using machine learning using Weather3.csv file in which we have humidity, temperature, pressure, weather.
Fire alert is checked using MQ2 gas module.
Water present in soil is checked using Soil moisture module.
All these notifications are send to the mobile through Pushetta. 

