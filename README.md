# CPT-predictor

## Crossing Point Temperature
Crossing point temperature (CPT) is the temperature at which the coal temperature coincides with that of the furnace temperature or bath temperature in °C. CPT or critical oxidation temperature gives an idea about the proneness of coal to auto oxidation or self-heating. This is a standard method followed in India for finding out the susceptibility of coal to spontaneous combustion. The higher the crossing point temperature value, the less will be the susceptibility of coal to spontaneous heating.


## Objective
To assess the spontaneous combustion susceptibility of coal using Machine learnin project and correlate its intrinsic properties with susceptibility indices. The work is divided into four parts as follows:
1) Sample collection and preparation according to standard procedures.
2) Determination of the intrinsic properties of the collected coal samples using
proximate analysis and bomb calorimetry.
3) Determination of spontaneous heating susceptibilities by Crossing point
temperature(CPT) test and wet oxidation potential(WOP) analysis.
4) Correlation of spontaneous heating susceptibilities indices with that of the
intrinsic properties.

## Parameter used for Machine Learning Model
● Moisture (%wt)
● Ash (%wt)
● Volatile Matter (%wt)
● Fixed Carbon (%wt)
● C (%wt)
● H (%wt)
● N (%wt)
● S (%wt)
● O (%wt)
● Calorific Value (MJ/kg)
● Vitrinite Reflectance (VRm)


## Model Performance

#### Model - RandomForestRegressor

1) Training R-squared (R²): A measure of how well the model explains the variability
in the training data. A value of **0.96** indicates a very good fit.
2) Training Explained Variation: This is another measure of how well the model
explains the variation in the training data. A value of **0.96** suggests that **96%** of
the total variation in the training data is explained by the model.
3) Training MAPE (Mean Absolute Percentage Error): An average of the absolute
percentage errors between predicted and actual values. A lower value **(1.38)**
indicates good accuracy in predictions.
4) Training Mean Squared Error (MSE): Measures the average squared difference
between predicted and actual values. A value of **6.83** indicates relatively low
error.
5) Training RMSE (Root Mean Squared Error): The square root of the MSE,
providing a measure of the spread of errors. A value of **2.61** is relatively low.
6) Training MAE (Mean Absolute Error): Measures the average absolute difference
between predicted and actual values. A value of **2.15** indicates relatively low
error.
