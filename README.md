# Seoul Bike Sharing Demand Prediction
**AlmaBetter Verfied Project** 
![seoul](https://user-images.githubusercontent.com/100474431/173244075-5ddd62c3-b038-4566-80d7-0a648fcee573.jpeg)

# **Problem Statement**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# **Data Description**

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

# **Data Pipeline**

● Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

● Data Processing: In this part we went through each attributes and encoded the categorical features.

● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

# **Conclusions**

● When we compare the root mean squared error and mean absolute error of all
the models, the random forest regression model has less root mean squared error
and mean absolute error, ending with the R-squared of 99% . So, finally this
model is best for predicting the bike rental count on daily basis.

● For all the models, temperature or hour was ranked as the most influential
variable to predict the rental bike demand at each hour.
