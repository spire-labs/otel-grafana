A cookie cutter instance of grafana for local development.

To include this in your compose file you can add

```
include:
  - oci://ghcr.io/spire-labs/otel-grafana:latest
```

For projects that don't need Grafana or need a customized instance of Grafana, use the no-grafana variant:

```
include:
  - oci://ghcr.io/spire-labs/otel-grafana:no-grafana
```

Depending on what version of docker you're running, you may need to set `COMPOSE_EXPERIMENTAL_OCI_REMOTE=true` 
