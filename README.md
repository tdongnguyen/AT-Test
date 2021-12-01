# AT technical test

A small project to test technical skills for Data Scientist Role in Auckland Transport

## Description

A technical test project, part of the recruitment process for the Data Scientist Role in Auckland Transport. In this project, author uses [the provided dataset](https://github.com/tdongnguyen/AT-Test/blob/f9ab9cd6fe7d766d94e3a3c713cabbc51c12e58b/Technical%20test%20sample%20data.ods) and follow a [guideline](https://github.com/tdongnguyen/AT-Test/blob/415ef83f54245291b9166a738612a51551ccf9da/AT%20ML%20technical%20Test.docx) from AT. This project is basically about building a fraud detection unsupervised model, pack it up as a package and prepare a presentation for findings. 

## Business Problem

* Technical Test for candidate
* Fraud Dectection
* Scaleable model building
* Find applicable insights to support business 

## Technical Methods

### Methods
* Inferential Statistics
* mice (Multivariate Imputation by Chained Equations) - [Reference](https://impyute.readthedocs.io/en/latest/_modules/impyute/imputation/cs/mice.html)
* IQR (Interquartile Range) - [Reference](https://en.wikipedia.org/wiki/Interquartile_range)
* Machine Learning Algorithm: Isolation Forest - [Reference](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)
* Machine Learning Algorithm: RandomForestRegressor - [Reference](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)

### Technologies
* Python
* Jupyter Notebook
* Pandas
* Numpy
* Pickle
* Visualisation: Seaborn, Matplotlib

## Results - Findings

Presentation [here](https://github.com/tdongnguyen/AT-Test/blob/5a9a52fbdd931e4097231d7ec67af32e30c79ca9/Presentation.pptx)

## Repository

* README.md
* AT Test - Nov 2021.ipynb  (Main Script Notebook)
* Presentation.pptx (Presentation to stakeholder)
* Technical test sample data.ods (Raw Data)
* AT ML technical Test.docx (AT Guideline)
* Data.odsanomaly_iforest2021_12_01.pkl (Pickle file where saved trained model)
* Fraud Detection - Predict.ipynb (Predict Script Notebook)

## Running steps

1. Clone this repo
2. Raw Data is being kept [here](https://github.com/tdongnguyen/AT-Test/blob/f9ab9cd6fe7d766d94e3a3c713cabbc51c12e58b/Technical%20test%20sample%20data.ods) within this repo.
3. Main Script is being kept [here](https://github.com/tdongnguyen/AT-Test/blob/f9ab9cd6fe7d766d94e3a3c713cabbc51c12e58b/AT%20Test%20-%20Nov%202021.ipynb)
4. Run the training Script (Note: Change the path of input file to where you save data in your local machine)
5. Using the pickle which is being kept [here](https://github.com/tdongnguyen/AT-Test/blob/1dabb3b4442f4eb97890c27d94932b990ed9bf56/Data.odsanomaly_iforest2021_12_01.pkl) to scoring more data. 
6. Run the prediction script  with new data to score data [here](https://github.com/tdongnguyen/AT-Test/blob/1dabb3b4442f4eb97890c27d94932b990ed9bf56/Fraud%20Detection%20-%20Predict.ipynb).

## Author
Ryan Truong - ryantruong1987@gmail.com




