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

## Dags hub

import dagshub
dagshub.init(repo_owner='MannShrestha', repo_name='MLflow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)