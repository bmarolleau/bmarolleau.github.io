---
layout: post
title: "IBM i Application Modernization with Bob"
date: 2026-02-04 09:00:00 +0100
categories: [ai-bob]
repo: https://github.com/bmarolleau/IBM-i-Application-Modernization-with-Bob
excerpt: "The full IBM i modernization journey with Bob — code comprehension, RPGUnit test generation, DDS-to-DDL migration, REST API spec, and Ansible IaC. All from a single lab."
---

The IBM i AppMod lab covers five stages: Bob reads and explains legacy RPG → generates RPGUnit tests → suggests DDS-to-DDL SQL migrations → produces an OpenAPI spec from service programs → scaffolds Ansible playbooks for system automation. Each step has a working exercise.

The key insight: **time to understand** is the real bottleneck. Once a team can read what the code does, every other modernization step accelerates dramatically. Bob collapses that from weeks to hours.

The companion `flight400-demo` runs this end-to-end on a fictional airline scenario — live, in Bob, with no pre-baked outputs. It's the demo I use in every customer engagement.
