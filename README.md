# Student Dropout Rates Prediction

## Project Overview

This project aims to predict student dropout rates using three different machine learning models: Logistic Regression, K-Nearest Neighbors (KNN), and K-Means Clustering. The dataset used in this project includes various features related to students' academic performance and other relevant factors.

## Dataset

**Dataset Link**: https://www.kaggle.com/datasets/missionjee/students-dropout-and-academic-success-dataset

The target variable (`Target`) indicates whether a student has "Dropped out" (0) or "Graduated" (1).

## Project Structure

- `student_dropout_prediction.ipynb`: The main notebook containing the code for EDA, data preprocessing, model training, evaluation, and predictions.
- `README.md`: Documentation of the project.
- `requirements.txt`: List of Python packages required to run the project.

## Steps Involved

1. **Exploratory Data Analysis (EDA):**
   - Analyzed the dataset for missing values and distribution of the target variable.
   - Visualized the distribution of the target variable.

2. **Data Preprocessing:**
   - Handled missing values and encoded the target variable.
   - Scaled the features using `StandardScaler`.

3. **Model Training and Evaluation:**
   - **Logistic Regression:**
     - Trained and evaluated using accuracy and classification report.
   - **K-Nearest Neighbors (KNN):**
     - Trained and evaluated using accuracy and classification report.
   - **K-Means Clustering:**
     - Applied clustering and evaluated using silhouette score.

## Results

- **Logistic Regression:**
  - Achieved an accuracy of `X.XX%` on the test set.
  
- **K-Nearest Neighbors (KNN):**
  - Achieved an accuracy of `X.XX%` on the test set.
  
- **K-Means Clustering:**
  - Achieved a silhouette score of `X.XX`.

## Requirements

- Python 3.7 or later
- Packages: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

To install the required packages, run:
```
$ pip install -r requirements.txt

```

## How to Run

- Clone the repository.

- Install the required packages.

- Run the notebook **'student_dropout_prediction.ipynb'** to see the results.
