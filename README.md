
# README

This file is a meeting agenda. (data is coming soon)



### 1. Questions about DataRobot:

-- How to improve the performance of time series models with DataRobot
( For example, patient 1 has medical records on 2017/1/1, 2017/3/14, 2017/4/5, 2018/4/5, and 2018/12/1. We would like to predict his/her medical conditions after the last records. )

Sample Data: 
train: patient_time_series_train.csv
test: patient_time_series_test.csv


```
problem: to predict patient next Expenditure Change Ratio based on their expenditure history and fundamental records

Expenditure Change Ration: current expenditure / last time expenditure


train: 153 patient historical expenditure time series and their basic informations
test: most recent expenditure


DataRobot: featureList:

1. patientID (catergorical 153 categories)
2. payment date (date)
3. payment rate of change (compare to last time)
4. most recent diagnosis code (as text)
5. number of primary diagnosis codes during life time
6. zip code
7. sex
8. race
9. current age


```


### 2. Two Case Studies and Relevant Questions:


#### Case Study I (Regression)

https://nbviewer.jupyter.org/github/HolyNameDataScience/Notebooks/blob/master/case1.ipynb


#### Case Study II (Classification)

https://nbviewer.jupyter.org/github/HolyNameDataScience/RDMeetingMaterials/blob/master/caseII.ipynb

### 3. General Questions:

TensorFlow Models


