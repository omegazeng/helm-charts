# nginx-ldap-auth-backend

## TL;DR

```bash
helm repo add omegazeng https://omegazeng.github.io/helm-charts
helm install omegazeng/nginx-ldap-auth-backend
```

## Introduction

This [Helm](https://github.com/kubernetes/helm) chart installs [nginx-ldap-auth-backend](https://github.com/nginxinc/nginx-ldap-auth) in a Kubernetes cluster.

## Prerequisites

- Kubernetes cluster 1.13+ with Beta APIs enabled
- Helm 2.11.0+

## Installing the Chart

```bash
helm repo add omegazeng https://omegazeng.github.io/helm-charts
helm install --name my-release omegazeng/nginx-ldap-auth-backend
```

The command deploys nginx-ldap-auth-backend on the Kubernetes cluster with the default configuration.
The [configuration](#configuration) section lists the parameters that can be configured in values.yaml or via '--set' flag during installation.

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```bash
helm delete --purge my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

The configurable parameters of the chart and the default values.

See [values.yaml](values.yaml)
