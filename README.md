# mlb_attendance_prediction


## The Purpose
We seek to build a means to accurately forecast the upcoming game attendance levels so we can make informed decisions on methods to augment the attendance. Live attendance at MLB stadiums is a vital link between the fans and the team generating $4Bn annual revenue.


## Data
The data comes from two sources:
* www.baseball-reference.com (game data from 2008 to 2019)
* https://www.wikiwand.com/en/List_of_current_Major_League_Baseball_stadiums (attributes about the 30 mlb stadiums such as capacity, roof type, turf type)


## How To Run

- Run notebook 02.01.01-data_wrangling.ipynb, this will scrape the web for the game statistics
- Run notebook 02.01.02-data_wrangling.ipynb, this will import the stadium attributes and join the datasets
- Run notebook 02.03.01-data_exploration.ipynb, this will run the EDA and write a file
- Run notebook 03.01_Data_Preparation.ipynb, this will remove features and prepare the data for the models
- Random Forest Model, 04.02_Random_Forest_Regressor.ipynb
- XGBoost Model, 04.02_XGBOOST_Regressor.ipynb
- Stochastic Gradient Descent Regression, 04.03_SVR_Regressor.ipynb 


## Model Parameter Files 
https://github.com/mrpalazz/mlb_attendance_prediction/blob/main/documents/Model%20Parameters%20File.txt

## Project Location
https://github.com/mrpalazz/mlb_attendance_prediction/edit/main
