Resume Analyser

Project Overview

The Resume Analyser is a Python-based machine learning project that identifies resumes containing specific skills, such as Python. The project uses natural language processing to extract features from resume text and applies Linear Regression and Logistic Regression models to predict skill presence accurately.

Features

1.Extracts key skills from resumes using TF-IDF vectorization.
2.Predicts skill presence with Linear Regression and Logistic Regression.
3.Evaluates models using accuracy metrics.
4.Generates charts for performance comparison within the notebooks.
5.Binary classification: resumes with the target skill (1) or without (0).

Project Structure

Plain text
resume_analyser/
│
├── resumes.csv                 # Dataset of resumes
├── linear_model.ipynb          # Notebook for Linear Regression analysis
└── logistic_model.ipynb        # Notebook for Logistic Regression analysis

Technologies Used

Python 3.x
pandas, numpy
scikit-learn (Linear Regression, Logistic Regression)
matplotlib, seaborn
Jupyter Notebook

Model Accuracy

Model
Accuracy
Linear Regression
0.79
Logistic Regression
0.82
Charts in each notebook visualize model performance and compare results.

Getting Started

1.Clone the repository:

git clone https://github.com/harinikumarijeyaraj/resume_analyser

2.Open the notebooks:

jupyter notebook linear_model.ipynb
jupyter notebook logistic_model.ipynb

3.Run all cells in each notebook to reproduce the analysis, models, and charts.

Usage

1.Update resumes.csv with your resume data.
2.Run each notebook to train and evaluate the corresponding model.
3.Visualizations in the notebooks show model accuracy and comparisons.

Conclusion

This project demonstrates applying machine learning to automate resume screening. Comparison between Linear Regression and Logistic Regression shows logistic regression performs slightly better for binary skill prediction. The project can be extended to multi-skill detection, larger datasets, and advanced NLP techniques for improved accuracy.
