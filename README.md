## MLflow Experiment

### MLflow site: [https://mlflow.org/docs/latest/index.html]

## How to run?
### Create conda environment

```bash

conda create -p venv python==3.9 -y
```

```bash

conda activate venv/
```

```bash

python app.py
```

```bash

mlflow ui
```

## parameter Experiment 1

```bash

python app.py 0.3 0.7
```

```bash

mlflow ui
```

## parameter Experiment 2

```bash

python app.py 0.6 0.6
```

```bash

mlflow ui
```

## Dags hub -> connect with github account

MLFLOW_TRACKING_URI=https://dagshub.com/MannShrestha/MLflowExperiment.mlflow
MLFLOW_TRACKING_USERNAME=MannShrestha
MLFLOW_TRACKING_PASSWORD=41f801ddadfd672ed6133c408cdff17b1a85368b
python script.py

## VScode Terminal
```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/MannShrestha/MLflowExperiment.mlflow
```

```bash
export MLFLOW_TRACKING_USERNAME=MannShrestha
```

```bash
export MLFLOW_TRACKING_PASSWORD=41f801ddadfd672ed6133c408cdff17b1a85368b
```