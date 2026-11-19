# Agent Compliance Monitor

**An applied AI engineering project focused on AI observability, evaluation and governance.**

This project explores the engineering challenges of monitoring AI-enabled systems in an enterprise Azure environment. It brings together cloud services, Python, large language models, telemetry, data persistence and a lightweight web interface.

The commercial product design and implementation details are intentionally not described here.

## Technology stack

| Area | Technologies and approaches |
| --- | --- |
| Application engineering | Python, modular services, typed/structured data handling |
| AI platform | Azure AI Foundry, Azure OpenAI, GPT-4.1 |
| Retrieval | Vector search, embeddings and retrieval-augmented generation (RAG) concepts |
| Observability | Azure Monitor / Log Analytics, application and agent telemetry |
| Data | SQL, SQLite for prototype persistence, JSON |
| Interface | Streamlit |
| Cloud identity | Microsoft Entra ID, Azure RBAC and identity-based access patterns |
| Quality | Python `unittest`, regression testing, controlled test scenarios |
| Tooling | VS Code, Git, GitHub, Azure CLI, PowerShell |

## Engineering highlights

- Developed a Python-based Azure AI integration with structured LLM outputs and independent application-side validation.
- Connected real Azure telemetry to a working end-to-end assessment and persistence flow.
- Implemented retrieval against Azure-hosted vector infrastructure.
- Built a Streamlit interface for exploring saved results.
- Developed automated tests and repeatable regression scenarios across the application components.
- Worked through practical concerns around identity, observability, error handling, reproducibility and traceability.

## Key technical themes

**LLM engineering.** Integrating cloud-hosted language models with conventional software components, validation and predictable application behaviour.

**Cloud observability.** Working with operational telemetry and designing for useful diagnostics, data quality and traceability.

**Retrieval and data engineering.** Preparing reference information for semantic retrieval and integrating retrieved context into application workflows.

**Engineering discipline.** Modular Python, version control, repeatable tests, environment management and incremental delivery.

## Project status

**Active prototype / engineering development.** The core Azure-backed integration has been demonstrated with real telemetry. Further work covers operational resilience, test coverage, deployment automation and production-readiness considerations. This README does not represent the prototype as a certified compliance solution or a production service.

## Scope of this public overview

This page is intended to demonstrate hands-on engineering experience. It deliberately excludes proprietary assessment methods, application workflows, rule definitions, prompt assets, internal architecture, operational configurations, credentials, customer information and commercial plans.

Any future public code examples will be selected and reviewed separately from the commercial implementation.

## Author

**Brian White** — Data & AI engineering, architecture and technology leadership.

- [GitHub](https://github.com/ironbrian)
- [LinkedIn](https://www.linkedin.com/in/brianawhiteuk/)

## Intellectual property

Copyright © 2026 Brian White. All rights reserved. This document does not grant a licence to proprietary code, designs or other intellectual property. Any third-party materials remain subject to their respective terms.
