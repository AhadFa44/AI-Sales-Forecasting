# AI-Powered Sales Forecasting
**SuperStore Dataset | R²: 96.5% | MAE: $10.92**

## Project Goals
- AI model predicts future sales
- Analyzes key drivers (Category, Region)
- Power BI dashboard (Actual vs Predicted)

## Results

| Metric   | Value                     |
| -------- | ------------------------- |
| Dataset  | 5,901 orders              |
| Model    | RandomForest + GridSearch |
| R² Score | 96.5%                     |
| MAE      | $10.92                    |


## Files
- `superstore_clean.csv`: Cleaned data
- `sales_predictions.csv`: **Actual vs Predicted** (Power BI ready)
- `AI_Sales_Forecasting.ipynb`: Full ML pipeline

## Links
- [Colab Notebook](https://colab.research.google.com/drive/...)
- [Power BI Dashboard](coming soon)
- [Dataset](https://www.kaggle.com/datasets/mohammadkaiftahir/superstore-sales-dataset)

## Run Locally
```bash
pip install pandas scikit-learn prophet
jupyter notebook AI_Sales_Forecasting.ipynb
