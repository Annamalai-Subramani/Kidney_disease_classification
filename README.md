# Kidney-Disease-Classification-MLflow-DVC

# Workflows
1.  Update config.yaml
2.  Update secrets.yaml [Optional]
3.  Update params.yaml
4.  Update the entity
5.  Update the configuration manager in src config
6.  Update the components
7.  Update the pipeline
8.  Update the main.py
9.  Update the dvc.yaml
10. app.py


# How to run?
## STEPS:
     Clone the repository

     https://github.com/Annamalai-Subramani/Kidney_disease_classification

## STEP 01- Create a conda environment after opening the repository
    conda create -n cnncls python=3.8 -y
    conda activate cnncls
## STEP 02- install the requirements
    pip install -r requirements.txt
## Finally run the following command
    python app.py


# Dagshub

MLFLOW_TRACKING_URI=https://dagshub.com/Annamalai-Subramani/Kidney_disease_classification.mlflow \
MLFLOW_TRACKING_USERNAME=Annamalai-Subramani \
MLFLOW_TRACKING_PASSWORD=5834dc456909f93114f5f78ede42333d46fdb630 \

  Run this to export as env variables:

set MLFLOW_TRACKING_URI=https://dagshub.com/Annamalai-Subramani/Kidney_disease_classification.mlflow

set MLFLOW_TRACKING_USERNAME=Annamalai-Subramani 

set MLFLOW_TRACKING_PASSWORD=5834dc456909f93114f5f78ede42333d46fdb630

python script.py

# DVC cmd
  1. dvc init
  2. dvc repro
  3. dvc dag


# About MLflow & DVC

  MLflow

1. Its Production Grade
2. Trace all of your expriements
3. Logging & taging your model

   DVC

1. Its very lite weight for POC only
2. lite weight expriements tracker
3. It can perform Orchestration (Creating Pipelines)

