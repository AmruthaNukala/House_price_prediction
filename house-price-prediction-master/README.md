# House Price Prediction

This project aims to predict house prices using two machine learning algorithms: Linear Regression and Gradient Boosting Regressor. The dataset includes various features related to houses, such as the number of bedrooms, bathrooms, square footage, and sale prices.

## Dataset

The dataset utilized for this project includes the following columns:
- **Bedrooms**: Number of bedrooms in the house.
- **Bathrooms**: Number of bathrooms in the house.
- **Square footage**: Total square footage of the house.
- **Garage spaces**: Number of garage spaces.
- **Year built**: Year the house was built.
- **Sale price**: The price at which the house was sold.

## Dependencies

To execute the code, ensure the following Python libraries are installed:
- NumPy
- pandas
- scikit-learn

## Usage

1. **Clone the repository to your local machine:**
    ```bash
    git clone https://github.com/AmruthaNukala/house-price-prediction.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd house-price-prediction
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook or Python script for model training and evaluation:**
    ```bash
    jupyter notebook House_Price_Prediction.ipynb
    ```
    or
    ```bash
    python house_price_prediction.py
    ```

## Project Structure

```
house-price-prediction/
│
├── data/
│   └── house_prices.csv        # Dataset file
│
├── notebooks/
│   └── House_Price_Prediction.ipynb  # Jupyter Notebook for model training and evaluation
│
├── scripts/
│   └── house_price_prediction.py  # Python script for model training and evaluation
│
├── requirements.txt  # List of dependencies
│
├── LICENSE  # License file
│
└── README.md  # Project readme file
```

## Results

This project evaluates and compares the performance of Linear Regression and Gradient Boosting Regressor models in predicting house prices. The models are assessed using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Conclusion

The evaluation metrics are used to determine which model offers better performance in predicting house prices. Additionally, the project provides insights into the significance of different features in the prediction process.

## Future Work

Potential future improvements include:
- Experimenting with other machine learning algorithms
- Hyperparameter tuning for better performance
- Adding more features to enhance prediction accuracy

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for more details.

---

Contributions are welcome! If you would like to contribute, please fork the repository and submit a pull request. For major changes, it's recommended to open an issue first to discuss the changes. If you find this project useful, consider giving it a star!