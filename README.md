Forecasting Student Dropouts and Academic Success

Steps to Run the Notebook Locally

Ensure Python is Installed
Make sure you have Python 3.8 or higher installed.
You can check by running:

python --version


Open a Terminal or Command Prompt
Navigate to the folder where your notebook and dataset are saved, for example:

cd "C:\Users\<YourName>\Documents\StudentDropoutProject"


Create and Activate a Virtual Environment (recommended)

python -m venv venv
venv\Scripts\activate         # For Windows
source venv/bin/activate      # For macOS/Linux


Install Required Dependencies
Install all the necessary Python libraries using pip:

pip install pandas numpy scikit-learn matplotlib seaborn plotly xgboost jupyter


Launch Jupyter Notebook
Start the notebook environment:

jupyter notebook


Open and Run the Notebook

In Jupyter, open the file:
Forecasting_Student_Dropouts_and_Academic_Success.ipynb

Run each cell in order (Shift + Enter).

The notebook will:

Load and preprocess the student dataset

Perform exploratory data analysis (EDA)

Train classification and regression models

Evaluate and display performance metrics

Generate visual insights and feature importance charts

Dependencies List
pandas
numpy
scikit-learn
matplotlib
seaborn
plotly
xgboost
jupyter
