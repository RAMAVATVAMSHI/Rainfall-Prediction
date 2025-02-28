# Rainfall-Prediction
The project involves predicting rainfall based on historical weather data. It uses Random Forest Regression to train a model and make predictions.
# Rainfall Prediction

## Overview
This project focuses on predicting rainfall using machine learning techniques. The dataset consists of various meteorological features, and the model is trained using a Random Forest Regressor to forecast rainfall.

## Dataset
The dataset contains the following attributes:
- **year**: Year of the recorded data.
- **tempavg**: Average temperature.
- **DPavg**: Average dew point.
- **humidity avg**: Average humidity.
- **SLPavg**: Average sea-level pressure.
- **visibilityavg**: Average visibility.
- **windavg**: Average wind speed.
- **Rainfall**: Amount of rainfall (target variable).

## Project Workflow
1. **Data Loading**: Load the dataset using Pandas.
2. **Data Preprocessing**:
   - Drop unnecessary columns (`month` and `day`).
   - Check for missing values and handle them accordingly.
   - Define dependent (`x`) and independent (`y`) variables.
3. **Train-Test Split**: Split the dataset into training and testing sets (80-20 split).
4. **Model Building**:
   - Train a Random Forest Regressor model.
   - Predict rainfall using the test set.
5. **Evaluation**:
   - Calculate the R² score to measure model performance.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## How to Run
1. Clone this repository.
2. Install dependencies using the above command.
3. Run the Jupyter Notebook (`Rainfall Prediction.ipynb`).

## Results
The model achieved an R² score of approximately **0.272**, indicating moderate prediction performance. Further improvements can be made by fine-tuning hyperparameters or using alternative models.

## Future Enhancements
- Feature engineering to improve model accuracy.
- Exploring deep learning techniques.
- Using real-time weather data for more accurate predictions.

## Author
Ramavath Vamshi

