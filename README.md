
# YPDC Project: Student Mental Health Analysis & Prediction

**Author:** Sofia Ghulam Nabi  
**Email:** sofiaghulamnabi76@gmail.com  
**Program:** YPDC (BS Data Science)  

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset Description](#dataset-description)  
3. [Objectives](#objectives)  
4. [What’s New / Added Features](#whats-new--added-features)  
5. [Libraries & Tools](#libraries--tools)  
6. [Model Training](#model-training)  
7. [Exploratory Data Analysis (EDA) & Visualization](#exploratory-data-analysis-eda--visualization)  
8. [How to Run](#how-to-run)  
9. [Results & Insights](#results--insights)  
10. [Future Work](#future-work)  
11. [License](#license)  

---

## Project Overview

This project performs a comprehensive analysis of **student mental health data** collected via a survey.

- Analyzes depression, anxiety, and panic attacks  
- Explores demographic patterns (gender, age, marital status, academic year, CGPA)  
- Builds a predictive model to foresee the likelihood of mental health issues, enabling early intervention  

---

## Dataset Description

The dataset contains the following fields:

| Field | Description |
|---|---|
| Gender | Student gender |
| Age | Student age |
| Course | Course/program name |
| Current Year of Study | 1st, 2nd, … etc |
| CGPA | Cumulative Grade Point Average |
| Marital Status | Married / Unmarried / Other |
| Depression / Anxiety / Panic Attacks | Yes / No responses |
| Treatment Seeking Behavior | Whether the student visited a specialist for treatment |

---

## Objectives

- Data cleaning & preprocessing  
- Visualization of key trends  
- Build a predictive model for mental health issues  
- Identify risk factors & high-risk groups  

---

---

## Libraries & Tools

- **Pandas** – Data manipulation and cleaning  
- **NumPy** – Numerical operations  
- **Matplotlib** – Custom visualizations (bar charts, histograms, pie charts, etc.)  
- **Seaborn** – Enhanced statistical plotting  
- **Scikit‑learn** – Model training and evaluation  
- **Jupyter Notebook** – Interactive analysis environment  

---

## Model Training

**Steps followed:**

1. **Preprocessing:**  
   - Filled missing values  
   - Encoded categorical variables  
   - Created new features (like `age_category`)  

2. **Feature Selection:**  
   - Correlation analysis to remove redundant features  

3. **Modeling:**  
   - Train-test split (80/20)  
   - Tried multiple ML models: Logistic Regression, Decision Tree, Random Forest  
   - Evaluated using cross-validation  

4. **Evaluation Metrics:**  
   - Accuracy, Precision, Recall, F1‑Score  
   - Confusion Matrix  
   - ROC Curve & AUC where applicable  

---

## Exploratory Data Analysis (EDA) & Visualization

EDA included:

- Gender-wise mental health condition barplots  
- Age distribution histograms with KDE curves  
- Marital status pie charts  
- Correlation heatmaps for numerical features  
- CGPA vs Mental Health condition plots  

Matplotlib & Seaborn have been used with improved formatting and better aesthetics for presentations.

---

## How to Run

1. Clone the repository:  

```bash
git clone https://github.com/sofiaghulamnabi76-afk/YPDC-PROJECT.git
```

2. Navigate into the project directory:  

```bash
cd YPDC-PROJECT
```

3. Install dependencies:  

```bash
pip install -r requirements.txt
```

4. Run Jupyter Notebook:  

```bash
jupyter notebook analysis.ipynb
```

---

## Results & Insights

- Depression and anxiety are relatively common among students  
- Significant differences observed between gender and age groups  
- CGPA and Year of Study have a moderate effect  
- Model performance achieved: **(Add your final accuracy/F1 score here)**  

---

## Future Work

- Collect more data for better generalization  
- Add more features like socioeconomic background, lifestyle, academic stress levels  
- Deploy model as a web dashboard or API  
- Perform hyperparameter tuning and try ensemble methods for better accuracy  

---

## License

This project is licensed under the **MIT License**.

---
