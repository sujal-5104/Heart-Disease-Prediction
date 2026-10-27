# Heart Disease Prediction Using Machine Learning

## Overview
This project uses machine learning classification algorithms to predict the presence of heart disease from patient health-related features. It demonstrates data exploration, preprocessing, model comparison, and performance evaluation in Python.

## Objectives
- Explore and understand the dataset.
- Preprocess numerical and categorical features.
- Train and compare classification models.
- Evaluate model performance using classification metrics and ROC-AUC.
- Save the selected model for future predictions.

## Dataset
The project uses:
- `values.csv` — Patient feature data.
- `labels.csv` — Target labels (`heart_disease_present`).

## Algorithms
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Results
The current notebook reports the following results on its test split:

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Gradient Boosting | 91.7% | 84.2% | 100% | 91.4% | 95.6% |
| Logistic Regression | 80.6% | 76.5% | 81.2% | 78.8% | 94.1% |
| Random Forest | 88.9% | 80.0% | 100% | 88.9% | 94.1% |

These values are from the current notebook outputs and may change when the notebook is rerun. They are preliminary results on a small dataset, not evidence of clinical diagnostic accuracy.

## Technologies
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Project Files
- `Heart_Disease_Prediction.ipynb` — Data analysis, preprocessing, training, and evaluation.
- `values.csv` — Patient features.
- `labels.csv` — Target labels.
- `heart_model.pkl` — Saved model.
- `requirements.txt` — Python dependencies.

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/sujal-5104/Heart-Disease-Prediction.git
   ```

2. Enter the project directory:

   ```bash
   cd Heart-Disease-Prediction
   ```

3. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Heart_Disease_Prediction.ipynb` and run the cells in order.

## Limitations
The dataset is small, so performance estimates may be unstable. Further validation on larger, independent datasets is needed.

