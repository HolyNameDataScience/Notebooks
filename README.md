
# README

This file is a meeting agenda. (data is coming soon)



### 1. Questions about DataRobot:

-- How to imporve time series model's performance with DataRobot ( will add a problem description and sample data)

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


