# Predictive Machine Learning Model for Annual Coffee Yield Forecasting
## A case of Western Hararghe Zone

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19630675.svg)](https://doi.org/10.5281/zenodo.19630675)

---

## 📋 Overview

This repository contains the complete code and dataset for the study:
**"Predictive Machine Learning Model for Annual Coffee Yield Forecasting: A case of Western Hararghe Zone"**

**Authors**: Ketema Deresa, Hashim Siraj, Gadissa Nemomsa  
**Institution**: Oda Bultum University, Chiro, Ethiopia  
**Correspondence**: [ketema.deresa@obu.edu.et](mailto:ketema.deresa@obu.edu.et)

---

## 🎯 Research Objectives

1. Develop machine learning models for annual coffee yield prediction
2. Compare six regression algorithms: Ridge, ElasticNet, Gradient Boosting, XGBoost, Random Forest, and SVR
3. Identify key predictors of coffee productivity in Western Hararghe Zone
4. Establish a baseline framework for data-driven agricultural planning

---

## 📊 Key Findings

- **Best Model**: Ridge Regression (R² = 0.8431, RMSE = 519.37, MAE = 377.49)
- **Top Predictors**: Cultivated Area, Soil Texture, Organic Carbon, Soil pH
- **Study Period**: 2007-2023 (Gregorian Calendar)
- **Study Area**: 5 districts in Western Hararghe Zone, Ethiopia

---

## 🗂️ Repository Structure
coffee-yield-forecasting-western-hararghe/
│
├── data/
│ └── coffee_yield_data.csv # Dataset (2007-2023)
│
├── coffee_yield_forecasting.py # Main Python script (all code)
│
├── results/ # Generated automatically when you run the code
│ ├── model_performance.csv
│ ├── feature_importance.png
│ ├── actual_vs_predicted.png
│ └── residual_plot.png
│
├── README.md # This file
├── requirements.txt # Python dependencies
├── .gitignore # Git ignore rules
└── LICENSE # MIT License

text

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Git (for cloning)

### Installation

**Step 1: Clone the repository**
git clone https://github.com/ketemaderesa/coffee-yield-forecasting-western-hararghe.git
cd coffee-yield-forecasting-western-hararghe
Step 2: Create a virtual environment

python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
Step 3: Install dependencies

pip install -r requirements.txt
Run the Code
Execute the single Python file:

python coffee_yield_forecasting.py
The script will:

Load and preprocess the data

Train all six models with hyperparameter tuning

Generate performance metrics

Create visualizations in the results/ folder

📈 Results Summary
Model	CV R²	Test R²	RMSE	MAE
Ridge	0.8228	0.8431	519.37	377.49
ElasticNet	0.8228	0.8417	521.58	378.54
SVR	0.8221	0.8400	524.49	385.94
Gradient Boosting	0.8267	0.8377	528.12	382.47
XGBoost	0.8186	0.8281	543.53	398.27
Random Forest	0.7975	0.7635	637.51	462.95
📝 Data Description
The dataset includes agronomic, soil, and climatic variables from 5 districts in Western Hararghe Zone, Ethiopia.

Feature	Range	Mean
Cultivated Area (ha)	3,220 - 18,929	10,529
Soil pH	5.0 - 6.7	6.04
Total Nitrogen (%)	0.06 - 10.4	0.42
Available Phosphorus (ppm)	7.0 - 405	31.04
Organic Carbon (%)	0.2 - 1.9	0.99
Annual Temp (°C)	32.1 - 36.6	34.03
Precipitation (mm/day)	1.1 - 4.0	2.15
Coffee Yield (ton/ha)	285 - 18,259	2,675.56
🔗 Links
GitHub: https://github.com/ketemaderesa/coffee-yield-forecasting-western-hararghe

Zenodo: https://doi.org/10.5281/zenodo.19630675

📚 Citation
If you use this code or dataset, please cite:
  title={Predictive Machine Learning Model for Annual Coffee Yield Forecasting: A case of Western Hararghe Zone},
  author={Deresa, Ketema and Siraj, Hashim and Nemomsa, Gadissa},
}

🙏 Acknowledgements
Ethiopian Coffee and Tea Authority

Western Hararghe Zone Agriculture Office

Ethiopian National Meteorological Agency (ENMA)

NASA POWER for climate data

❓ Questions?
Contact the corresponding author at ketema.deresa@obu.edu.et
