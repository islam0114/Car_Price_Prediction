# Car Price Prediction

## 1. Project Overview
This project aims to build a machine learning model to predict the price of cars based on their specifications.
By analyzing features such as manufacturer, model year, engine volume, mileage, fuel type, and more, the model provides an estimated car price that can help buyers and sellers make informed decisions.

----

## 2. Dataset Description
Source: Kaggle

The dataset contains detailed information about cars with the following columns:

- ID: Unique identifier for each car

- Price: Target variable (car price in currency)

- Levy: Additional car levy/tax

- Manufacturer: Car brand (e.g., Toyota, BMW, Mercedes)

- Model: Specific car model

- Prod. year: Production year of the car

- Category: Car category (e.g., Sedan, SUV)

- Leather interior: Whether the car has leather interior (Yes/No)

- Fuel type: Petrol, Diesel, Hybrid, Electric, etc.

- Engine volume: Size of the engine

- Mileage: Distance the car has traveled (km)

- Cylinders: Number of cylinders in the engine

- Gear box type: Automatic, Manual, Tiptronic, etc.

- Drive wheels: Type of drivetrain (FWD, RWD, AWD)

- Doors: Number of doors

- Wheel: Steering position (Left/Right)

- Color: Exterior color of the car

- Airbags: Number of airbags available

- has_Turbo: Indicates whether the engine has a turbocharger (Yes/No)


----

## 3. Project Workflow

1- Data Preprocessing

- Handling missing values

- Encoding categorical variables (e.g., Fuel type, Manufacturer)

- Feature scaling/normalization

- Outlier detection and removal

2- Exploratory Data Analysis (EDA)

- Distribution of prices

- Correlation between features and price

- Visualizations (e.g., price vs. year, price vs. mileage)

3- Modeling

- Train/test split

- Regression models (Linear Regression, Random Forest, Gradient Boosting, XGBoost)

- Hyperparameter tuning

4- Evaluation

Metrics: RMSE, MAE, R²

Model comparison

----

## 4. Tools & Technologies

| Category         | Tools                         |
| ---------------- | ----------------------------- |
| Language         | Python                        |
| Data Processing  | pandas, NumPy                 |
| Machine Learning | scikit-learn, XGBoost         |
| Visualization    | Matplotlib, Seaborn, Power BI |

----

## 5. Project Structure
Car_Price_Prediction/

│

├── Code/                          # Final scripts and source code

│

├── Data/                      # Processed datasets

│

├── README.md                      # Project documentation and overview
