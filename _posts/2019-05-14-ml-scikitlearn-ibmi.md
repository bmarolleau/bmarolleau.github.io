---
layout: post
title: "Machine Learning on IBM i with scikit-learn"
date: 2019-05-14 09:00:00 +0100
categories: [ibm-i]
repo: https://github.com/bmarolleau/firstdemo-scikitlearn-ibmi
excerpt: "A first experiment running scikit-learn ML models on Db2 for i data — proving in 2019 that IBM i is a first-class ML platform with no infrastructure changes needed."
---

The question in 2019: can you run a scikit-learn model trained on IBM i Db2 data and write predictions back — all in one loop? Yes. This notebook does exactly that: connect via `ibm_db`, extract training data, train a classifier, score it, insert results back to IBM i.

IBM i shops sit on decades of clean, high-integrity business data — the exact kind of data ML models need and rarely get. The challenge was never the data. It was the mental model that IBM i couldn't participate in the AI stack.

This project was the first step in what became: H2O Driverless AI on POWER9, Watson Studio + WML with IBM i, and eventually the `ibmi-assistant` LLM prototype. The thread runs all the way to IBM Bob.
