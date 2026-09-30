---
layout: post
title: "Data Fabric & AI: watsonx.data, Governance, and the Unified Data Layer"
date: 2022-02-28 09:00:00 +0100
categories: [data-streaming]
repo: https://github.com/bmarolleau/retailOne
excerpt: "IBM watsonx.data as the open lakehouse for unified federated queries across IBM i Db2 and cloud data stores — with the RetailOne reference architecture."
---

`retailOne` is a reference architecture for a fictional retailer: IBM i Db2 as the operational backbone, watsonx.data (Presto/Trino + Iceberg) as the federated query layer, Watson Knowledge Catalog for governance. A single SQL query joins IBM i orders with cloud analytics data — no ETL, no data copy.

The governance piece matters for AI: ungoverned data produces ungoverned models. Lineage, data classification, PII tagging, business glossary — Watson Knowledge Catalog enforces these before any model training touches the data.

The IBM i Db2 connector for Presto makes decades of operational data accessible to analytics without moving it. For customers who've been told they need to "lift and shift" their IBM i data to a warehouse, this is the alternative.
