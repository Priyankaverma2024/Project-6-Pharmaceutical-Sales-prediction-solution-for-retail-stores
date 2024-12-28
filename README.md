# Project-6-Pharmaceutical-Sales-prediction-solution-for-retail-stores
# This Project is all about End to End sales prediction of Rossmann Pharmaceuticals retail stores future sales in advance .
# This Rossmann Sales data contain : store.csv,train.csv,test.csv,submission.csv.
# The dataset used for this project contains the following columns:
Store: The store ID.
DayOfWeek: The day of the week (1-7, where 1 is Monday and 7 is Sunday).
Date: The date of the sales record.
Sales: The total sales for the given day and store.
Customers: The number of customers on the given day and store.
Open: Indicates whether the store was open (1) or closed (0) on the given day.
Promo: Indicates whether a promotional offer was active (1) or not (0) on the given day.
StateHoliday: Indicates whether the day was a state holiday (a, b, c) or not (0).
SchoolHoliday: Indicates whether the day was a school holiday (1) or not (0).
StoreType: The type of store (a, b, c, d).
Assortment: The assortment level of the store (a = basic, b = extra, c = extended).
CompetitionDistance: The distance to the nearest competitor store.
CompetitionOpenSinceMonth: The month when the nearest competitor store opened.
CompetitionOpenSinceYear: The year when the nearest competitor store opened.
Promo2: Indicates whether a continuous promotional offer is active (1) or not (0).
Promo2SinceWeek: The week of the year when the continuous promotional offer started.
Promo2SinceYear: The year when the continuous promotional offer started.
PromoInterval: The intervals at which the continuous promotional offer is repeate
# Data understanding
Train data has both independent and dependent variables but Test.csv don't have target variable
I use train and store data for mergeing them for modle building.
# Featuer Extaction from 'Date' column 
# EDA Outcomes
 I have tried many kind of visualization to get  all posibilities like seasonality ,weekly monthly sales trend ,and promotion and holidaya impact on regular sales for sales forcasting and filter them for training and testing 
 # Model building using Macine Learning algorithms to get future six weeks sales .
