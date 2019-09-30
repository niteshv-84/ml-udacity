Machine Learning Engineer Nanodegree Capstone Project
==============================

This github repo contains capstone project for Udacity's Machine Learning Nanodegree. 

#### Problem Statement:
Build a machine learning model to detect if a child is suffering from pneumonia using chest x-ray images.

## Setup Instructions
-------------
 Download the repo to the current directory. To create an anaconda environment run the following. 
 
```
conda env create -f environment.yml
```

The input data-set for the project is available on kaggle and can be downloaded from the below url

https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia/download 

This dataset need to be stored inside the input folder in the following structure.

### Input Structure
------------ 
    |─ input
    |   |─ chest_xray
    |        |── train
    |              |──NORMAL
    |              |── PNEUMONIA
    |        |── val
    |              |──NORMAL
    |              |── PNEUMONIA
    |        |── test
    |              |──NORMAL
    |              |── PNEUMONIA
  
 


### Project Organization
------------

   
    ├── README.md            <- The top-level README file
    ├── input
    │   ├── chest_xray       <- Folder where the original input images need to be stored. Detailed structure explained above.
    │   ├── transformed      <- Folder which will store the transformed images (transformed as part of data pre-processing)
    │
    ├── proposal.pdf         <- Capstone project proposal
    │
    ├── report.pdf          <- Capstone project report.
	│
    ├── capstone-notebook.ipynb            <- Jupyter Notebook for the project
    │
    ├── environment.yml   <- The environment file for reproducing the analysis environment.
    
--------

