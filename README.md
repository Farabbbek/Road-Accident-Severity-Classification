# Road-Accident-Severity-Classification
ML_Project-Road Accident Severity Classification

## 📌 Project Overview
This project focuses on predicting the severity of road accidents based on various conditions such as weather, lighting, road surface, and type of collision.
Using real-world crash data from New York State, the model classifies each accident as either minor (property damage) or severe (injury/fatal).

## 🎯 Objective
To build a machine learning model that helps classify the severity of an accident and assists in:

faster response planning,

better understanding of accident patterns,

and improved public safety measures.

## 🗂️ Dataset
Source: Open Data NYC - Motor Vehicle Crashes (Three-Year Window)

Size: Over 1.9 million records

Features used:

Day of Week

Hour of Day

Lighting Conditions

Weather Conditions

Collision Type Descriptor

Road Surface Conditions

Event Descriptor

Number of Vehicles Involved

## 🧹 Data Preparation
Missing values filled or removed

Time features extracted: Hour, Day of Week, Time of Day

One-hot encoding for categorical features

Numerical features normalized

Target variable Severity_Binary created:

0 → Property Damage Accident

1 → Any other (Injury, Fatal, etc.)

## 📊 Exploratory Data Analysis (EDA)
EDA included:

Accident distributions by time, lighting, weather, surface

Crash severity by condition

Top municipalities and collision types

Visual conclusions for each distribution

## 🤖 Modeling

Random Forest 

## 🔮 Predictions

Model was tested

Random accident predictions were printed to verify correctness

## ✅ Conclusions

Random Forest delivered the best balance between precision and recall

The model showed strong results even on imbalanced real-world data

EDA helped identify key patterns influencing accident severity

## 🚀 Future Improvements

Upgrade to multiclass classification (0, 1, 2, 3 levels of severity)

Add more contextual features (vehicle type, driver info)

Try advanced models (XGBoost, ensemble stacking)

Build interactive dashboards or real-time prediction apps

## 👤 Author

Author : Tusup Al-Farabi,Asset,Amir

Student project — Machine Learning Applications

