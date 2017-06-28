# helm-alertmanager

## Prerequisites
If running against a new or local environment then make sure you have initialized first.
```
helm init
```

## Install

It is best to install the alertmanager through the helm-prometheus helm chart.  The Alertmanager is one of the helm-prometheus chart dependencies. Not directly using the method below.

```
git clone git@github.com:Smarsh/helm-alermanager.git
cd helm-alertmanager
helm install . --set Service.Type=NodePort 
```

## Notifications

### Email

Notification are sent via MS office 365 to an email list named 'X-Prom-Alerts@smarsh.com'.  The repeat interval is 15 minutes.

### Pager Duty

  *TBD*

### Slack

  *TBD*

### HipChat

  *This will probably not be supported.*

## Known Issues


