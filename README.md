# sensor-time-series-regression
Time series regression experiment for household appliance energy consumption prediction using environmental sensor data. Implemented Lasso, Ridge, and Random Forest, with time-series cross-validation.

## Dataset
Appliances Energy Prediction (UCI Machine Learning Repository, ID:374).
- URL: https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction
- Task: Regression task to predict household appliances energy consumption.
- Raw dataset is not included in this repository.
- Data directory structure: `data/raw/` for original downloaded data, and `data/processed/` for processed outputs. All data files are excluded from git.
- To reproduce: Download the dataset from the UCI URL above and place `appliances+energy+prediction.zip` under `data/raw/`.
- Preprocessing: None at this stage. Only data loading is implemented.
