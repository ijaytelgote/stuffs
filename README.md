# Heart Failure Prediction Data Science Project

![Heart Failure](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/001/731/418/datas/original.jpg)

## Overview

This GitHub repository contains a data science project focused on predicting heart failure using machine learning and data analysis techniques. Heart failure is a critical medical condition that affects millions of people worldwide. Early detection and prediction of heart failure can significantly improve patient outcomes.

In this project, we aim to develop a predictive model that can identify individuals at risk of heart failure based on a set of clinical and demographic features. We leverage data science and machine learning to analyze a dataset of historical patient data, build a predictive model, and evaluate its performance.

## Dataset

The dataset used in this project contains the following features:

- Age: Age of the patient (in years).
- Sex: Gender of the patient (0 for female, 1 for male).
- CP: Chest pain type (0, 1, 2, 3, or 4).
- Trestbps: Resting blood pressure (mm Hg).
- Chol: Serum cholesterol level (mg/dL).
- Fbs: Fasting blood sugar > 120 mg/dL (0 for no, 1 for yes).
- Restecg: Resting electrocardiographic results (0, 1, or 2).
- Thalach: Maximum heart rate achieved.
- Exang: Exercise-induced angina (0 for no, 1 for yes).
- Oldpeak: ST depression induced by exercise relative to rest.
- Slope: Slope of the peak exercise ST segment (0, 1, or 2).
- Ca: Number of major vessels (0-3) colored by fluoroscopy.
- Thal: Thallium stress test result (0, 1, 2, or 3).
- Target: Presence of heart failure (0 for no, 1 for yes).

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for training and evaluation.
- `notebooks/`: Jupyter notebooks with the data analysis, feature engineering, model training, and evaluation steps.
- `src/`: Python source code for data preprocessing, model development, and evaluation.
- `models/`: Saved machine learning models.
- `requirements.txt`: List of Python libraries and dependencies used in the project.

## Getting Started

To run this project locally or reproduce the results, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/ijaytelgote/heart-failure-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd heart-failure-prediction
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebooks in the `notebooks/` directory to see the data analysis, feature engineering, model training, and evaluation steps.

## Results

We achieved promising results in predicting heart failure using machine learning models. The final model demonstrates strong performance with accuracy, precision, recall, and F1-score metrics. Detailed evaluation metrics and visualizations can be found in the Jupyter notebooks.

## Conclusion

This project serves as an example of using data science and machine learning techniques to predict heart failure based on patient data. Predictive models like this one can potentially aid healthcare professionals in early detection and intervention, ultimately improving patient outcomes.

Feel free to explore the code, data, and results in this repository. If you have any questions or suggestions, please don't hesitate to reach out.
