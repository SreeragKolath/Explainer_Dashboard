## Explainer Dashboard

👉**what is Explainer Dashboard**

explainerdashboard is a library for quickly building interactive dashboards for analyzing and explaining the predictions and workings of (scikit-learn compatible) machine learning models, including xgboost, catboost and lightgbm. This makes your model transparant and explainable with just two lines of code. 

It allows you to investigate SHAP values, permutation importances, interaction effects, partial dependence plots, all kinds of performance plots, and even individual decision trees inside a random forest. With explainerdashboard any data scientist can create an interactive explainable AI web app in minutes, without having to know anything about web development or deployment.

👉**What is this repository about?**

In this repository, we are going to build Interactive dashboard for a Machine Learning model using ExplainerDashboard library in Python. The jupyter notebook (.ipynb) and this readme provide the code and all the relevant information about this tutorial. 

👉**Dataset taken:**

I have taken **California dataset** imported from **sklearn** for creating interactive dastboard. This dataset is used to train the Regression model and build the interactive Machine Learning dashboard.

👉**How to install explainerdashboard:**

  **!pip install explainerdashboard**
  
- You can use this command in Colab or a Kaggle notebook directly. However, if using a Jupyter notebook running on a local machine, using a virtual environment might be a better choice to avoid any conflict due to the package dependencies.

👉**Approch followed:**

- Import the libraries and load **california dataset** from **sklearn**
- Create DataFrame from the dataset (No data preprocessing required for this demo tutorial)
- Split the data and train the model
- Deploy the dashboard on a local port

## More Information:

Learn more about explainer dashboard [here](https://github.com/oegedijk/explainerdashboard).










