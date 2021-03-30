# Machine Learning MPG API

## Usage
This API contains all the API code in the main.py file. It only has two routes, /ping and /predict. The /ping is a GET route and simply pings the API to ensure the server starts. The /predict route is a POST route and uses the trained model saved in the model.bin file. It takes in a vehicle config and uses that as one of the parameters for the prediction and returns the result as a JSON object. Also included are the jupyter notebook files that were used for data exploration, analysis, and modeling. 

## Data Set Information
The data set that was used was concerning fuel consumption in miles per gallon and can be found at http://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data

## Main Libraries
The main libraries used for this project were numpy, pandas, matplotlib, seaborn, and sklearn.

##Data Science Topics Covered
*Data Collection
*Exploratory Data Analysis
*Data Preperation
*Model Selection and Training
*Cross-Validation and Hyperparamater Tuning
