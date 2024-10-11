# ML-Linear-Regression-Home-Price-Prediction-Analysis-Project

This project aims to predict house prices using a dataset that includes features like the number of rooms, type of property, suburb, and more. We will implement linear regression as the primary model, followed by Ridge and Lasso regressions to handle potential overfitting or underfitting.

## Dataset Description

The dataset used in this project contains the following key features:

- **Suburb**: The suburb where the house is located.
- **Rooms**: Number of rooms in the house.
- **Type**: Type of property (e.g., house, unit, townhouse).
- **Price**: The target variable, representing the price of the property in Australian dollars.
- **SellerG**: The name of the real estate agent.
- **Distance**: Distance from the Central Business District (CBD) in kilometers.
- **Regionname**: The general region (e.g., West, North, East).
- **Propertycount**: The number of properties that exist in the suburb.
- **Bathroom**: Number of bathrooms.
- **Car**: Number of car parking spaces.
- **Landsize**: The size of the land in square meters.
- **BuildingArea**: The size of the building in square meters.
- **Method**: How the property was sold (e.g., sold at auction, sold prior to auction, etc.).

For a detailed description of all columns, please refer to the dataset.

## Project Structure

- **Part 1: Data Exploration & Pre-processing**
  - Load and describe the dataset.
  - Handle missing values (filling with 0 or mean where appropriate).
  - Drop irrelevant columns like `Address`, `Date`, `Postcode`, etc.
  - Create dummy variables for categorical features (e.g., `Method`, `Type`).
  
- **Part 2: Model Building**
  - Define target (`Price`) and features.
  - Build a Linear Regression model.
  - Assess model performance using metrics like MSE, MAE, RMSE, and R² score.
  - Apply Ridge and Lasso regressions to improve performance in case of overfitting.

## Steps to Run the Project

**1. Clone the Repository:**
  ```bash
  git clone https://github.com/your-username/ML-Linear-Regression-Home-Price-Prediction-Analysis-Project.git
  cd ML-Linear-Regression-Home-Price-Prediction-Analysis-Project

**2. Dataset:**
 Download the dataset and place it in the appropriate folder, or ensure the dataset is available in the same directory as the code file.

**3. Run the Jupyter Notebook or Python Script:**
Open the Jupyter Notebook (home_price_prediction.ipynb) or run the Python script:
```bash
jupyter notebook ML Home Price Prediction & Analysis Project.ipynb

**4. Model Training & Evaluation:**
The notebook will guide you through loading the data, preprocessing it, and building a linear regression model.The final section will display the model's performance metrics.

## Model Evaluation

The following metrics are used to evaluate the model:

**Mean Squared Error (MSE):** Measures the average squared difference between predicted and actual values.
**Mean Absolute Error (MAE):** Measures the average absolute difference between predicted and actual values.
**Root Mean Squared Error (RMSE):** The square root of MSE, providing error metrics in the same units as the target variable.
**R² Score:** Represents the proportion of variance in the target variable explained by the model.

## Conclusion

This project demonstrates the use of linear regression for house price prediction. By handling missing values, generating dummy variables for categorical data, and using Ridge and Lasso regressions, we aim to create a model that generalizes well on new data.
