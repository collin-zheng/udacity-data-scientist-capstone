# Udacity DS Nanodegree Capstone project - Employee Churn Model

### Table of Contents

1. [Motivation](#motivation)
2. [Data and Libraries](#requirements)
3. [Results](#results)
4. [Blog](#blog)

## Motivation <a name="libraries"></a>

- Working in banking, preventing customer churn is an important goal. Flipping this on its head, we're going to investigate churn from the perspective of employees in a hypothetical mid-sized company of 10,000+ employees. This project is completed as part of the Udacity Data Scientist for Enterprise Nanodegree. The datasets come from elitedatascience.com.

There are two objectives of this project:
1. To train a binary classification model that predicts, based on an employee's happiness, performance, workload and experience, whether they will leave the company. The deliverable will be a trained .pkl file.
2. Rank the features based on importance of this winning model.

## Data & Libraries <a name="requirements"></a>

The model is created in a Jupyter notebook EmployeeChurnNotebook.ipynb. An easy way to run it yourself is to install the latest version of Anaconda, which contains Jupyter Lab and Python 3.7. Important libraries imported in the notebook (included in the Anaconda distribution) are: NumPy, Pandas, Matplotlib, Seaborn and Sklearn.

A single dataset is required for running the analysis and is in this repository:
employee_data.csv (from elitedatascience.com)

## Results <a name="results"></a>

The final trained machine learning model is model_v2.pkl, which has an AUROC score of 99%.
The three most important features are: n_projects (workload), satisfaction (happiness) and tenure (experience). The full list can be found in the .ipynb notebook and in the corresponding blog post below. Moreover, the notebook and blog post describe a number of interesting insights from the exploratory data analysis on the dataset.

## Blog <a name="blog"></a>
Here's my [blog](https://medium.com/@col_jung/travelling-or-investing-seattles-airbnb-scene-a4d8e613a1ca "blog") post about this project.