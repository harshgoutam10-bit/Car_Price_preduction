# 🚗 Car Price Prediction

### Car Price Prediction using Linear Regression

This project uses Machine Learning to predict the selling price of used cars based on important vehicle features such as present price, manufacturing year, driven kilometers, fuel type, seller type, transmission, and owner information.

## 📌 Project Objective

The main objective of this project is to build a Machine Learning regression model that can estimate the selling price of a used car from its available features.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset

The project uses a used-car dataset containing information such as:

- Present Price
- Selling Price
- Manufacturing Year
- Driven Kilometers
- Fuel Type
- Seller Type
- Transmission
- Owner

## 🤖 Machine Learning Model

The project uses:

*Linear Regression*

The dataset is divided into training and testing data. The model is trained using the training data and then evaluated on unseen test data.

## 📈 Model Evaluation

The model achieved the following results:

- *R² Score:* 0.8488
- *Accuracy/Explained Variance:* approximately 84.88%
- *MAE:* 1.216
- *MSE:* 3.481
- *RMSE:* 1.866

An R² score of approximately *0.849* means that the model explains about *84.9% of the variation* in car selling prices.

## 📉 Actual vs Predicted Prices

The project also includes a graph comparing actual car selling prices with the prices predicted by the Linear Regression model.

The predictions are reasonably close to the actual values for most observations.

## 📂 Project Files

```text
Car_Price_Prediction/
│
├── Car_Price_Prediction.ipynb
├── car data.csv
└── README.md
## 📊 Actual vs Predicted Car Prices

![Actual vs Predicted Car Prices]
(actual_vs_predicted.png)
