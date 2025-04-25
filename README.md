# CrimeCategoryPrediction

🔍 Crime Category Prediction

🧠 Project Goal

Leverage historical crime data to predict the category of crime associated with each incident. This project explores various features including incident location, time, victim demographics, and other key details to build robust predictive models.

📊 Dataset Overview

This dataset offers a rich landscape for data exploration and model development. Each record represents a reported crime, complete with contextual details that paint a story — from location and timing to suspect behavior and victim information.

My objective is to analyze these patterns and develop models capable of predicting the type of crime committed in each case.

📁 Data Files
train.csv — Contains the training data, including the target variable crime_category and all feature columns.

test.csv — Includes the same features as the training set, but without the crime_category; this is the data you’ll predict on.

sample_submission.csv — A template for formatting your predictions for submission.

🧾 Feature Descriptions

Column Name	Description

Location	Street address where the crime took place.
Cross_Street	Nearest cross street to the crime location.
Latitude / Longitude	Geospatial coordinates of the incident.
Date_Reported	Date the crime was reported.
Date_Occurred	Date when the crime actually occurred.
Time_Occurred	Time of the incident in 24-hour format.
Area_ID	LAPD geographic area code.
Area_Name	Name of the LAPD geographic area.
Reporting_District_no	District number of the reporting unit.
Part 1-2	Classification of the crime (Part I or II).
Modus_Operandi	Actions/behaviors associated with the suspect.
Victim_Age	Age of the victim.
Victim_Sex	Gender of the victim.
Victim_Descent	Ethnic/descent code of the victim.
Premise_Code	Code for the type of location where the crime occurred.
Premise_Description	Description corresponding to the premise code.
Weapon_Used_Code	Code representing the weapon used (if any).
Weapon_Description	Description of the weapon type.
Status	Status code for the case (e.g., open, closed).
Status_Description	Description of the case status.
Crime_Category	Target variable — the category/type of crime to be predicted.
