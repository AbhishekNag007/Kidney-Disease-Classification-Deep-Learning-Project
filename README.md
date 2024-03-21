# Kidney-Disease-Classification-Deep-Learning-Project
Kidney Disease

# Workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml
10. app.py


# How to run

# STEPS

Clone the repository
```bash
https://github.com/AbhishekNag007/Kidney-Disease-Classification-Deep-Learning-Project
```

# STEP 1: Create a conda environment after opening the repository
```bash
conda create -n kidney
```
```bash
conda activate kidney
```

# STEP 2: install the requirements
```bash
pip install -r requirements.txt
```
```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui


### dagshub
[dagshub](https://dagshub.com)

MLFLOW_TRACKING_URI=https://dagshub.com/AbhishekNag007/Kidney-Disease-Classification-Deep-Learning-Project.mlflow \
MLFLOW_TRACKING_USERNAME=AbhishekNag007 \
MLFLOW_TRACKING_PASSWORD=2973e83d8aa80974eb004d828d372468dc9ede81 \
python script.py


Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/AbhishekNag007/Kidney-Disease-Classification-Deep-Learning-Project.mlflow

export MLFLOW_TRACKING_USERNAME=AbhishekNag007

export MLFLOW_TRACKING_PASSWORD=2973e83d8aa80974eb004d828d372468dc9ede81

```

```bash
$env:MLFLOW_TRACKING_URI="https://dagshub.com/AbhishekNag007/Kidney-Disease-Classification-Deep-Learning-Project.mlflow"
$env:MLFLOW_TRACKING_USERNAME="AbhishekNag007"
$env:MLFLOW_TRACKING_PASSWORD="2973e83d8aa80974eb004d828d372468dc9ede81"
```