
Raven-miner
===========

A Helm chart for Kubernetes


## Configuration

The following table lists the configurable parameters of the Raven-miner chart and their default values.

| Parameter                | Description             | Default        |
| ------------------------ | ----------------------- | -------------- |
| `address` | Address of wallet for the miner | `null` |
| `replicaCount` |  | `1` |
| `image.repository` |  | `"miner/raven"` |
| `image.pullPolicy` |  | `"IfNotPresent"` |
| `image.tag` |  | `"0.0.1"` |
| `imagePullSecrets` |  | `[]` |
| `nameOverride` |  | `""` |
| `fullnameOverride` |  | `""` |
| `serviceAccount.create` |  | `false` |
| `serviceAccount.annotations` |  | `{}` |
| `serviceAccount.name` |  | `""` |
| `podAnnotations` |  | `{}` |
| `podSecurityContext` |  | `{}` |
| `securityContext` |  | `{}` |
| `service.type` |  | `"ClusterIP"` |
| `service.port` |  | `8443` |
| `ingress.enabled` |  | `false` |
| `ingress.className` |  | `""` |
| `ingress.annotations` |  | `{}` |
| `ingress.hosts` |  | `[{"host": "miner.example", "paths": [{"path": "/", "pathType": "Prefix"}]}]` |
| `ingress.tls` |  | `[]` |
| `resources` |  | `{}` |
| `nodeSelector` |  | `{}` |
| `tolerations` |  | `[]` |
| `affinity` |  | `{}` |



---
_Documentation generated by [Frigate](https://frigate.readthedocs.io)._

