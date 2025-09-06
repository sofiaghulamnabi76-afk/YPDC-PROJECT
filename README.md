# YPDC-PROJECT
YPDC project repository. Completed as part of the YPDC program, this project demonstrates my ability . The repository includes the project's codebase, documentation, and implementation details
# Student Mental Health Analysis

This project analyzes a dataset related to students' mental health. The dataset contains information about students' demographics, academic background, and mental health conditions such as depression, anxiety, and panic attacks. The goal of this project is to explore trends, patterns, and correlations in student mental health.

## Dataset Columns

The dataset contains the following columns:

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

## Technologies Used

- Python
- Pandas
- Matplotlib
- Numpy
- Seaborn
- Jupyter Notebook (optional)

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


```

