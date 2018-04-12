This nifi README may be used as a starting point for writing a Service Guide for your DC/OS Service.

Apache NiFi is a dataflow system based on the concepts of flow-based programming. It supports powerful and scalable directed graphs of data routing, transformation and system mediation logic. NiFi has a web-based user interface for design, control, feedback, and monitoring of dataflows. It is highly configurable along several dimensions of quality of service, such as loss-tolerant versus guaranteed delivery, low latency versus high throughput and priority-based queuing. NiFi provides fine-grained data provenance for all data received, forked, joined cloned, modified, sent and ultimately dropped upon reaching its configured end-state.

DC/OS NiFi Service is an automated service that makes it easy to deploy and manage Apache Nifi on Mesosphere [DC/OS](https://mesosphere.com/product/), eliminating nearly all complexities, that are traditionally associated with managing a cluster of NiFi nodes.

Benefits
DC/OS Nifi  offers the following benefits of a semi-managed service:

1. Easy installation 
2. Multiple NiFi clusters 
3. Elastic scaling of Nodes
4. Replication and graceful shutdown for high availability 
5. Nifi cluster and Node monitoring



DC/OS Nifi  provides the following features:

1. Single-command installation for rapid provisioning
2. Multiple clusters for multiple tenancy with DC/OS
3. High availability runtime configuration and software updates
3. Storage volumes for enhanced data durability, known as Mesos Dynamic Reservations and Persistent Volumes
5. Integration with syslog-compatible logging services for diagnostics and troubleshooting
6. Integration with statsd-compatible metrics services for capacity and performance monitoring



# DC/OS Nifi Service Documentation

## Table of Contents

- [Overview](docs/index.md)
- [Install and Customize](docs/install.md)
- [Security](docs/security.md)
- [Uninstall](docs/uninstall.md)
- [Quick Start](docs/quick-start.md)
- [Connecting Clients](docs/connecting-clients.md)
- [Managing](docs/managing.md)
- [Diagnostic Tools](docs/diagnostictools.md)
- [API Reference](docs/api-reference.md)
- [Troubleshooting](docs/troubleshooting.md)
- [Limitations](docs/limitations.md)
- [Supported Versions](docs/support.md)
- [Release Notes](docs/release-notes.md)
- [Upgrade](docs/upgrade.md)
