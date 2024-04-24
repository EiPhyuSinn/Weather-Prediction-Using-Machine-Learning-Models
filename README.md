# Weather Prediction Using Machine Learning Models

This project aims to build machine learning models for weather prediction based on historical weather data. The dataset used contains attributes such as precipitation, maximum temperature, minimum temperature, and wind speed, with the goal of predicting categorical weather conditions (e.g., sunny, rainy, drizzle, fog, snow).

## Dataset

The dataset used for weather classification includes the following attributes:

- Precipitation (Inch): Measures rain or snowfall and indicates if it rained or snowed.
- Temp_max (Celsius): The highest temperature of the day.
- Temp_min (Celsius): The lowest temperature of the day.
- Wind (mph): Measures how fast the wind is blowing.

## General Steps to Build the Prediction Model

1. **Data Collection:** Gather historical weather data, including attributes and the target value.
2. **Data Preprocessing:**
   - Handle missing data: Fill in missing values or remove incomplete records.
   - Feature scaling: Normalize or standardize numerical features to ensure they have similar scales.
3. **Data Splitting:** Split the dataset into training and testing sets.
4. **Choose a Machine Learning Algorithm:** Select an appropriate algorithm for weather prediction tasks.
5. **Model Training:** Train the chosen machine learning model on the training data.
6. **Model Evaluation:** Assess the model's performance on the testing data using appropriate evaluation metrics.
7. **Make Predictions:** Use the trained model to make predictions on new, unseen data or forecast future weather conditions.

## Models Included

### 1. Decision Tree Classifier
- A classification algorithm that uses a tree-like structure to make decisions based on data features.

### 2. K-Nearest Neighbors (KNN)
- A simple machine learning algorithm that classifies or predicts based on the majority vote of its nearest data points in feature space.

### 3. Random Forest Classifier
- An ensemble machine learning model that combines multiple decision trees to make robust predictions for classification tasks.

## Folder Structure

- `code/`: Contains Python scripts for data preprocessing, model training, and evaluation.
- `data/`: Contains the dataset used for training and testing.
- `models/`: Contains serialized trained models.

## Usage

To replicate the project or use the provided models:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Explore the `code/` directory for Python scripts to preprocess data, train models, and evaluate performance.
4. Use the trained models in the `models/` directory for making predictions on new data.

## Contributors

- Ei h y u Sinn (2016-MIIT-ECE-051)

## License

This project is licensed under the [MIT License](LICENSE).
