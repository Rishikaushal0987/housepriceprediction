# House Price Prediction

## Overview
This project implements a simple **House Price Prediction** model using **Linear Regression**. It uses **Python** and key data science libraries such as `pandas`, `numpy`, `matplotlib`, and `scikit-learn`. The model predicts house prices based on features like **area (sq ft), number of bedrooms, and house age**.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Dataset
The dataset is **randomly generated** for demonstration purposes. In a real-world scenario, you should replace it with actual housing market data.

## Installation
To run this project, ensure you have Python installed along with the required dependencies:
```sh
pip install pandas numpy matplotlib scikit-learn
```

## How It Works
1. Generates a dataset with random house features and prices.
2. Splits the data into **training (80%)** and **testing (20%)** sets.
3. Trains a **Linear Regression Model** on the training data.
4. Makes predictions on the test data.
5. Evaluates the model using **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **Root Mean Squared Error (RMSE)**.
6. Visualizes actual vs. predicted prices using a scatter plot.

## Usage
Run the script:
```sh
python house_price_prediction.py
```

## Model Evaluation
The model’s performance is evaluated using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

## Output Visualization
The script generates a scatter plot comparing actual vs. predicted house prices.

## Future Improvements
- Use a **real-world dataset** instead of random data.
- Try different regression models such as **Decision Tree Regressor** or **Random Forest Regressor**.
- Include more features like location, number of bathrooms, etc.

## License
This project is open-source and available under the MIT License.

---
🚀 **Happy Coding!**
