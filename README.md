# Maths MP Analysis and Prediction

This Streamlit application analyzes the performance of students in Maths for the academic year 2023-24 and provides predictions for their first-year engineering results based on their academic scores.

## Overview

This Streamlit app performs the following tasks:

- Data loading and preprocessing: Loads the student performance data from a CSV file and preprocesses it by handling categorical data and dropping unnecessary columns.
- Data exploration: Displays the loaded dataset and summary statistics to provide an overview of the data.
- Data visualization: Visualizes the relationship between different academic scores (10th, 12th, and CET marks) and semester 1 performance using bar charts.
- Model training: Trains a Random Forest classifier using the preprocessed data to predict student results.
- Model evaluation: Evaluates the trained model's performance using accuracy, confusion matrix, and classification report metrics.
- Feature importance analysis: Displays the feature importance plot to show the importance of different input features in predicting student results.
- Prediction: Allows users to input their academic scores and predicts their first-year engineering result using the trained model.

## Installation

To run this Streamlit app locally, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/sojith29034/maths_mp_23-24.git
   ```

2. Navigate to the project directory:

   ```
   cd maths_mp_23-24
   ```

3. Install the required dependencies using pip:

   ```
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:

   ```
   streamlit run maths_mp.py
   ```

5. Access the Streamlit app in your web browser at `http://localhost:8501`.

## Usage

- Upon running the Streamlit app, you'll see the different sections for data exploration, visualization, model training, and prediction.
- Use the sliders or input fields to input your academic scores for 10th, 12th, and CET marks.
- Click the "Predict" button to see the predicted result for your first-year engineering.

## Dependencies

The Streamlit app relies on the following Python libraries:

- `streamlit`: For building and running the web application.
- `matplotlib`: For data visualization and plotting.
- `pandas`: For data manipulation and analysis.
- `scikit-learn`: For machine learning model training and evaluation.

These dependencies are listed in the `requirements.txt` file for easy installation.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
