# Udacity DS Nanodegree Capstone project - Employee Churn Model

### Table of Contents

1. [Motivation](#motivation)
2. [Data and Libraries](#requirements)
3. [Results](#results)
4. [Blog](#blog)

## Motivation <a name="libraries"></a>

- Working in banking, preventing customer churn is an important goal. Flipping this on its head, we're going to investigate churn from the perspective of employees in a hypothetical mid-sized company of 10,000+ employees. This project is completed as part of the Udacity Data Scientist for Enterprise Nanodegree. The datasets come from elitedatascience.com.

There are two objectives of this project:
1. To train a binary classification model that predicts, based on an employee's happiness, performance, workload and experience, whether they will leave the company.<br>
The deliverable will be a trained .pkl file **model_v2.pkl**.
2. Rank the features based on importance of this winning model.

## Requirements, files and data <a name="requirements"></a>

**Project files required for the project:**
1) EmployeeChurnNotebook.ipynb
2) employee_data.csv

**Software required to run these files:**<br>
Download the latest version of Anaconda here: https://www.anaconda.com/products/individual<br>
Anaconda contains Python 3.7 and the data science-centric IDE JupyterLab.<br>
Load EmployeeChurnNotebook.ipynb in JupyterLab and run all cells.<br>
This will create the following files:
- analytical_base_table_v1.csv and analytical_base_table_v2.csv (datasets for modelling).
- model_v1.pkl and model_v2.pkl.

## Results <a name="results"></a>

The final trained machine learning model (saved as model_v2.pkl) has an AUROC score of 99%.<br>
The three most important features are: n_projects (workload), satisfaction (happiness) and tenure (experience).<br> 
The full feature importance list can be found in the .ipynb notebook and in the corresponding blog post below.<br>
Moreover, the notebook and blog post describe a number of interesting insights from the exploratory data analysis on the dataset.

## Blog <a name="blog"></a>
Here's my [blog](https://medium.com/@col_jung/travelling-or-investing-seattles-airbnb-scene-a4d8e613a1ca "blog") post about this project.