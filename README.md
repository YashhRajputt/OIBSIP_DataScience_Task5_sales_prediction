# OIBSIP_DataScience_Task5_sales_prediction.

# Sales Prediction using Linear Regression

## Objective
The aim of this project is to predict the sales of a product based on advertising spending across TV, Radio, and Newspaper channels using Machine Learning.

## Steps Performed

1. Data Collection
  - Loaded the dataset Advertising.csv containing advertising expenses and sales figures.
2. Data Exploration & Preprocessing
  - Checked for null values and data types.
  - Performed exploratory data analysis (EDA) to understand the relationship between advertising channels and sales.
3. Data Visualization
  - Plotted scatter plots to visualize the correlation between each advertising channel and sales.
  - Created heatmaps to show feature correlations.
4. Model Building
  - Split the data into training (80%) and testing (20%) sets.
  - Used Linear Regression to train the model.
5. Model Evaluation
  - Evaluated model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.
6. Prediction
  - Used the trained model to predict sales for given advertising spending inputs.

## Tools Used

- Python (Programming Language)
- Pandas (Data manipulation)
- NumPy (Numerical operations)
- Matplotlib & Seaborn (Data visualization)
- Scikit-learn (Machine Learning algorithms and evaluation)

## Dataset Inf

### First 5 Rows
   Unnamed: 0     TV  Radio  Newspaper  Sales
0           1  230.1   37.8       69.2   22.1
1           2   44.5   39.3       45.1   10.4
2           3   17.2   45.9       69.3    9.3
3           4  151.5   41.3       58.5   18.5
4           5  180.8   10.8       58.4   12.9

### Missing Values
Unnamed: 0    0
TV            0
Radio         0
Newspaper     0
Sales         0
dtype: int64

## Model Training
- **Features:** TV, Radio, Newspaper
- **Target:** Sales
- **Algorithm:** Linear Regression

## Results
- **R² Score:** 0.90
- **RMSE:** 1.78

## Outcome 
The model successfully predicts sales with high accuracy based on advertising spend.
R² Score: ~0.90 (indicating the model explains around 90% of the variance in sales).
The analysis revealed that TV advertising had the strongest influence on sales, followed by Radio, with Newspaper having minimal effect.
