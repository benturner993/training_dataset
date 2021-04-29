![training_dataset](misc/lcc.png)

# Objective
The objective of this code repository is to create a learning resource which can be used for analysis without commerical licencing constraints / restrictions.

# Purpose
The purpose of the challenge is to create a predictive model using any tool of choice (e.g. Excel, Emblem, SAS VIYA, R and Python) in order to predict whether a claim is a large collision (large_collision) where each row in the dataset indicates a claim. 

For illustrative purposes, a large collision can be defined as a claim which has a value of greater than £150,000. 

Within this repository are four csv datasets: 

* train - a dataset to be used to train the model
* test - a dataset to be used to validate the model
* results - a dataset provided to the participants without the response column which which can be used to score results

The validation metric of this challenge is F1.

# Data Dictionary

The following columns are included:

* pol_ref - the policy reference of the customer
* name - the name of the policy holder
* address - the address of the policy holder
* gender - the gender of the policy holder
* car_make - the brand of car
* car_value_as_new - the value of the car when purchased new
* car_year - the year the car was purchased
* pol_holder_age - the age of the policy holder
* pol_employment_type - the employment contract of the policy holder
* pol_employment_industry - the employment industry of the policy holder
* pol_holder_licence_length - the number of years which the policy holder has held a licence
* car_top_speed - the top speed of the car
* postcode_rating - an integer 0-50 which rates the postcode of the policy holder (50 worst) 
* credit_rating - an integer 0-50 which rates the credit rating of the policy holder (50 worst)
* other_named_driver - an indicator which states if there are any other named drivers on the policy
* criminal_convictions - the number of criminal convisions which the policy holder has
* car_modified_indicator - an indicator stating whether the car has been modified
* car_colour - the colour of the vehicle
* collision_date - the date of the collision
* collision_description - a description of the conditions
* large_collision - an indicator which has the value 1 for claims which have a value of greater than £150,000 

# Author
This project was created by Ben Turner in 2021Q2. Please feel free to provide any feedback.