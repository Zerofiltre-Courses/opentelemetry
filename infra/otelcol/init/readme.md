👉 [Repo](https://github.com/open-telemetry/opentelemetry-helm-charts)

👉 [Documentation](https://opentelemetry.io/docs/kubernetes/helm/collector/)

## Ajout du repo
```shell
helm repo add open-telemetry https://open-telemetry.github.io/opentelemetry-helm-charts
```


## Installation

```shell
 helm install otelcol open-telemetry/opentelemetry-collector -f values.yml -n namespace --version 0.126.0
```

## Upgrade

```shell
 helm upgrade otelcol open-telemetry/opentelemetry-collector -f values.yml -n namespace --version 0.126.0
```


## Deletion
```shell
helm un otelcol -n namespace
```

