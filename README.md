# House-PP

The value of a house is based on what buyers in the market will pay for it. And it depends on the buyer's preferences and needs. The typical home value of homes in the United States is $263,351.( https://www.zillow.com/home-values/ )  There are various factors that can influence the price of a house for example location , Home size and usable space, Age and condition,  etc. One of the most important factors is nebourhood area. So I have tried to develop a model that can predict the price of a house given information about the area house is located in. 


### Data

The dataset used for this model can be download from  https://www.kaggle.com/farhankarim1/usa-house-prices  

There are 5000 rowa and 7 columns in the dataset 

The dataset contains the following Columns:

- Avg. Area Income 
  - Avgerage Income of residents of the city house is located in.
- Avg. Area House Age 
  - Avgerage Age of Houses in the city house is located in.
- Avg. Area Number of Rooms 
  - Avgerage Number of Rooms for Houses the city house is located in.
- Avg. Area Number of Bedrooms 
  - Avgerage Number of Bedrooms for Houses the city house is located in.
- Area Population
  - Population of city house is located in.
- Price
  - Price that the house sold at.
- Address
  - Address for the house.
  

### Repository 

This repository mainly contains three .ipynb files 

#### Data Analysis and Visualizations.ipynb

Data analysis and visualizations are done to gain the basic information about the data, dependent variable( Price) and corrilation between various features 

#### Data Preprocessing.ipynb

The main dataset is divided into train and test sets  

Train and test data is standerdaized and stored in train.csv and test.csv respictively 

#### Regression Models.ipynb

Three different Regression Models are used i.e Linear Regression, Ridge Regression, Lasso Regression










