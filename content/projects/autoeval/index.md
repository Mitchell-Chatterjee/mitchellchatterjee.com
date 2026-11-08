---
title: "AutoEval: Automated AI Evaluation"
summary: "TD Bank's standard framework for evaluating agentic conversations, with reusable evaluators and a streamlined path from development to production."
weight: 1
tags: ["Agents", "Evaluation", "MLOps"]
---

## Context

On the Agentic AI team at Layer 6 AI / TD Bank, we build long-running agents for complex tasks in a highly regulated environment. AutoEval is the bank-wide standard evaluation framework I developed to assess agentic conversations, with reuse across generative AI and other AI applications.

## What I built

- **Reusable evaluation.** A framework that lets research scientists build custom evaluators for different AI use cases.
- **A simpler path to production.** A standardized pipeline that lets scientists and MLOps work independently with minimal handoff.
- **Reliable execution.** Support for concurrent evaluation, persistence, retries, and failure handling, with extensions for monitoring and storage integrations.

Standardizing the development-to-production pipeline reduces the estimated time to deploy a custom evaluator from roughly six months to weeks.
