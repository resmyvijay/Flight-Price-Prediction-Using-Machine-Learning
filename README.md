## Flight Price Prediction
This project is about using a machine learning model to predict flight prices, given a dataset of flight data.

### Data Dictionary

#### Variable	Description

Airline	- The name of the airline

source -	The date of the journey

Destination -	The destination where the service ends.

Route -The route taken by the flight to reach the destination.

Dep_Time -	The time when the journey starts from the source

Arrival_Time -	Time of arrival at the destination.

Duration -	Total duration of the flight.

Total_Stops -	Total stops between the source and destination.

Additional_Info -	Additional information about the flight

Price -	Target, The price of the ticket()

### MACHINE LEARNING MODELS

LINEAR REGRESSION

RMSE: -0.15382690702196586

RANDOM FOREST REGRESSION

RMSE: -0.08553874202794202

ADA BOOST REGRESSOR

RMSE: -0.28852171860706

XGB REGRESSOR

RMSE: -0.0778318696839152

### Random Forest Regressor displayed a low 'rmse' score compared to other regression models. hence it is used for predicting the test dataset 'price'



#### RMSE between the predicted price(y_pred) and the observed price(y_true) is calculated using the formulae:

-np.sqrt(np.square(np.log10(y_pred +1) - np.log10(y_true +1)).mean())
