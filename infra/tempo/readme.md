[Documentation](https://github.com/grafana/helm-charts/tree/main/charts/tempo)

## Installation

```shell
helm install tempo grafana/tempo -f values.yml -n zerofiltre-bootcamp --version=1.21.1
```


## Upgrade 
```shell
helm upgrade tempo grafana/tempo -f values.yml -n zerofiltre-bootcamp --version=1.21.1
```

## Deletion
```shell
helm un tempo -n zerofiltre-bootcamp
```


