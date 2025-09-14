# YPDC-PROJECT
YPDC project repository. Completed as part of the YPDC program, this project demonstrates my ability . The repository includes the project's codebase, documentation, and implementation detail





📊 Student Mental Health Analysis

This project analyzes a *Student Mental Health Dataset* using Pandas, Matplotlib, and Seaborn, Numpy  
It includes *data cleaning, **visualization, and **insights* to understand mental health trends among students.

---

## 📂 Dataset Description

The dataset contains information about students’:
- *Gender*
- *Age*
- *Course*
- *Current Year of Study*
- *CGPA*
- *Marital Status*
- *Depression, Anxiety, Panic Attacks*
- *Treatment seeking behavior*

---

## 🎯 Project Objectives

- Clean and prepare the dataset for analysis  
- Visualize key insights:
  - Gender Distribution
  - Age Distribution
  - Depression, Anxiety, Panic Attack Count
  - Marital Status Pie Chart
  - Correlation Heatmap (Numerical Relationships)
- Learn and apply **.iloc[]** and **.loc[]** for data selection

---

## 🛠 Libraries Used

| Library | Purpose |
|--------|---------|
| *Pandas* | Data loading, cleaning, manipulation |
| *Matplotlib* | Basic visualizations (bar charts, histograms, pie charts) |
| *Seaborn* | Advanced, beautiful visualizations (countplots, heatmaps) |
| *Jupyter Notebook* | Interactive environment for step-by-step execution |

Column Name Cleaning:
Removed extra spaces, converted names to lowercase, replaced spaces with _.

Missing Values Handling:
Filled missing values using mode (most frequent value).

Dataset Check:
Verified using df.info() and df.isnull().sum() before and after cleaning.

📊 Exploratory Data Analysis (EDA)
1️⃣ Gender Distribution
Bar chart showing number of male vs female students.

2️⃣ Age Distribution
Histogram + KDE curve to check age spread of students.

3️⃣ Mental Health Insights
Countplots for:

Depression

Anxiety

Panic Attacks

4️⃣ Marital Status
Pie chart showing percentage of married vs unmarried students.

5️⃣ Correlation Heatmap
Visual representation of relationships between numerical features.

🔍 Using .iloc[] and .loc[]
.iloc[] (Index-Based Selection)
Select data using row/column index numbers.

# Select first 5 rows & first 3 columns
df.iloc[0:5, 0:3]
.loc[] (Label-Based Selection)
Select data using row/column names or conditions.

# Select only Female students with their Age
df.loc[df['choose_your_gender'] == 'Female', ['choose_your_gender', 'age']]

# Create a new column using loc
df.loc[:, 'age_category'] = df['age'].apply(lambda x: 'Teen' if x < 20 else 'Adult')
▶ How to Run
Clone the Project / Download Files

git clone <your-repo-link>
Install Required Libraries

pip install pandas matplotlib seaborn jupyter
Run Jupyter Notebook

jupyter notebook
Open student_mental_health_project.ipynb
Run cells one by one to see results and visualizations.

✅ Output Highlights
Clean dataset saved as cleaned_student_mental_health.csv

Interactive visualizations for key insights

New column age_category created using .loc[]
## Dataset columns
- `Timestamp` – Time when the survey was submitted
- `Choose your gender` – Gender of the student
- `Age` – Age of the student
- `What is your course?` – The course or program the student is enrolled in
- `Your current year of Study` – Year of study (e.g., 1st, 2nd, 3rd year)
- `What is your CGPA?` – Current CGPA of the student
- `Marital status` – Marital status of the student
- `Do you have Depression?` – Indicates if the student suffers from depression
- `Do you have Anxiety?` – Indicates if the student suffers from anxiety
- `Do you have Panic attack?` – Indicates if the student experiences panic attacks
- `Did you seek any specialist for a treatment?` – Whether the student sought professional help
## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/sofiaghulamnabi76-afk/YPDC-PROJECT.git
````

2. Navigate to the project folder:

   ```bash
   cd student-mental-health
   ```
3. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Load the dataset in Python using Pandas.
2. Perform data cleaning and preprocessing as needed.
3. Conduct analysis and visualizations to understand trends in mental health.

Example:

```python
import pandas as pd

# Load dataset
df = pd.read_csv("student_mental_health.csv")

# Basic exploration
print(df.head())
print(df.describe())
```

## Features

* Analyze mental health trends among students
* Explore relationships between demographics, academic performance, and mental health
* Identify patterns in seeking professional help

## License

This project is licensed under the MIT License.

## 📌 Conclusion
This project shows:

Majority of students are young and unmarried.

A noticeable number report depression and anxiety.

Provides insights that can help in mental health policy planning for students.

## 📜 Author
Sofia Ghulam Nabi
3rd Semester, BS.DATA SCIENCE
📧 sofiaghulamnabi76@gmail.com
