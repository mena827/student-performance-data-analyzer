# Student Performance Data Analyzer

## Project Overview

Student Performance Data Analyzer is a beginner-friendly Python project that analyzes fictional student grades and summarizes academic performance.

The project demonstrates data analysis, statistical summaries, data visualization, CSV file handling, and automated validation.

## Objectives

- Calculate each student's average score.
- Calculate average scores for individual subjects.
- Identify the student with the highest average.
- Classify student results using a defined score threshold.
- Visualize subject averages and student averages.
- Export analysis results to CSV files.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Dataset

The project uses a fictional dataset containing 10 students and scores in three subjects:

- Mathematics
- Science
- Programming

All student records are synthetic and do not represent real individuals.

## Methodology

1. Create a structured dataset using Pandas.
2. Calculate the average score for each student.
3. Calculate the average score for each subject.
4. Identify the student with the highest average.
5. Generate bar charts using Matplotlib.
6. Export results to CSV files.
7. Run validation checks on the dataset and analysis.

## Project Files

- `Student_Performance_Data_Analyzer.ipynb` — Python code and analysis notebook.
- `student_results.csv` — Student scores, averages, and classifications.
- `subject_averages.csv` — Average scores by subject.
- `subject_averages.png` — Chart showing average scores by subject.
- `student_averages.png` — Chart showing average scores by student.

## Validation

The notebook includes checks for:

- The number of student records.
- Score values within the range of 0 to 100.
- Calculated averages within the expected range.
- The expected highest-performing student.
- The number of students meeting the defined score threshold.

All included validation tests passed during the recorded run.

## Limitations

This project uses a small, fictional dataset for educational purposes. Its results cannot be generalized to real student populations.

The classification threshold is a simple example and may not match an institution's actual grading policy.

## Learning Outcomes

This project provides practice in Python programming, tabular data processing, descriptive statistics, data visualization, CSV file handling, and basic software testing.
