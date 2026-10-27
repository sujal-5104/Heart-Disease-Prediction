# Heart Disease Prediction Using Machine Learning

## Project Overview
This project uses machine learning classification algorithms to predict the presence of heart disease based on patient health-related features. It demonstrates data exploration, preprocessing, model training, comparison, and evaluation using Python.

## Objectives
- Explore and understand the dataset.
- Clean and preprocess numerical and categorical features.
- Train and compare multiple classification algorithms.
- Evaluate performance using classification metrics and ROC-AUC.
- Save the selected trained model for future predictions.

## Dataset
The project uses:
- `values.csv` — Patient feature data.
- `labels.csv` — Target labels (`heart_disease_present`).

## Machine Learning Algorithms
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

## Model Evaluation Results
The current notebook reports the following results on its test split:

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Gradient Boosting | 91.7% | 84.2% | 100% | 91.4% | 95.6% |
| Logistic Regression | 80.6% | 76.5% | 81.2% | 78.8% | 94.1% |
| Random Forest | 88.9% | 80.0% | 100% | 88.9% | 94.1% |

These results reflect the current notebook outputs and may change when the notebook is rerun. They are preliminary estimates from a small dataset and do not establish clinical diagnostic accuracy.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Pickle for model serialization

## Project Files
- `Heart_Disease_Prediction.ipynb` — Data analysis, preprocessing, model training, and evaluation.
- `values.csv` — Patient feature data.
- `labels.csv` — Target labels.
- `heart_model.pkl` — Saved trained model.
- `requirements.txt` — Python dependencies.
- `.gitignore` — Files excluded from Git tracking.

## Installation and Usage

### 1. Clone the repository
```bash
git clone https://github.com/sujal-5104/Heart-Disease-Prediction.git
```

### 2. Enter the project directory
```bash
cd Heart-Disease-Prediction
```

### 3. Install dependencies
```bash
python -m pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 5. Run the project
Open `Heart_Disease_Prediction.ipynb` and run the cells in order.

## Limitations
The dataset is small, so performance estimates may be unstable. Validation on larger, independent datasets is needed before drawing broader conclusions.

