---
layout: post
title: "API-Enabling IBM i with IWS and TAI Security"
date: 2022-04-12 09:00:00 +0100
categories: [ibm-i]
repo: https://github.com/bmarolleau/iws-tai-security
excerpt: "Expose IBM i RPG service programs as REST APIs using IWS — no code change — and secure them with OAuth2/JWT via Trust Association Interceptors for enterprise API gateways."
---

IBM i's Integrated Web Services (IWS) wraps any service program procedure in an HTTP endpoint — no code change to the RPG program. The problem: IWS authenticates with IBM i user profiles. Enterprise API gateways expect OAuth2 tokens. That gap blocked adoption.

The `iws-tai-security` project implements a Trust Association Interceptor (TAI) for WebSphere on IBM i: intercept the request, validate the JWT against an identity provider (Security Verify, Keycloak, Azure AD), map the token subject to an IBM i profile, let it through. Now IBM i APIs are API-gateway-compatible.

With this pattern, API Connect (or any gateway) can sit in front of IBM i, enforcing rate limiting, analytics, and OAuth flows — while the RPG program sees only a normal service call.
