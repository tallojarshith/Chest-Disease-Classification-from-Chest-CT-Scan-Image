# Chest-Disease-Classification-from-Chest-CT-Scan-Image

## workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main


## How to run?

```bash
conda create -n chnv python=3.8 -y
```

```bash
conda activate chnv
```

```bash
pip install -r requirements.txt
```
```bash
python app.py
```

## mlflow dagshub connection uri
```bash
MLFLOW_TRACKING_URI=https://dagshub.com/tallojarshith/Chest-Disease-Classification-from-Chest-CT-Scan-Image.mlflow \
MLFLOW_TRACKING_USERNAME=tallojarshith \
MLFLOW_TRACKING_PASSWORD=04a304871261fea53077042e31f26c95473c78c0 \
python script.py
```

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/tallojarshith/Chest-Disease-Classification-from-Chest-CT-Scan-Image.mlflow
export MLFLOW_TRACKING_USERNAME=tallojarshith 
export MLFLOW_TRACKING_PASSWORD=04a304871261fea53077042e31f26c95473c78c0
```bash

```bash
1. dvc init
2. dvc repro
3. dvc dag
```bash