# BMW-Price-Prediction-ANN
BMW car price prediction using ANN and Linear Regression with a Gradio deployment interface

# BMW Car Price Prediction 🚗
Comparing Linear Regression and Artificial Neural Networks (ANN).

## 📌 Project Overview
This project aims to predict the market price of BMW cars based on several features like engine size, horsepower, mileage, and car age. The main goal was to compare a traditional machine learning model with a deep learning approach.

## 🛠️ Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, TensorFlow/Keras.
- **Deployment:** Gradio.

## 📊 Performance Comparison
| Model | R² Score |
| :--- | :--- |
| **Linear Regression** | 94% |
| **Neural Network (ANN)** | 98.1% |

## 🚀 Key Features
- **Data Preprocessing:** Handled missing values using mean and mode imputation.
- **Feature Engineering:** Calculated "Car Age" to provide better insights than "Year".
- **Deep Learning:** Built a 3-layer ANN with ReLU activation for high-accuracy regression.
- **Interactive UI:** A Gradio interface to predict prices in real-time.

## 📁 How to use
1. Upload the dataset `bmw_cars_market_dataset_synthetic.csv`.
2. https://www.kaggle.com/datasets/tahaberkterekli/bmw-cars-market-dataset
3. Run the notebook to train the model.
4. Use the Gradio link to test with custom car specs.
