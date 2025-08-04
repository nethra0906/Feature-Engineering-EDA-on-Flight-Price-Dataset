**Flight Price Prediction — Feature Engineering**
**Overview**
- A project exploring and preparing the Kaggle Flight Price Prediction dataset for modeling flight ticket prices using feature engineering.

**Dataset Description**
- Contains flight details from six major Indian cities: Airline, Source City, Departure Date & Time, Arrival Date & Time, Route, Duration, Total Stops, Class (Economy / Business), and Price (target variable) 

**Feature Engineering (FE)**
- Data Cleaning:
  Address missing values via imputation or removal, clean inconsistent formats, remove duplicates
  Convert Duration from string (e.g. "2h 50m") to numeric (total minutes or hours) 

- Encoding:
  One-hot or label encode categorical variables: Airline, Source, Destination, Class, Time Bins, Stops


