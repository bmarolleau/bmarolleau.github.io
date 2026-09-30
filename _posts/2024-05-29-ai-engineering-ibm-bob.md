---
layout: post
title: "AI Engineering with IBM Bob: The Agentic Revolution for Enterprise"
date: 2024-05-29 09:00:00 +0100
categories: [ai-bob]
repo: https://github.com/bmarolleau/ibmi-assistant
excerpt: "How IBM Bob transforms enterprise software engineering — and the ibmi-assistant prototype that explored LLM-powered assistance for IBM i before Bob existed."
---

The `ibmi-assistant` project was my exploration of what an LLM-powered assistant tuned for IBM i would look like: RAG over IBM i documentation, system information sources as context, API-exposed for IDE plugins. It's the prototype that preceded what Bob does at scale today.

The pattern it established — connect an LLM to platform-specific context, expose it as a tool — is exactly how Bob's skills and MCP servers work. Build a focused instruction document or a context server, and Bob becomes a specialist rather than a generalist.

For enterprise IBM i: the value isn't faster code completion. It's making 30-year-old RPG estates legible to developers who've never seen a green screen — in hours, not months.
