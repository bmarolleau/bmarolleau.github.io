---
layout: post
title: "IoT & Big Data: From Sensor to Dashboard, via IBM i"
date: 2025-10-01 09:00:00 +0100
categories: [iot]
repo: https://github.com/bmarolleau/iot-bigdata-lab
also-repos:
  - https://github.com/bmarolleau/vms-iot-dashboard
  - https://github.com/bmarolleau/watson-iot-labs
excerpt: "End-to-end IoT pipelines for engineering and business school students — MQTT, Node-RED, time-series storage, and real-time dashboards connected to IBM i business data."
---

The `iot-bigdata-lab` was built for **IAE Montpellier** MBA students: sensor → MQTT broker → Node-RED pipeline → dashboard, with IBM i Db2 providing the business context. The goal was to give non-developers a real mental model of what their engineers actually build.

The pattern matters beyond the classroom. Industrial IoT data (vibration, temperature, pressure) is only useful when joined with business context — maintenance history, asset SLAs, production orders — and that context almost always lives in IBM i. The `vms-iot-dashboard` project shows this in a real manufacturing scenario.

Node-RED remains my go-to prototyping tool. The `node-red-contrib-db2-for-i` node I published connects any Node-RED flow directly to IBM i Db2 — thousands of downloads, still used in production.
