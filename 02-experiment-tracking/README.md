Install environment:
```sh
poetry install
```

Run MLFlow:
```sh
cd homework
mlflow server --backend-store-uri sqlite:///mlflow.db --default-artifact-root mlartifacts
```