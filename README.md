# House Price Prediction Using Linear Regression

## Project Overview
This project predicts house prices using the Linear Regression machine learning algorithm. The model uses house-related features such as area, number of bedrooms, and age to predict the house price.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Information
The dataset contains 100 records and 4 columns.

**Input Features:**
- `area` – Area of the house
- `bedrooms` – Number of bedrooms
- `age` – Age of the house

**Target Variable:**
- `price` – House price

## Project Workflow
1. Importing Required Libraries
2. Loading the Dataset
3. Feature and Target Selection
4. Splitting Data into Training and Testing Sets
5. Model Training using Linear Regression
6. Predicting House Prices
7. Model Evaluation
8. Data Visualization

## Model Details
- **Algorithm:** Linear Regression
- **Training Data:** 80%
- **Testing Data:** 20%
- **Random State:** 42

## Model Performance
The model performance is evaluated using the R² Score.

**R² Score: 93.12%**

## Visualization

### Actual vs Predicted House Prices

This scatter plot compares the actual house prices with the predicted house prices. The red dashed line represents the ideal prediction line.

![Actual vs Predicted House Prices](images/actual_vs_predicted.png)

## How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Place the `House_price.csv` dataset in the project folder.
4. Open the Jupyter Notebook.
5. Run all cells to train the model and predict house prices.

## Author
A. ABDUL AZIZ
