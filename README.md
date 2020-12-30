## configure helm 

curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh

# Airflow Community Helm Charts

## Charts

| name | description |
| --- | --- |
| [charts/airflow](https://github.com/airflow-helm/charts/tree/main/charts/airflow) | the continuation of [stable/airflow](https://github.com/helm/charts/tree/master/stable/airflow), by the same maintainers

## Repo Usage

```sh
helm repo add airflow-stable https://airflow-helm.github.io/charts
helm repo update
```

## Contributing

Please refer to [CONTRIBUTING.md](https://github.com/airflow-helm/charts/tree/main/CONTRIBUTING.md) for details.
