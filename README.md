# helm-alertmanager

## Prerequisites
If running against a new or local environment then make sure you have initialized first.
```
helm init
```

## Install
```
git clone git@github.com:Smarsh/helm-alermanager.git
cd helm-alertmanager
helm install . --set Service.Type=NodePort 
```
