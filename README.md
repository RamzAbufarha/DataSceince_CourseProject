# Flight Delay Prediction Project

##  Project Overview
This project investigates the impact of weather and operational factors on flight delays using machine learning. The study analyzes flight operations from five major European cities between 2023 and 2025 to predict whether a flight will be delayed by more than 15 minutes.

##  Objectives
- Analyze flight delay patterns across different European cities.
- Explore the impact of weather conditions on flight delays.
- Perform data cleaning and preprocessing.
- Engineer operational, weather, and temporal features.
- Compare multiple machine learning classification models.
- Optimize the best-performing model.
- Evaluate model performance using metrics suitable for imbalanced datasets.

## Team Information
**Team Name:** Dark Mode

- Yaqeen Azamta - 1221736
- Ramz Abufraha - 1230963
- Anas Hamdan Al-Haj - 1230038

## Dataset 
The analytical dataset was created by combining three public sources:

- Flight Delays Europe 2023–2025
- OurAirports Database
- Open-Meteo Historical Weather API

After preprocessing and integration, the final analytical dataset contains:

- **2,081,394 flight records**
- **65 original features**
- **52 encoded modeling features**
- **30 selected features** after feature selection

The project focuses on flights departing from:

- London (United Kingdom)
- Amsterdam (Netherlands)
- Paris (France)
- Frankfurt (Germany)
- Barcelona (Spain)

## Machine Learning Pipeline
- Data Collection
- Data Cleaning
- Feature Engineering
- Feature Selection
- Train/Test Split
- Model Training
- Hyperparameter Tuning
- Threshold Optimization
- Model Evaluation

## Models Compared
- Baseline (Majority Class)
- Logistic Regression
- Gaussian Naive Bayes
- K-Nearest Neighbors
- Decision Tree
- Random Forest

## Best Model

**Random Forest**

Performance on the delayed class:
Metric    :Scor
Precision :0.29 
Recall    :0.34 
F1 Score  :0.31 

The model was further improved using:

- Hyperparameter tuning
- Decision threshold optimization

SMOTE was also evaluated but did not improve performance.

## Repository Contents
```
Flight_Delay_FINAL_Submission.ipynb   # Complete notebook
DataScienceReport.pdf                 # Final project report
figures/                              # Figures used in the report
README.md
```


## 🛠️ Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Google Colab

## Results

- Random Forest achieved the highest performance among all evaluated models.
- Operational features contributed more to prediction performance than weather features.
- Flight delays remain difficult to predict accurately using only publicly available data.
- The study highlights the importance of operational history over weather conditions.

## Future Work

Potential improvements include:

- Using real airline operational data.
- Incorporating air traffic control information.
- Adding arrival-airport and en-route weather.
- Exploring deep learning and time-series approaches.


## 🚀 Status
- Phase 1: Completed  
- Phase 2: Completed
- Phase 3: Completed
- Phase 4: Completed
