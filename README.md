<h1 style="text-align: center; border-bottom: 1px dashed">car_price_analysis</h1>
 This repository contains files that were cleaned, engineered and used to make predictions using different regression models as well as evaluating all the models to see the best performing model.

 ## THE LIST OF PROJECTS IN THIS REPOSITORY SO FAR ARE;
 <ol>
 <li><a href="#cleaning">Cleaning A car price dataset</a>
 <li><a href="#engineering">Engineering Features on a dataset</a>
 <li><a href="#model">Model Creation and prediction on a dataset</a>
 </ol>

<h2 id="cleaning"><b>1. Cleaning A car price dataset</b></h2>A jupyter notebook file that consists of python libraries used to clean a dataset "(cars.data)" already in the repository, the dataset contains several columns and empty rows that needed cleaning, dummy variables was created becuae the csv file is going to be used for some machine learning models and the notebook was created and step by step comments on each block was made so as to make the user understand what happens per block of code. <b>Name of project (car_price_cleaning.ipynb)</b>

## Technology used in this project
<ul>
<li> Python programming language and some of its libraries
<ul>
<li> Jupyter Notebook
<li> Pandas
<li> Matplotlib
<li> Numpy
</ul>
</ul>

<h2 id="engineering"><b>2. Engineering Features on a dataset</b></h2>This dataset has already been cleaned in the first notebook (car_price_cleaning.ipynb), the already cleaned dataset ("cleanead_car_price.csv") was then imported into this notebook, feature engineering (Called data engineering by some people) was done on the dataset to pick the features that can actually be used in our model for a better accuracy. <b>Name of project (car_price_engineering.ipynb)</b>

## Technology used in this project
<ul>
<li> Python programming language and some of its libraries
<ul>
<li> Jupyter Notebook
<li> Pandas
<li> Matplotlib
<li> Seaborn
<li> Scipy
</ul>
</ul>

<h2 id="model"><b>3. Model Creation and prediction on a dataset</b></h2>This dataset has already been cleaned in the first notebook (car_price_cleaning.ipynb), the already cleaned and used to engineer the features in (car_price_engineering.ipynb), the already engineered features ("features_car.csv") were used to train models and and make prediction, after the models have been trained they were tested, validated and evaluated. <b>Name of project (car_price_model.ipynb)</b>

## Technology used in this project
<ul>
    <li> Python programming language and some of its tools
    <ul>
        <li> Jupyter Notebook
        <li> Pandas
    </ul>
    <li> sklearn
    <ul>
        <li> train_test_split
        <li> sklearn.ensemble
        <li> sklearn.linear_model
        <li> sklearn.tree
        <li> sklearn.metrics
    </ul>
</ul>
<hr>
<div style="text-align: center;">
<a href="https://oluwaseun-ogundeko.netlify.app/">Learn more about me!</a>
</div>