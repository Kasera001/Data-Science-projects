# Data Science Projects

This repository contains my data science, machine learning, and AI projects, with a focus on practical analysis, model building, and clear business insights.

The current project, [Employee_Dataset_Analysis_and_ML_model.ipynb](Employee_Dataset_Analysis_and_ML_model.ipynb), explores an employee dataset and combines exploratory data analysis with a simple machine learning workflow.

## Project Overview

This notebook covers the full analysis pipeline for an employee dataset, including:

- Data loading and overview
- Data cleaning and preparation
- Exploratory data analysis with `pandas`, `matplotlib`, and `seaborn`
- Feature engineering and transformation
- Visualization of salary, bonus, gender, team, and tenure patterns
- A classification model to predict senior management status
- Insights and actionable recommendations based on the findings

## What This Dataset Analysis Covers

The notebook is centered on understanding employee compensation and workforce patterns. Key areas of interest include:

- Salary distribution and outliers
- Bonus percentage patterns
- Gender representation and compensation fairness
- Team-level salary differences
- Year of service and its relationship with salary
- Predicting whether an employee belongs to the senior management class

## Machine Learning Workflows Included

The project demonstrates a basic but complete ML workflow:

- Preparing the dataset for modeling
- Encoding categorical features
- Scaling or normalizing numeric features
- Training a Random Forest classifier
- Comparing the model with a majority-class baseline
- Interpreting feature importance and class performance

The model in the notebook is exploratory, not production-ready. It is mainly used to show how employee data can be turned into a supervised learning problem and evaluated responsibly.

## Key Findings

From the analysis, the notebook highlights:

- Salary varies widely across employees and contains at least one strong high-salary outlier
- Team-level salary differences are visible and worth reviewing further
- Bonus percentage is only weakly related to salary and tenure
- Year of service has a weak positive relationship with salary
- The Random Forest model performs about the same as the baseline, which suggests the available features are limited for predicting senior status

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository Structure

- [Employee_Dataset_Analysis_and_ML_model.ipynb](Employee_Dataset_Analysis_and_ML_model.ipynb): Main notebook for analysis and modeling
- [README.md](README.md): Project overview and setup instructions

## Getting Started

1. Clone the repository.
2. Open the notebook in Jupyter, VS Code, or Google Colab.
3. Install the required Python libraries if they are not already available.
4. Update the dataset path in the notebook if needed.

Example installation:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Note on Data Path

The notebook currently loads data from a path used in a Colab-style environment. If you are running it locally, update the CSV file path to match your system before executing the cells.

## Future Work

As I add more ML and AI projects to this repository, I will keep expanding it with:

- More exploratory data analysis projects
- Supervised and unsupervised machine learning notebooks
- Model evaluation and comparison experiments
- AI-related prototypes and applied workflows


