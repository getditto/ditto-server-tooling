# Ditto Server Tooling

Monitoring dashboards, reference deployment examples, and utilities for the self-managed Ditto Server offering.

This repository holds artefacts that users may find useful deployed alongside a self-managed Ditto Server (Big Peer) deployment, but don't belong inside the Ditto Operator itself.

## What's in here

- **`dashboards/grafana`** Grafana dashboards for the components that make up a Ditto Server deployment (API, store, subscription, and the Kafka transaction log). Importable as JSON and versioned so you can track changes.

More coming soon!

## Requirements

These assets assume a running Ditto Server deployment managed by the Ditto Operator.

The Grafana dashboards require a running Grafana and a Prometheus-compatible data source. Reference deployments for these are coming soon.


## Support

This repository is maintained separately from the Operator, and the contents are not managed or supported by the Ditto Operator itself. The contents of this repo are provided as templates, best practice examples and complementary tooling which users can adapt at their own discretion.

If you have any feedback about for this repo, please get in touch with your Ditto account/FDE contact. For questions about Ditto Server or the Ditto Operator itself, please contact [Ditto Support](https://support.ditto.com).
