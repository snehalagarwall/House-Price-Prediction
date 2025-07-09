"# House-Price-Prediction" 

house-price-prediction/
├── data/
│ ├── hoursing.csv # Original dataset
│ └── processed_data.csv # Cleaned/processed data
├── working/
│ └── 01_eda.ipynb # EDA notebook 
| └── 02_linear.ipynb #model training notebook
├── output/
│ └── metrics.txt #saves the model rmse
└── README.md

## Installation
git clone https://github.com/snehalagarwall/house-price-prediction.git
cd house-price-prediction

Key Features
Feature Engineering: Handling categorical and numerical data
Exploratory Data Analysis: Comprehensive data visualization
Linear Regression: Baseline model implementation
Model Evaluation: RMSE metric for performance validation

Workflow
Data Preprocessing:
Handled categorical data (Label Encoding)
Scaled numerical features (StandardScaler)

Model Training:
Implemented Linear Regression
Saved performance metrics (RMSE) to output/metrics.txt

Results:
Model performance is tracked in output/metrics.txt with Root Mean Square Error (RMSE).


