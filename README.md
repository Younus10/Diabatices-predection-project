# Diabetes Prediction Project

This project focuses on analyzing blood sugar data to predict the likelihood of diabetes using machine learning techniques. Using a dataset of health-related parameters, we build a classification model that identifies individuals as diabetic or non-diabetic.

## Project Overview

The objective of this project is to analyze blood sugar data and predict diabetes based on various health parameters. The dataset contains information on **768 individuals** and **8 parameters**, including:

- Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

Each entry is labeled with an outcome of either `0` (non-diabetic) or `1` (diabetic), indicating the health status.

## Dataset

- **Source**: [Kaggle - Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- **Format**: CSV (Comma-Separated Values)
- **Data Origin**: Originally from the National Institute of Diabetes and Digestive and Kidney Diseases

### Data Cleaning and Preprocessing

The dataset required minimal cleaning as there were no missing values. Some preprocessing steps were performed, including standardizing parameter values to ensure consistency across the dataset.

## Analysis and Model

This project utilizes a **Random Forest Classifier** to predict diabetes. The analysis steps include:

1. Splitting the dataset into training and testing sets.
2. Training the Random Forest model on the training set.
3. Evaluating the model's performance on the test set.
4. Creating visualizations to explore the relationship between parameters and diabetes status.

### Tools and Libraries

- **Programming Language**: Python
- **Libraries**:
  - Data manipulation: Pandas, Numpy
  - Visualization: Matplotlib, Seaborn, Plotly
  - Machine Learning: Scikit-learn
  - App Interface: Streamlit

## Results

The trained Random Forest model provides accurate predictions on the test data, allowing us to identify key factors associated with diabetes. Visualizations created during the analysis highlight significant relationships, such as glucose level and BMI, in relation to diabetes status.

## Conclusion

The project successfully demonstrates the use of machine learning for diabetes prediction. The insights derived can be valuable for identifying at-risk individuals based on simple health metrics.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

