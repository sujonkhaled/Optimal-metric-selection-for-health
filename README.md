# Optimal-metric-selection-for-health
# AIDS Virus Infection Prediction Using Machine Learning Metrics

## Overview
This repository contains the core experiment code for our research paper titled "F1, MCC, and AUC-ROC through the Lens of Machine Learning, Statistics, and XAI: Optimal Performance Metric Selection for Health Data Mining"**.  Our primary goal was to select the optimal performance metric for the health data mining. we conducted various tests to validate our hypothesis in this research. The study uses machine learning models to predict the likelihood of AIDS virus infection based on various clinical and demographic features.

## Dataset
We used the "AIDS Virus Infection Prediction Dataset" by A. Velu (2023), which was collected from Kaggle. This dataset contains the following features:

- **(a) time**: Time duration  
- **(b) trt**: Treatment type  
- **(c) age**: Age of the individual  
- **(d) wtkg**: Weight in kilograms  
- **(e) hemo**: Hemoglobin levels  
- **(f) homo**: Homozygous gene status  
- **(g) drugs**: Drug usage  
- **(h) karnof**: Karnofsky performance score  
- **(i) oprior**: History of opportunistic infections  
- **(j) z30**: Z-score at 30 days  
- **(k) preanti**: Pre-antiretroviral treatment status  
- **(l) race**: Race of the individual  
- **(m) gender**: Gender of the individual  
- **(n) str2**: Stratification variable 2  
- **(o) strat**: Stratification variable  
- **(p) symptom**: Presence of symptoms  
- **(q) treat**: Treatment received  
- **(r) offtrt**: Treatment discontinued status  
- **(s) cd40**: CD4+ cell count at 40 days  
- **(t) cd420**: CD4+ cell count at 420 days  
- **(u) cd80**: CD8+ cell count at 80 days  
- **(v) cd820**: CD8+ cell count at 820 days  

The target variable is **infected**, which indicates whether an individual is infected with the AIDS virus. The dataset was accessed on November 11, 2023.

### Note:
The dataset is not included in this repository as the dataset is publicly available . You can download the dataset from Kaggle at : https://www.kaggle.com/datasets/aadarshvelu/aids-virus-infection-prediction 

##Citation
If you use this  experiment in your research, please cite our paper
 

## Contents
This repository includes:
- **`health_data_metric_selection.py`**: The main Python script for the experiment.
- **`requirements.txt`**: A list of dependencies required to run the code.

## Prerequisites
You need **Python 3.8 or later**. Install the dependencies listed in `requirements.txt` using:
```bash
pip install -r requirements.txt




