---
layout: post
title: "Node-RED & Watson IoT: Prototyping Connected Systems"
date: 2019-05-19 09:00:00 +0100
categories: [iot]
repo: https://github.com/bmarolleau/watson-iot-labs
excerpt: "Node-RED and Watson IoT Platform labs for university sessions — a practical introduction to event-driven IoT pipelines, and the origin of node-red-contrib-db2-for-i."
---

The `watson-iot-labs` were created for IBM Cloud & Watson Days at French universities. Sensor → MQTT → Node-RED flow → Watson API → dashboard. The goal: non-developers leave understanding what an IoT pipeline actually does, not just what it is in theory.

Out of these sessions came `node-red-contrib-db2-for-i` — a Node-RED node I wrote and published that connects flows directly to IBM i Db2. Thousands of downloads. It filled a gap that had no clean solution before.

The patterns here evolved: Watson IoT Platform → IBM Event Streams (Kafka), Node-RED dashboards → Grafana, Cloudant → watsonx.data. The concepts are identical. The infrastructure is now production-grade.
