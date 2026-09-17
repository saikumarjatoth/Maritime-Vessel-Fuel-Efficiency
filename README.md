A machine-learning project that predicts vessel fuel consumption and quantifies how operating conditions affect fuel efficiency.

Objectives

Analyze vessel operating and environmental variables.

Predict fuel consumption.

Identify the most influential operational factors.

Simulate fuel usage under alternative speed/operating scenarios.

Translate model predictions into efficiency recommendations.

Dataset

Use a public vessel-operation / ship-fuel-consumption dataset or a cleaned operational dataset with at least:

speed_knots

engine_power_kw

draft_m

cargo_tons

distance_nm

wind_speed_mps

wave_height_m

fuel_consumption_tpd

Place it at:

vessel_fuel_data.csv

Methodology

Data validation and cleaning

Exploratory analysis

Feature engineering

Random Forest regression

MAE / RMSE / R² evaluation

Feature-importance analysis

Speed-scenario simulation

Fuel-saving opportunity analysis

Outputs

fuel_predictions.csv

efficiency_scenarios.csv

maritime_fuel_analysis.xlsx

Prediction and scenario charts

Business Applications

Fuel budgeting

Voyage planning

Speed optimization

Emissions-reduction analysis

Operational benchmarking

Skills

Python, Pandas, NumPy, Scikit-learn, regression, feature engineering, maritime analytics, scenario modeling.

Run

pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
jupyter notebook 02_maritime_vessel_fuel_efficiency.ipynb

Author

J. Sai Kumar
B.Tech — Naval Architecture & Ocean Engineering, IIT Madras
