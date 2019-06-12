# Smallstep Helm Charts

This is a [Helm](https://helm.sh) repository with packages for Kubernetes.

To install the [Smallstep](https://smallstep.com) repo just run:

```console
helm repo add smallstep  https://smallstep.github.io/helm-charts
helm repo update
```

## Packages

* [Step Certificates](https://github.com/smallstep/helm-charts/blob/master/step-ca/README.md):
  An online certificate authority and related tools for secure automated
  certificate management, so you can use TLS everywhere.
  Install step-certificates using:
  
  ```console
  helm install --name your-release smallstep/step-certificates
  ```