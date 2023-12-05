# kidney-disease-classification

## Workflows
1. Update config.yaml
2. Update secrets.yaml [optional]
3. Update params.yaml
4. Update entity
5. Update configuration manager in src config
6. Update components
7. Update pipeline
8. Update main.py
9. Update dvc.yaml
10. Update app.py

# How to run?
### STEPS:

Clone the repo

```bash
https://github.com/subhankar710/kidney-disease-classification
```

### STEP 01 - Create a conda environment after opening the repository.

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```

### STEP 02 - Install requirements
```bash
pip install -r requirements.txt
```

## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/subhankar710/kidney-disease-classification.mlflow \
MLFLOW_TRACKING_USERNAME=subhankar710 \
MLFLOW_TRACKING_PASSWORD=c317dbf89090a80de63883c0918efa55c70a7fa2 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/subhankar710/kidney-disease-classification.mlflow

export MLFLOW_TRACKING_USERNAME=subhankar710 

export MLFLOW_TRACKING_PASSWORD=c317dbf89090a80de63883c0918efa55c70a7fa2

```
