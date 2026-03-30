# Fire Weather Index Prediction

Built a Machine Learning regression system to predict the Fire Weather Index (FWI) using daily weather conditions and FWI component indicators from two Algerian regions for the year June–Sept 2012.

The model learns how factors like temperature, humidity, wind speed, rainfall, and fuel moisture codes influence wildfire severity risk. Evaluated multiple regression techniques and selected Ridge Regression with cross validation based on performance with R2 ≈ 0.98, MAE ≈ 0.56.

Built a Flask web app to input real time values and instantly generate the predicted FWI for early fire risk assessment and deployed it on Render. 
Link - https://fireweatherindex-prediction.onrender.com/
