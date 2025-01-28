# Housing Price Prediction using TensorFlow Decision Forests 🏡🌱

This project demonstrates the application of **TensorFlow Decision Forests (TF-DF)** to predict housing prices using a regression model. By leveraging decision forests, we achieve robust and interpretable results for tabular data.

---

## Features ✨

- **Regression with TF-DF**: Predict housing prices with high accuracy.
- **Data Visualization**: Analyze the dataset with visualizations.
- **Customizable Parameters**: Fine-tune the model for your use case.
- **End-to-End Pipeline**: From data preprocessing to prediction and evaluation.

---

## Requirements 📂

Make sure you have the following installed:

- Python 3.8+
- TensorFlow 2.18.0
- TensorFlow Decision Forests
- NumPy, pandas, matplotlib, seaborn

Install dependencies using:
```bash
pip uninstall tensorflow tensorflow_decision_forests -y
pip install tensorflow==2.18.0
pip install tensorflow_decision_forests
pip install numpy pandas matplotlib seaborn
```

---

## Getting Started 🚀

Follow these steps to set up and run the project:

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/housing-price-prediction.git
cd housing-price-prediction
```

### 2. Prepare the Dataset
Ensure the `housing.csv` file is in the root directory. The dataset should contain relevant features and the target column `price_lakh`.

### 3. Run the Code
Execute the script to preprocess the data, train the model, and make predictions:
```bash
python housing_price_prediction.py
```

---

## How It Works 🕵️‍♂️

1. **Data Loading and Visualization**:
    - The `housing.csv` dataset is loaded and basic statistics and visualizations are generated.

2. **Data Splitting**:
    - The dataset is split into training and validation sets for evaluation.

3. **Model Training**:
    - A Random Forest model is trained using TensorFlow Decision Forests.

4. **Evaluation**:
    - The model is evaluated using metrics like RMSE (Root Mean Squared Error).

5. **Variable Importance**:
    - Feature importances are calculated and visualized to understand key drivers of predictions.

6. **Prediction**:
    - Predictions are made on the test dataset and saved to a CSV file.

---

## Demo 🎥

Run the script to see data visualizations, model training progress, and predictions in action!

---

## Further Queries ✉️

If you have any questions or need support, feel free to reach out:
**Email**: aryan070sharma@gmail.com

---

## Contributing 📚

Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

---

## License 🔒

This project is licensed under the [MIT License](LICENSE).

---

Happy Coding! ✨
