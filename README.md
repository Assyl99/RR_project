# RR_project

## Team members:

- Poojitha annabathula 
- Zuzanna Kowalczyk 
- Assyl Salah 
- Viktor Sas 

## Project Description
This project replicates and extends a regression-based analysis of video game sales originally done in R. The aim is to make it fully reproducibility in python. 

## Project Overview
- Predict global video game sales using features such as critic scores, user scores, and game age.
- Apply and compare multiple regression models: **Linear Regression**, **KNN**, and **Decision Tree**.
- Evaluate models using **RMSE**, **MAE**, and **R² Score**.
- Visualize correlations and distributions.
- Apply **cross-validation** to assess model generalization.

## Prerequisites

- Python 3.12.4
- Python package installer (Pip)
- Visual studio code or Juypter notebook

## 1. Installation

### 1.1  Install Python

Go to https://www.python.org/downloads/ and download python version 3.12.4 for your OS (Windows, macOS, or Linux). During installation for windows, make sure to check `Add Python to PATH.` Verify by opening a terminal and typing:

- ```python --version```
- ```pip --version```


### 1.2 Install Visual studio code
Download from https://code.visualstudio.com/. **Open VS Code**, then go to **Extensions** (left sidebar) and install:

- Python by Microsoft 
- Pylance by Microsoft 
- Jupyter by Microsoft 



## 2. Clone the Repository

Start by cloning the repository using bash, command line or git bash


- ```git clone https://github.com/Assyl99/RR_project.git```
- ```cd RR_project``` 

## 3. Set Up a Virtual Environment 
To create virtual environment, run the following commands in the Visual studio code terminal: 

- ```python -m venv .venv``` on `windows` or ```python3 -m venv .venv``` for `macOS/Linux`.
- ```source venv/Scripts/activate``` This is command from git bash and for `macOS/Linux`.
-```.\.venv\Scripts\Activate.ps1``` run this if you are using `windows`. If you get the error of `UnauthorizedAcces` run the following command ```Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser``` then run the activate command again. 

The PowerShell prompt should change to ```(.venv) PS C:\…>``` for `windows`. Then proceed to install packages and run Python as usual.

## 4. Install Required Libraries
1. Before installing libraries if you already have some of them installed upgrage pip by the following command:
```python -m pip install --upgrade pip setuptools wheel```

2. In the terminal run the following command: 
```pip install -r requirements.txt ```


## Acknowledgment

We would like to acknowledge the use of AI tools that assisted with formatting and refining some of the code for generating charts. Although We performed all analyses, data wrangling, and core conceptual work based on the original project written in `R`,  We consulted AI-based suggestions to streamline Seaborn plotting syntax and verify code structure.

## Original project link: 
```https://www.kaggle.com/code/yonatanrabinovich/video-games-sales-regression-techniques```
