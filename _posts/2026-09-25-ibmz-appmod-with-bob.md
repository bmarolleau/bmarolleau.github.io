---
layout: post
title: "IBM Z Application Modernization with Bob"
date: 2026-09-25 09:00:00 +0100
categories: [ai-bob]
repo: https://github.com/bmarolleau/IBM-z-Application-Modernization-with-Bob-ppz
excerpt: "Bob reads COBOL, explains JCL, generates zUnit tests, and scaffolds z/OS Connect REST APIs — making mainframe code legible and evolvable without a big-bang rewrite."
---

95% of ATM swaps, 80% of credit card transactions — IBM Z runs them. The problem isn't that the code doesn't work. It's that the people who wrote it are retiring, and the codebases are essentially undocumented.

Bob on Z reads COBOL (including REDEFINES and nested PERFORM), parses JCL job streams, generates zUnit test stubs, and helps define z/OS Connect API wrappers to expose mainframe logic as REST endpoints. The lab in this repo walks through each step on a realistic workload.

The approach: **strangler fig**. Don't replace. Wrap. Add tests. Expose APIs. Migrate individual services based on business priority.
