# GraphDB Grafana Dashboard

Grafana dashboard for GraphDB

## Background

Ontotext provides a Grafana dashboard for Enterprise users, but doesn't provide a dashboard for the free version. This repository contains a dashboard that scrapes data from Prometheus, which is in turn scraping data from GraphDB's metrics endpoint (you need Prometheus for this).

## Dashboard

The dashboard exposes *most* of the metrics that GraphDB provides. This is limited to system level metrics such as space constraints, memory, and heap usage.

![Grafana Dashboard](./images/dashboard.png "Grafana Dashboard")
