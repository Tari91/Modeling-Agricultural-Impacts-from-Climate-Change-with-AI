**Synthetic Climate and Agricultural Impact Dataset & Modeling**
This repository contains synthetic data and Python code for modeling the impacts of climate variables on agricultural crop yield using AI techniques.

**Contents**
synthetic_climate_crop_data.xlsx:
An Excel file containing synthetic data with the following columns:

Temperature (°C)

Rainfall (mm/year)

CO2 (ppm)

Humidity (%)

CropYield (arbitrary units, simulated)

modeling_code.py (or notebook):
Python code that:

Generates synthetic data

Trains a Random Forest regression model to predict crop yield based on climate variables

Evaluates model performance

Visualizes feature importance and prediction accuracy

**Purpose**
This synthetic dataset and model demonstrate how AI can be used to analyze and predict agricultural outcomes under varying climate conditions. It serves as a starting point for exploring climate change impacts on agriculture.

**Requirements**
Python 3.x

Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn

Optionally, Jupyter Notebook to run the code interactively

Install dependencies via:

bash


pip install numpy pandas scikit-learn matplotlib seaborn
Usage
Load the synthetic data from synthetic_climate_crop_data.xlsx or generate it programmatically using the provided code.

Train machine learning models on the dataset to predict crop yields.

Analyze feature importance to understand climate variables’ effects.

Extend the model with real-world data or other climate factors for more detailed studies.

**Notes**
The data is synthetic and meant for educational and prototyping purposes only.

Crop yield is generated via a simplified nonlinear function with noise.

Model results will vary based on hyperparameters and data size.

Author
Tarinabo williamtarinabo@gmail.com
