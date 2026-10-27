# Heart Disease Prediction Using Machine Learning

## Project Overview
This project uses machine learning techniques to predict the presence of heart disease based on patient health features. It includes data analysis, preprocessing, model training, and evaluation to identify a suitable predictive model.

## Objectives
- Analyze and understand the heart disease dataset.
- Perform data cleaning and preprocessing.
- Train and compare multiple machine learning algorithms.
- Evaluate model performance using classification metrics.
- Save the trained model for future predictions.

## Dataset
The project uses `values.csv` for patient features and `labels.csv` for the target variable, `heart_disease_present`.

## Machine Learning Algorithms
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib / Pickle

## Project Files
- `Heart_Disease_Prediction.ipynb` — Data analysis, preprocessing, model training, and evaluation.
- `values.csv` — Patient feature data.
- `labels.csv` — Heart disease target labels.
- `heart_model.pkl` — Saved trained model.
- `.gitignore` — Files excluded from Git tracking.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sujal-5104/Heart-Disease-Prediction.git
   ```
2. Navigate to the project folder.
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open `Heart_Disease_Prediction.ipynb` and run the cells in order.

## Model Evaluation
The notebook evaluates the trained models using classification metrics and ROC-AUC analysis. The best-performing model is selected based on the evaluation results.

## Disclaimer
This project is intended for educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.

