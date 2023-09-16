# Customer segmentation

## Introduction
* This is a machine learning classifier, this project is about customer segmentation for an automobile company that aims to have groups of customers that have similar features and behaviors in order to offer each of them a unique experience and opportunity to give an important step as buy a car. 

<div align="center">
    <img src="./images/customer_segmnt.png" width="423" height="300">
</div>


* [Kaggle Dataset](https://www.kaggle.com/datasets/abisheksudarshan/customer-segmentation)

## Instructions
 - In order to run the model into your local environment, you will need to clone the repo 
 ```bash
     git clone git@github.com:LeonardoOlmos/bc-final-project.git
 ```
 - Once the repo was cloned, you will need to install all the required libraries by running:
 ```bash
     pip install -r requirements.txt
 ```
 - Finally you have to open the file with `jupyter-notebooks` or `google-collaboratory` to run it
 - Before running `v1_0.ipynb` it's necessary to run `encoders, scalers and models`

## Main structure
- Into this repo you will find the next structure

```
├── bc-final-project
│   ├── README.txt
│   ├── data
│   ├── encoders
│   ├── images
│   ├── models
│   ├── notebooks
│   ├── scalers
│   ├── requirements.tx
```

* README: File to add docs to the repo
* data: Folder used to store all those files used as data source anda data ouput.
* encoders: Folder with small pieces of code used as encoders for the project.
* images: Folder that stores images required by README file.
* models: Folder with small pieces of code used as models for the project.
* scalers.sql: Folder with small pieces of code used as scalers for the project.
* notebooks: Main file with the logic required to run the project.
* requirements.txt: File with libraries required to run the project.
