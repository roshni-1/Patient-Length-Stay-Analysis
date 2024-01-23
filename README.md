# Patient Length Stay Analysis Project

## Overview
This project aims to predict the duration of hospital stays for patients based on various features such as hospital details, patient information, and admission-related data.

## Dataset
- The dataset includes two main files: `train.csv` (for training) and `test.csv` (for testing).
- The training dataset contains information about hospital stays along with the target variable 'Stay'.
- The test dataset lacks the 'Stay' column, and predictions for this column are made using the trained model.

## Project Steps

1. **Loading the Data:**
   - Loading the training and test datasets (`train.csv` and `test.csv`).

2. **Exploratory Data Analysis (EDA):**
   - Checking for missing values, exploring data distributions, and analysing feature correlations.
      - Handling missing values.
   - Peforming data cleaning and preprocessing.

3. **Data Preprocessing:**
   - Encoding categorical variables.
   - Performing feature engineering.

4. **Model Training:**
   - Spliting the training dataset into features and the target variable.
   - Training a Random Forest model on a subset for quick testing.
   - Evaluating the model on a validation set.

5. **Hyperparameter Tuning:**
   - Performing hyperparameter tuning using GridSearchCV to find the best parameters for the Random Forest model.

6. **Model Evaluation:**
   - Evaluating the tuned Random Forest model on the validation set.
   - Generating predictions for the test dataset.

7. **Save Predictions:**
   - Saving the predicted 'Stay' values for the test dataset to a CSV file (`predicted_stay.csv`).

## Files and Structure
- `train.csv`: Training dataset.
- `test.csv`: Test dataset.
- `predicted_stay.csv`: CSV file containing predicted 'Stay' values for the test dataset.

## Visualizations
![Image 1](https://github.com/roshni-1/Patient-Length-Stay-Analysis/blob/main/plsa1.png)

![Image 2](https://github.com/roshni-1/Patient-Length-Stay-Analysis/blob/main/plsa2.png)

![Image 3](https://github.com/roshni-1/Patient-Length-Stay-Analysis/blob/main/plsa3.png)

![Image 4](https://github.com/roshni-1/Patient-Length-Stay-Analysis/blob/main/plsa4.png)

## Requirements
- Python 3.x
- Libraries: pandas, scikit-learn

## How to Run
1. Install the required libraries: `pip install pandas scikit-learn`.
2. Execute the code in the Jupyter Notebook or your preferred Python environment.

## Author
Roshni Yadav

