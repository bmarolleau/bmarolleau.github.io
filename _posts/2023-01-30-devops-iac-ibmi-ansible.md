---
layout: post
title: "Infrastructure as Code for IBM i: Ansible, DevOps, and the MOP Way"
date: 2023-01-30 09:00:00 +0100
categories: [devops-iac]
repo: https://github.com/bmarolleau/Ansible-for-i-MOP
also-repos:
  - https://github.com/bmarolleau/MerlinLab
  - https://github.com/bmarolleau/iws-tai-security
excerpt: "Ansible automation for IBM i system management — library backups, user profiles, PTFs, IFS operations — structured as Method of Procedure runbooks for safe, auditable system changes."
---

IBM i has excellent Ansible support via the `ibm.power_ibmi` collection. The `Ansible-for-i-MOP` repo contains the playbooks I use in **Method of Procedure** workshops — structured runbooks for upgrades, migrations, and routine operations that replace 2-hour manual procedures with 5-minute automated jobs, with a full audit trail.

Bob can generate these playbooks from natural language: *"Back up PRODLIB to IFS with today's date in the filename, then send a message to QSYSOPR if it fails."* That's a Ansible playbook in 30 seconds. For IBM i admins new to IaC, this is the fastest on-ramp.

Merlin (`MerlinLab`) closes the loop: Git for RPG source, CI/CD pipelines on commit, RPGUnit tests automated. The combination of Ansible (infra) + Merlin (app) gives IBM i shops a complete modern DevOps picture.
