---
layout: post
title: "IoT Meets IBM i: Real-Time Dashboards with VMS and Event Streaming"
date: 2023-05-16 09:00:00 +0100
categories: [iot]
thumbnail-img: /assets/img/cloud-network.jpg
repo: https://github.com/bmarolleau/vms-iot-dashboard
excerpt: "Connecting industrial IoT sensors to IBM i business systems via Kafka — a real production pattern for predictive maintenance and operational intelligence."
---

Industrial sensors on a plant floor generate vibration, temperature, and pressure data. Alone, it's noise. Joined with IBM i asset records, maintenance history, and production orders, it becomes predictive intelligence. This project builds that join.

The pipeline: sensors → MQTT → Node-RED → Kafka → stream processor → IBM i Db2 (via Debezium CDC for the business context side). The dashboard merges both streams in real time, surfacing alerts with full business context — which machine, which SLA, which production order is affected.

The ML step: train a failure-prediction model on historical sensor + IBM i maintenance data, deploy it as a Kafka Streams processor, write predicted maintenance work orders back to IBM i automatically. A complete closed loop.
