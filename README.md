# Subject-wise Student Performance Predictor
A beginner-friendly Machine Learning project that predicts a student's final marks for a selected subject based on academic and attendance-related features.

## Project Overview
This project uses Machine Learning to predict final student marks using:

- Subject
- Study Hours
- Attendance
- Previous Marks
- Assignment Score

The project demonstrates the complete basic Machine Learning workflow from data generation and EDA to model training, evaluation, and prediction.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Workflow
1. Dataset Generation
2. Data Inspection
3. Exploratory Data Analysis (EDA)
4. One-Hot Encoding
5. Train-Test Split
6. Linear Regression
7. Prediction
8. Model Evaluation
9. New Student Prediction
10. Actual vs Predicted Visualization

## Model
Linear Regression is used to predict the final marks.

### Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)

## Dataset
The dataset used in this project is synthetically generated for educational and demonstration purposes.

## Example
Input:

- Subject: DBMS
- Study Hours: 6
- Attendance: 85%
- Previous Marks: 72
- Assignment Score: 80

The trained model predicts the student's final marks based on these features.

## Project Structure
```text
subject-wise-student-performance-predictor/
│
├── Subject-wise Student Performance Predictor.ipynb
├── student_performance_dataset.csv
└── README.md
