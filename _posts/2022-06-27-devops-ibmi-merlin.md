---
layout: post
title: "DevOps for IBM i: Git, CI/CD, and the Merlin Experience"
date: 2022-06-27 09:00:00 +0100
categories: [devops-iac]
repo: https://github.com/bmarolleau/MerlinLab
excerpt: "IBM Merlin brings Git, CI/CD pipelines, and automated RPGUnit testing to IBM i — the DevOps experience developers have been waiting for."
---

IBM Merlin (IBM Developer for IBM i DevOps Experience) gives IBM i developers a web-based VS Code IDE, Git integration, CI/CD pipelines that compile and test RPG on every commit, and RPGUnit as the automated test runner. The `MerlinLab` repo is the hands-on lab I use with teams making this shift.

The hard part isn't the tooling — it's the culture. The lab is designed to be incremental: start with main-branch-only Git, no PRs, just version history. Add automated builds next. Add RPGUnit. Add branches. Each step is a win visible to the team, not a disruption.

RPGUnit is the safety net that makes refactoring safe. Bob generates the test stubs; Merlin runs them on every push. Together: the first time IBM i developers can change code with confidence.
