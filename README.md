# Sales Prediction

## Project Description
This project predicts product sales using Machine Learning based on advertising expenditure across TV, Radio, and Newspaper. It analyzes the relationship between advertising budgets and sales to build an accurate prediction model.

## Dataset
The project uses a Sales Prediction dataset containing:
- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget
- Sales

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithm
- Linear Regression

## Project Workflow
1. Load the dataset.
2. Clean and preprocess the data.
3. Perform Exploratory Data Analysis (EDA).
4. Split the dataset into training and testing sets.
5. Train the Linear Regression model.
6. Predict sales.
7. Evaluate model performance using R² Score, MAE, and MSE.
8. Visualize the results.

## Features
- Data Preprocessing
- Exploratory Data Analysis
- Sales Prediction
- Data Visualization
- Model Evaluation

## Files
- sales_prediction.py
- advertising.csv
- README.md

## How to Run

1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Place `advertising.csv` in the project folder.

3. Run the program:
   ```bash
   python sales_prediction.py
   ```

## Output
The project displays:
- Dataset Preview
- Correlation Heatmap
- Sales Prediction Graph
- Actual vs Predicted Sales
- Model Accuracy Metrics

Example:

```
 Unnamed: 0     TV  Radio  Newspaper  Sales
0           1  230.1   37.8       69.2   22.1
1           2   44.5   39.3       45.1   10.4
2           3   17.2   45.9       69.3    9.3
3           4  151.5   41.3       58.5   18.5
4           5  180.8   10.8       58.4   12.9
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 200 entries, 0 to 199
Data columns (total 5 columns):
 #   Column      Non-Null Count  Dtype  
---  ------      --------------  -----  
 0   Unnamed: 0  200 non-null    int64  
 1   TV          200 non-null    float64
 2   Radio       200 non-null    float64
 3   Newspaper   200 non-null    float64
 4   Sales       200 non-null    float64
dtypes: float64(4), int64(1)
memory usage: 7.9 KB
None
Unnamed: 0    0
TV            0
Radio         0
Newspaper     0
Sales         0
dtype: int64
```
<img width="1231" height="1231" alt="sales" src="https://github.com/user-attachments/assets/a88db7ce-f7b3-4bf6-80d1-6689c5fcf24f" />
<img width="700" height="470" alt="sales1" src="https://github.com/user-attachments/assets/e5120489-c530-4955-80bc-4c5802c4ff56" />

## Author
**Nithish Reddy Alampally**
