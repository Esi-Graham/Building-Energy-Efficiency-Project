### Introduction
Buildings use 40% of the world's energy, making them crucial for energy efficiency improvements. Addressing heating and cooling needs throughout a building's lifecycle, including operation and design stages, can lead to energy savings, lower operational costs, and reduced environmental impact.

### Problem Statement and Objectives
The goal of this project is to create a predictive model that can accurately forecast the heating and cooling load requirements for building energy efficiency.With a growing emphasis on sustainable and energy-efficient building designs, it is vital to understand and estimate heating and cooling energy requirements.This work intends to forecast these loads using multiple machine learning models and building energy performance data, which can help to optimize energy usage, reduce expenses, and minimize environmental effect.The purpose of this study is to use several models and building energy performance data to anticipate how much heating and cooling will be required for building efficiency.

### Jupyter Notebook Outline
1. Importation of packages
2. Data Importation
3. Data Cleaning and Validation
4. Exploratory Data Analysis
5. Data Preprocessing
6. Model Building
7. Model Comparison

### Data Description
The dataset includes the following variables about building design and energy use:
Relative Compactness: Determines how compact the building shape is.
Surface Area (m²): The whole outside area of the building.
Wall Area (m²) refers to the total area of the building's walls.
Roof Area (m²): The size of the building's roof.
Overall Height (m): The height of the building.
Orientation: The direction the building faces (2: north, 3: east, 4: south, 5: west).
Glazing Area (% of floor area): The proportion of the floor area covered by windows (0%, 10%, 25%, 40%).
Glazing Area Distribution: How windows are distributed (1: uniform, 2: north, 3: east, 4: south, and 5: west).
Heating Load (kWh): The energy required to heat the building.
Cooling Load (kWh): The energy required to cool the building.
The features allow us to understand how building design influences the amount of energy required for heating and cooling.

### Model Selection
eXtreme Gradient Boosting Regressor(XGBoostRegressor) is the best-performing model, followed by the Support Vector Regressor model, when taking into account the R2 scores of the various models.

### Conclusion
Our goal in this project was to use Building Energy Efficiency dataset to create a prediction model for Cooling Load and Heating Load.Data cleaning and validation as well as Exploratory Data Analysis was performed on the data set to ensure effective model building.The data set was split into one train and two test sets for predictive model building.The XGBoostRegressor, with an R2 score of 0.9877 and 0.9985 for Cooling Load and Heating Load respectively, was found to be the best-performing regression model after a variety of models, including Support Vector Regressor, Random Forest and Random Forest Regressor.The Support Vector Regressor was ranked as the second-best model. Other metrics such as the Root Mean Squared error and Mean Squared error were also employed to measure model errors.

