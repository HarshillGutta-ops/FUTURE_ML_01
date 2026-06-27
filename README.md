# Sales and Demand Forecasting - Future Interns Task 1

A machine learning project to forecast future sales using historical Superstore business data.

## Objective
Build a sales forecasting model that predicts future demand and presents results in a clear, business-friendly way that can be used by store owners, startup founders, and business managers.

## Dataset
- Sample Superstore Sales Dataset
- Source: Kaggle (Superstore Dataset)
- Records: 9,994 transactions
- Date Range: 2014 to 2017
- Features: Order Date, Category, Sub-Category, Region, Sales, Quantity, Discount, Profit

## Techniques Used
- Time-based feature engineering (Year, Month, Quarter, Seasonality)
- Label encoding for categorical features
- Models trained and compared:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor

## Results

| Model | MAE | RMSE | R2 Score |
|---|---|---|---|
| Linear Regression | - | - | - |
| Random Forest | - | - | - |
| Gradient Boosting | - | - | - |

## Visualizations
- Graph 1: Monthly sales trend (2014 to 2017)
- Graph 2: Sales by category and region
- Graph 3: Seasonality analysis (monthly and quarterly)
- Graph 4: Model performance comparison
- Graph 5: Actual vs predicted sales and residuals
- Graph 6: 6-month future sales forecast with annotations
- Graph 7: Feature importance
- Graph 8: Top sub-categories and sales vs profit

## Business Insights
- Q4 (October to December) consistently shows the highest sales
- Technology category drives the highest revenue
- West region leads in total sales
- High discount rates are reducing profit margins

## How to Run

Install dependencies:
```bash
pip install scikit-learn pandas numpy matplotlib seaborn
```

Open `sales_demand_forecasting.ipynb` in VS Code with the Jupyter extension and run all cells in order.

Note: Update the file path in Cell 1 to point to your local dataset location.

## Tools and Libraries
- Python 3.13
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn