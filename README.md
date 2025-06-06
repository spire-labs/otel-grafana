A cookie cutter instance of grafana for local development.

To include this in your compose file you can add

```
include:
  - oci://ghcr.io/spire-labs/otel-grafana:latest

```


Depending on what version of docker you're running, you may need to set `COMPOSE_EXPERIMENTAL_OCI_REMOTE=true` 
