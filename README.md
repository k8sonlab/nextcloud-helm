# Nextcloud Helm Charts - forked from original helm

[Helm](https://helm.sh) repo for different charts related to Nextcloud which can be installed on [Kubernetes](https://kubernetes.io)

### Add Helm repository

To install the repo just run:

```bash
helm repo add nextcloud https://k8sonlab.github.io/nextcloud-helm/
helm repo update
```

### Helm Charts

* [nextcloud](https://nextcloud.github.io/helm/)

  ```bash
  helm install my-release nextcloud/nextcloud
  ```
