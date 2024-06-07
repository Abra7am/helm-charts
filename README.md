```bash
helm repo add helm-charts https://raw.githubusercontent.com/Abra7am/helm-charts/main
helm install phonebook-chart helm-charts/phonebook-chart
```

- To use your own images run below commands;

```bash
helm install phonebook-chart helm-charts/phonebook-chart --set webserver_image=<image_name>  --set resultserver_image=<image_name>
```