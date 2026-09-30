---
layout: post
title: "Cloud Design Patterns: Event-Driven, CDC, and Mesh Architectures"
date: 2025-08-29 09:00:00 +0100
categories: [data-streaming]
repo: https://github.com/bmarolleau/cdp-mesh-tutorial
also-repos:
  - https://github.com/bmarolleau/debezium-ibmi-demo
  - https://github.com/bmarolleau/EventDriven_CDC_Lab
excerpt: "Real cloud design patterns from a Polytech Montpellier course — Kafka event streaming, Debezium CDC from IBM i, and data mesh concepts applied to enterprise modernization."
---

These patterns power the modernization projects I run with customers. The `cdp-mesh-tutorial` is the Polytech Montpellier course material — hands-on Kafka and CDC exercises on OpenShift, from zero to a running event-driven pipeline in a few hours.

The most impactful pattern for IBM i: **Debezium CDC**. Capture every Db2 for i journal record change and stream it to Kafka — zero polling, no ETL, real-time data propagation without touching the application. The `debezium-ibmi-demo` repo shows this end-to-end: IBM i journal → Debezium → Kafka → downstream consumers.

Data mesh is the next step: treating IBM i operational data as a domain-owned, catalogued data product, accessible to analytics and AI workloads via federated query — without copying it into a warehouse.
