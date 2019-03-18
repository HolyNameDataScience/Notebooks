
# README

This file is a meeting agenda. (data is coming soon)



### 1. Questions about DataRobot:

#### How to improve the performance of time series models with DataRobot?


```

**Problem:** how to predict patients' next Expenditure Change Ratio based on their historical data?

**Expenditure Change Ratio:** new expenditure amount/previous expenditure amount - 1.0

**An Example:** Patient A has historical medical records on 2017/1/1, 2017/3/14, 2017/4/5, 2018/4/5, and 2018/12/1. We would like to predict his/her next expenditure after the last records.)

**Sample Data:**
train: 153 patient historical expenditure time series and their basic informations (patient_time_series_train.csv)
test: most recent expenditure (patient_time_series_test.csv)


**DataRobot: featureList:**

1. patientID (catergorical 153 categories)
2. payment date (date)
3. payment rate of change
Expenditure Change Ration: current expenditure / last time expenditure
 (compare to last time)
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


