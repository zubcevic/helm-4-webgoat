# WebGoat Helm chart

This helm chart can be used to install WebGoat and WebWolf on a kubernetes runtime environment.

## Usage

    helm install webgoat

> **Note:** This helm chart is provided for convenience of helm chart uses. WebGoat can be installed in many ways.

**What it does:**

- Spin up a container with WebGoat and WebWolf inside

## Configuration

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| service.port | int | `8080` |  |
| service.type | string | `"ClusterIP"` |  |
