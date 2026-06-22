---
author: blckaddr
pubDatetime: 2026-06-18T09:00:00.000Z
title: "Building an Agent, One Concept at a Time"
slug: building-an-agent-one-concept-at-a-time
featured: true
draft: false
tags:
  - ai
  - agents
  - spring
description: "A learning book on how a Spring AI agent that calls tools actually works — built one concept at a time, with the failures left in."
---

Most "AI agent" tutorials hand you a finished demo and the illusion that it
always works. I wanted the opposite: to build one agent slowly — a phase at a
time — and *watch* what the loop really does, including the parts that fail.

The result is a book, **Building an Agent, One Concept at a Time**. The agent's
job is deliberately mundane (convert currencies, add numbers, by calling tools
in separate little servers) so the *machinery* stays in plain view: how a model
decides to call a tool, how results flow back, how multi-step plans hold
together — or fall apart.

## What's inside

Each chapter is one rung of a learning ladder — reasoning concepts first, then
delivery concepts — and every chapter follows the same beat:

> **What we wanted to learn → What we built → What actually happened → What it taught us.**

The "what actually happened" sections quote real output, wrong answers included,
because the wrong answers taught the most.

## Read it

📖 **[Read the book →](https://blckaddr.github.io/spring-ai-agent-by-example/)**

The code lives on [GitHub](https://github.com/blckaddr/spring-ai-agent-by-example).
