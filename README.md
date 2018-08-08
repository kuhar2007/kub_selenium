## _kub_selenium_
kub_selenium - orchestrating docker-selenium via Kubernetes using .yaml scripts

-------------------------

### Launch a Selenium-hub
```
$ kubectl -f create kube-rc.yaml
```

### Launch a Selenium-hub as a service
```
$ kubectl -f create kube-service.yaml
```

### Bring up 2 Selenium nodes with FireFox
```
$ kubectl -f create firefox.yaml
```