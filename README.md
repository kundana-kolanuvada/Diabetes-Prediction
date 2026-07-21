# Diabetes Prediction using Machine Learning

A Machine Learning project that predicts whether a person is diabetic based on various health parameters using classification algorithms.

## Project Overview

Diabetes is a chronic disease that affects millions of people worldwide. Early prediction helps in timely diagnosis and treatment. This project applies Machine Learning techniques to predict diabetes using patient health records from the PIMA Indians Diabetes Dataset.

The project includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Statistical analysis
- Data standardization
- Train-Test Split
- Model training
- Model evaluation
- Diabetes prediction on new input data

---

## Tech Stack

| Category | Technology Used |
|---|---|
| Programming Language | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) |
| Data Analysis | ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)|
| Machine Learning | ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white) |
| Notebook Environment | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) |
| Development Environment | ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visual-studio-code&logoColor=white) |

---

## Dataset

**Dataset Used:** PIMA Indians Diabetes Dataset
https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
The dataset contains the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target Variable**

- **0** → Non-Diabetic
- **1** → Diabetic

---

## Project Workflow

- Data Collection
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Standardization
- Train-Test Split
- Model Training
- Model Evaluation
- Prediction

---

## Setup

### Clone the Repository

```bash
git clone https://github.com/kundana-kolanuvada/Diabetes-Prediction.git

cd Diabetes-Prediction
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `notebook.ipynb` and run all the cells.

---

## Results

The trained Machine Learning model predicts whether a patient is diabetic based on the provided health parameters. Model performance is evaluated using standard classification metrics.

---

## Future Improvements

- Compare multiple classification algorithms
- Hyperparameter tuning
- Feature engineering
- Deploy using Streamlit or Flask
- Build an interactive web application


## License

This project is intended for educational and learning purposes.
