# Helm-Charts

This repository contains [Helm](https://helm.sh) charts for various projects. Garner is currently only using/modifying the [Distributed Loki](https://github.com/garnercorp/helm-charts/tree/master/charts/distributed-loki) chart.

The original versions of the charts can be found here:

- [Distributed Loki](https://github.com/whyeasy/helm-charts/tree/master/charts/distributed-loki)
- [Gitlab-extra-exporter](https://github.com/Whyeasy/helm-charts/tree/master/charts/gitlab-extra-exporter)
- [Jira-exporter](https://github.com/Whyeasy/helm-charts/tree/master/charts/jira-exporter)
- [Jira-sd-exporter](https://github.com/Whyeasy/helm-charts/tree/master/charts/jira-sd-exporter)
- [k8s Node Termination Handler](https://github.com/whyeasy/helm-charts/tree/master/charts/k8s-node-termination-handler)
- [Osiris](https://github.com/whyeasy/helm-charts/tree/master/charts/osiris)
- [Prometheus MongoDb Exporter](https://github.com/whyeasy/helm-charts/tree/master/charts/prometheus-mongodb-exporter)
- [Stackdriver-exporter](https://github.com/Whyeasy/helm-charts/tree/master/charts/stackdriver-exporter)
- [Sonarcloud-exporter](https://github.com/Whyeasy/helm-charts/tree/master/charts/sonarcloud-exporter)
- [Version-checker](https://github.com/Whyeasy/helm-charts/tree/master/charts/version-checker)

## Installing the Loki Chart from this Repository
Add the Repository to Helm:
```
helm repo add garnercorp-helm-charts https://garnercorp.github.io/helm-charts
```
Install the chart:
```
helm install garnercorp-helm-charts/loki-distributed
```
