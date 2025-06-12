👉🏼 [Repository]()

- Add chart :
```shell
helm repo add grafana https://grafana.github.io/helm-charts
```

- Install
```shell
helm install -f values.yaml loki-backend grafana/loki -n zerofiltre-bootcamp --version 6.30.1
```


- Upgrade
```shell
helm ugrade -f values.yaml loki-backend grafana/loki -n zerofiltre-bootcamp --version 6.30.1
```