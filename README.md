# House Price Prediction Model
The aim of this project is to predict a house price based on the various features like the income, area-population, longotide and latitude, number of rooms and other similar factors using machine learning. RendomForestReggresor estimator is used after trying multiple estimator. We meausre the accuracy or score in terms of MAE(mean absolute error) whcih is 31500 and the house value range from 10,0000 to 50,0000 so overall our prediction is deviated by 18%. 

### Tools and Technologies
- Data Pre-processing : Numpy and Pandas
- Data Visualization : Matplaotlib and pandas
- Modeling and Evoluation  : Scikit-learn
- File Habdling Modules: tarfile and urllib

### Data 
- Sourse : https://raw.githubusercontent.com/ageron/handson-ml2/master/datasets/housing/housing.tgz

This model is used data from the 1990 California census, this is small dataset from StatLib repository. these are the following features of datasets:
| Features             |   types   | 
|----------------------|-----------|
|longitude             |float64|
|latitude              |float64|
|housing_median_age    |float64|
|total_rooms           |float64|
|total_bedrooms        |float64|
|population            |float64|
|households            |float64|
|median_income         |float64|
|median_house_value    |float64|
|ocean_proximity       |object |

### Model Evolution 
We use Mean Absolute Error as the performace measure, we also calculate the RMSE and MSE to get better idea. we stpit the whole data set in two part test_set(20%) and train_set(80%), for spliting the data we use stratified sampling to avoid any baise in both the samples.

- Mean Absolute Error is  31598.46
- Mean Square Error is  2306019441.74
- Root Mean Square Error is  48021.031

Actual House value is range from 100000 to 500000. overall are predicted result is deviated by 18% from the actual result.

