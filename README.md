# Student Data Analysis using Python

## Project overview
This portfolio project demonstrates a complete exploratory data analysis (EDA) workflow on student performance data using Python, Pandas, NumPy, Matplotlib, and Seaborn.

**Dataset note:** `data/student_performance_sample.csv` is a synthetic practice dataset created for this portfolio project. It is not real student data and should not be represented as data from an actual institution.

## Objectives
- Inspect data structure and data types
- Identify and handle missing values
- Detect implausible values and potential outliers
- Summarize performance by department
- Explore relationships among attendance, study time, assignments, and exam scores
- Create clear visualizations and record findings

## Tools
- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository structure
```text
Student_Data_Analysis_Python/
├── data/
│   └── student_performance_sample.csv
├── notebooks/
│   └── student_data_analysis.ipynb
├── outputs/
│   └── (generated charts are saved here when the notebook is run)
├── src/
│   └── analysis.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Run locally
1. Install Python 3.10 or newer.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `notebooks/student_data_analysis.ipynb` and run all cells from top to bottom.

## Key questions explored
- Which departments have the highest average exam score?
- Is attendance associated with exam performance?
- How do study hours relate to exam scores?
- Are there missing or implausible values that need treatment?

## Important
This is a learning/portfolio project built with synthetic data. Review the notebook, run the analysis, and update the findings based on your own execution before presenting it as completed work.
