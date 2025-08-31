# Cosanet Helm Charts

This repository contains the Helm chart for deploying Cosanet on Kubernetes.

<p align="center"><a href="https://github.com/cosanet/cosanet" rel="cosanet"><img src="https://raw.githubusercontent.com/cosanet/cosanet/master/logo/cosanet_logo_256.png" alt="Cosanet Logo" width="256"></a></p>

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
