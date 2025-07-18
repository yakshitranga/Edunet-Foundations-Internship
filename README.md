# Edunet Foundations Internship
Forecasting electric vehicle (EV) adoption isn't just about numbers, it's about preparing our cities for a sustainable future. This project builds a regression model to help urban planners and policymakers estimate future EV demands and proactively plan infrastructure, especially charging stations.

🚗 Problem Statement
Electric vehicles are growing fast. But without solid forecasting, we risk underbuilding or misplacing infrastructure like charging points. Using historical EV registration data, the goal is to predict future EV adoption at the county level.

🎯 Project Goal
Train a regression model that can:
Predict future EV adoption trends 
Leverage patterns from past vehicle registrations
Help identify regions with increasing EV usage

📊 Dataset Overview
Sourced from the Washington State Department of Licensing, this dataset includes:
Timeframe: January 2017 to February 2024
Granularity: Monthly, by county

Features:
Date: Snapshot of registrations
County, State: Region info
Vehicle Primary Use: Passenger or Truck
BEVs: Battery-only electric vehicles
PHEVs: Plug-in hybrids
EV Total: Sum of BEVs and PHEVs
Non-Electric Vehicle Total
Total Vehicles
Percent Electric Vehicles

⚙️ Tools & Libraries Used
pandas, numpy for data handling
seaborn, matplotlib for EDA
scikit-learn for model building and evaluation
joblib for saving the trained model

📌 Project Highlights
Cleaned missing values and corrected data types
Capped outliers in target features using IQR bounds
Built a Random Forest Regressor to predict EV percentage growth
Performed feature encoding, hyperparameter tuning, and model evaluation

📈 Results
The trained model effectively captures temporal and regional patterns in EV adoption, and can be extended to build interactive dashboards or guide infrastructure planning.
