# Cosanet Helm Charts

This repository contains the Helm chart for deploying Cosanet on Kubernetes.

- [cosanet project](https://github.com/cosanet/cosanet)

## Usage

### Prerequisites

- [Helm](https://helm.sh/) 3.x
- Access to a Kubernetes cluster

### Install the Chart

```bash
helm repo add cosanet https://cosanet.github.io/charts
helm install cosanet cosanet
```

## Configuration

Refer to [`values.yaml`](https://github.com/cosanet/charts/blob/main/charts/cosanet/values.yaml) and [Cosanet's arguments documentation](https://github.com/cosanet/cosanet#arguments) for all available configuration options.
