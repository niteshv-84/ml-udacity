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

This dataset need to be stored inside a folder named ```input``` at the same level as the notebook.
The different folders need to be stored in the following order.


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
    ├── proposal-review.pdf         <- Capstone project proposal review
    │
    ├── report.pdf          <- Capstone project report.
	│
    ├── capstone-notebook.ipynb            <- Jupyter Notebook for the project
    │
    ├── environment.yml   <- The environment file for reproducing the analysis environment.
    
--------

