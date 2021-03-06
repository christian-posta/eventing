# Samples

This directory contains sample services which demonstrate `Feed`
functionality.

## Prerequisites

1. [Setup your development environment](../DEVELOPMENT.md#getting-started)
2. [Start Eventing](../DEVELOPMENT.md#starting-eventing-controller)

## Tools

- [Kail](https://github.com/boz/kail) - Kubernetes tail. Streams logs from all
  containers of all matched pods. Match pods by service, replicaset,
  deployment, and others. Adjusts to a changing cluster - pods are added and
  removed from logging as they fall in or out of the selection.


## Samples

* [Github Pull Request Handler](./github) - A simple handler for Github Pull Requests
* [GCP PubSub Receiver Handler](./gcp_pubsub_function) - A simple handler for processing GCP PubSub events
* [K8S events Handler](./k8s_events_function) - A simple handler for processing k8s events in the cluster
* [K8S events Handler using Flow](./flow) - Example using Flow object that wires k8s events through the bus
