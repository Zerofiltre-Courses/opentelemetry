## Source : https://github.com/prometheus-community/helm-charts/tree/main/charts/prometheus

**Installing**

```` 
helm install prometheus prometheus-community/prometheus -f values.yml -n zerofiltre-bootcamp --version 27.20.0
````

**Upgrading**

```
helm upgrade prometheus prometheus-community/prometheus -f values.yml -n zerofiltre-bootcamp --version 27.20.0
```
