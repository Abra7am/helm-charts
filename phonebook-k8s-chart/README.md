```bash
helm repo add helm-charts https://raw.githubusercontent.com/Abra7am/helm-charts/main
helm install phonebook-app helm-charts/phonebook-k8s-chart
```

- To use your own images execute the following;


```bash
helm install phonebook-app helm-charts --set webserver_image=<image-name>  --set result_server=<image-name>
```



