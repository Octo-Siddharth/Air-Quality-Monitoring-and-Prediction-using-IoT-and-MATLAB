# Air-Quality-Monitoring-and-Prediction-using-IoT-and-MATLAB
* PROBLEM STATEMENT: As the world is moving one step forward towards modernization, our environment is facing a sheer stress of hiked pollution. Increased amount of harmful gas like CO, NO2, CO2 and Suspended Particulate Matter (SPM) in air is leading to the reduction of air quality which ultimately affects human health and living, increasing use of fossil fuels and harmful gaseous chemicals deployment in the air are prime factors. Thus, we have though for a solution to collect real time data and process them to predict the AQI (Air Quality Index).

* SOLUTION: In this project we are using 4 gas sensors: MQ4 (Methane Gas), MQ7 (Carbon Monoxide), MQ9 (CO + CH4), MQ135 (NH3, NOx, alcohol, Benzene, smoke, CO2) connected with Node MCU (ESP8266 – WIFI module). We will connect 3 Node MCUs together using Mesh Networking. These three devices will then be connected to an ESP32 (WIFI module) by forming a master-slave configuration. After successfully deployment of the above configuration, the gas sensors will be connected with the WIFI modules (Node MCU) which will send the data to the ESP32 (master) and those retrieved data will get uploaded in Google Sheet. Now, after collecting all the real time data from the google sheet we will processing those data and feed them to the Time Series Forecasting ML model. After data processing, evaluation and visualization the model will be predicting a similar data which is based on concentration of the above gases. The real time data along with the predicted AQI will be hosted in a web site for monitoring.

* FEATURES:</br> • Mesh Networking, i.e., 3 Node MCUs will be connected together in form of (many to one connection). It will gather all the relevant sensors data and will send it to the master ESP32.</br> • Master-Slaves formation by connecting Node MCUs with ESP32. • Google Sheets will be configured as server to receive the data from the master ESP32.</br> • Server and Client protocol used along with Time Delay function for pre-processing of data before feeding the data to the ML model.</br> • Machine Learning (Time Series Forecasting ML model) will be used for predicting the data.</br> • Processed data will be hosted on website.</br>

* HELPFUL FEATURES: • AQI (AIR QUALITY INDEX) will be predicted based on past 2 weeks data. • To get complete product we will host a web site which will shows the predicted data (Air quality index in this case). • Air Quality will be monitored with the help of the prototype and thus with the prediction we can help to curb the excessive use of harmful gases in our environment. • The data stored in the server will further provide a data based on the air quality of the surrounding and help in monitoring.

* CONSTRAINTS: • A Huge amount of training dataset is required for machine learning training purpose for the model to work with precise accuracy.

# SOFTWARE USED 
* Arduino IDE</br> 
* MATLAB</br>
* Python</br>
* Google Sheets</br>
* Google Script</br>
* Visual Studio Code</br>
* HTML
* CSS

# PROJECT VIDEO

# PROJECT WEBSITE LINK
* https://air-quality-monitoring-and-prediction-using-iot-and-matlab.tiiny.site/


