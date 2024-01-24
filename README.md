# Falco Helm Chart

## Overview

[Falco](https://falco.org/) is an open-source cloud-native runtime security project. This Helm chart simplifies the deployment of Falco on Kubernetes using Helm.

## Prerequisites

- Kubernetes cluster
- Helm installed ([Installing Helm](https://helm.sh/docs/intro/install/))
- Falco dependencies (e.g., Elasticsearch, Fluentd, etc.) configured if needed

## Installation

```bash
helm install falco .

## To run Falco Sidekick locally and access its web interface, use the following command:
```bash
kubectl port-forward falcosidekick-ui-pod-suffix-number 2802:2802

## Note
By default, you need to enter "admin" as both the username and password for the web interface.

