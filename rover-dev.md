# Run rover dev. Replace ... with your own values

```sh
APOLLO_KEY=service:sv15-connectors-supe-g2d7pn:bf8sI00f1Kj9-fxm9PITcA \
APOLLO_GRAPH_REF=sv15-connectors-supe-g2d7pn@current \
APOLLO_ROVER_DEV_ROUTER_VERSION=2.0.0-preview.0 \
rover dev --supergraph-config supergraph.yaml --router-config router-config.yaml
```

```powershell
$env:APOLLO_KEY="service:sv15-connectors-supe-g2d7pn:bf8sI00f1Kj9-fxm9PITcA"
$env:APOLLO_GRAPH_REF="sv15-connectors-supe-g2d7pn@current"
$env:APOLLO_ROVER_DEV_ROUTER_VERSION="2.0.0-preview.0"
rover dev --supergraph-config supergraph.yaml --router-config router-config.yaml
```

APOLLO_KEY=service:sv15-connectors-supe-g2d7pn:bf8sI00f1Kj9-fxm9PITcA \
  APOLLO_GRAPH_REF=sv15-connectors-supe-g2d7pn@current \
  APOLLO_ROVER_DEV_ROUTER_VERSION=2.0.0-preview.0 \
  rover dev --supergraph-config supergraph.yaml