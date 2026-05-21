# Drug Overdose Death Detection Using Machine Learning

**Domain:** Public Health Analytics  
**Stack:** Python · scikit-learn · pandas · Flask · Random Forest · Gradient Boosting  
**Deployment:** Flask web application with real-time prediction interface

---

## What This Project Does

Builds a machine learning pipeline to predict drug overdose death risk 
based on patient and demographic features. Trained and compared multiple 
classification models. Deployed as an interactive web app using Flask.

---

## Results

| Model | Accuracy | F1 Score |
|---|---|---|
| Gradient Boosting | Highest | Highest |
| Random Forest | High | High |
| Logistic Regression | Baseline | Baseline |

![Final Result](reports/Final_Result.png)

---

## Project Structure
---

## How to Run

```bash
pip install -r requirements.txt

# Run the notebook
jupyter notebook Notebook.ipynb

# Run the web app
python app.py
```

---

## Skills Demonstrated

Feature Engineering · Model Comparison · Hyperparameter Tuning · 
Flask Deployment · Classification · Imbalanced Data Handling
