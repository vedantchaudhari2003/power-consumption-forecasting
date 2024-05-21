# Power Consumption Forecasting

## Project Overview
This project aims to predict electricity consumption using historical weather data by developing a Random Forest model, focusing on improving forecast accuracy.

## Motivation
To leverage machine learning techniques for accurate power consumption forecasting, helping in efficient energy management and planning.

## Key Features
- **Data Collection and Processing**: Gathered and cleaned extensive temperature and power consumption datasets.
- **Feature Engineering**: Created features like lagged temperature and rolling averages to enhance model performance.
- **Model Development**: Built and optimized a Random Forest model to predict power consumption.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/power-consumption-forecasting.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare your dataset and place it in the `data` folder.
2. Run the training script:
    ```bash
    python train_model.py
    ```
3. Evaluate the model:
    ```bash
    python evaluate_model.py
    ```

## Results
The Random Forest model achieved a Root Mean Squared Error (RMSE) of [insert RMSE value], demonstrating strong predictive performance.

## Contributing
Contributions are welcome. Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.
