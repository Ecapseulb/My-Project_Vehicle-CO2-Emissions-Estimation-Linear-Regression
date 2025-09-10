# Vehicle CO2 Emissions Estimation

## Introduction

This notebook documents how we train a Linear Regression model from a given dataset to predict the CO2 emissions of vehicles . It includes EDA, model training and evaluation.

## About Dataset

**Description:**

This dataset contains information on vehicle specifications, fuel consumption, and CO2 emissions, collected to analyze the environmental impact of vehicles and predict their CO2 emissions using regression models. The dataset is structured to support both Simple Linear Regression (SLR) and Multiple Linear Regression (MLR) approaches for machine learning projects.

**Key Features**
- <font color =orange>Brand</font>: The brand or manufacturer of the vehicle (e.g., Toyota, Ford, BMW).
- <font color =orange>Vehicle Type</font>: Classification of vehicles based on size and usage (e.g., SUV, Sedan).
- <font color =orange>Engine Size (L)</font>: Engine displacement volume in liters.
- <font color =orange>Cylinders</font>: Number of cylinders in the engine.
- <font color =orange>Transmission</font>: Type of transmission (e.g., Automatic, Manual).
- <font color =orange>Fuel Type</font>: Type of fuel used by the vehicle (e.g., Gasoline, Diesel, Hybrid).
- <font color =orange>Fuel Consumption (City, Hwy, and Combined)</font>: Fuel efficiency measured in liters per 100 kilometers (L/100 km).
- <font color =orange>CO2 Emissions (g/km)</font>: Carbon dioxide emissions per kilometer (target variable for prediction).

**Use Cases**
- Exploratory Data Analysis (EDA):
  
  Clean and analyze the dataset to understand trends in CO2 emissions based on engine size, fuel type, and vehicle class.

- Simple Linear Regression (SLR):

  Use Engine Size (L) to predict CO2 Emissions (g/km).

- Multiple Linear Regression (MLR):

  Incorporate additional features like Fuel Consumption and Cylinders to create more accurate prediction models.

**Objective**
This dataset is designed to:

 - Help understand the relationship between vehicle specifications and their environmental impact.
 - Enable the application of regression models for predicting CO2 emissions.
 - Explore the impact of fuel efficiency and engine size on carbon emissions.

**Why This Dataset?**

Environmental concerns are a critical issue, and analyzing CO2 emissions is essential to mitigate climate change. It offers a practical application for machine learning students and professionals to develop predictive models. Provides an opportunity to practice EDA, data cleaning, and regression modeling techniques.

**Dataset Highlights**
- Suitable for both beginners and advanced practitioners in data science.
- Provides a hands-on opportunity to work on real-world data.
- Perfect for showcasing machine learning skills in regression analysis.

**Provider:** Batuhan Şahan

Reference: https://www.kaggle.com/datasets/brsahan/vehicle-co2-emissions-dataset/data


## About this notebook

For this notebook, we refer the source code shared by Pavan Kumar S on Kaggle as a reference.
(https://www.kaggle.com/code/pavankumar4757/co2-emissions-prediction-r-0-99-rmse-5-48/notebook)
