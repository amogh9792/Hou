# Bangalore House Price Prediction Model

## Introduction
This project focuses on predicting house prices in Bangalore, India, using machine learning techniques. The model is designed to help individuals estimate house prices based on certain features like location, total square feet area, number of bathrooms, and number of bedrooms.

## Features Used
- **total_sqft**: Total square feet area of the property
- **bath**: Number of bathrooms
- **bhk**: Number of bedrooms
- **location**: Location of the property

## Technologies Used
- Python
- Libraries: Pandas, NumPy, Matplotlib, Scikit-learn

## Data Preprocessing
- Removed unnecessary columns like area_type, society, and balcony.
- Handled missing values in the dataset.
- Cleaned the 'total_sqft' column to handle ranges and non-numeric values.

## Exploratory Data Analysis (EDA)
- Explored various features like location, size, total_sqft, bath, and price.
- Analyzed the distribution of house prices based on different parameters.
- Identified outliers and handled them appropriately.

## Model Building
- Utilized linear regression to build the predictive model.
- Evaluated the model using cross-validation and grid search techniques.
- Implemented Lasso regression and Decision Tree regression as alternatives.

## Model Evaluation
- Achieved an accuracy of approximately 84.52% on the test dataset.
- Conducted cross-validation to ensure robustness and reliability of the model.

## Deployment
- Developed a function to predict house prices based on user input.
- Saved the trained model using pickle for future use.
- Created a JSON file containing information about data columns for reference.

## Conclusion
The developed model serves as a valuable tool for estimating house prices in Bangalore. Users can input specific details about the property, and the model will provide an estimated price based on the learned patterns from the dataset. This project demonstrates the application of machine learning techniques in real estate valuation and can be further extended to include additional features and improve accuracy.