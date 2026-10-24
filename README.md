# Analysis of Agentic AI Platforms for Autonomous Multi-Agent Ecosystems

> Research report — Master IoT, EURECOM (June 2026)  
> **Author**: Ikram Aziz · **Supervisor**: Prof. Jérôme Härri

## Abstract

Future autonomous transportation systems will not be built as a single monolithic program, but as ecosystems of many independent software *agents* — representing vehicles, traffic-management systems, charging stations, weather services and more — that must cooperate despite being built by different vendors, on different technologies, with different internal data models.

This report surveys the current state of the art of the platforms, protocols and standards proposed to make such cooperation possible.

## Research Question

> *How can autonomous agents communicate, cooperate, and reason together, and what is the current state of the art of the platforms, protocols and standards that aim to make this possible?*

## Technologies Surveyed

| Technology | Category |
|-----------|----------|
| **Agntcy** (CoffeeAGNTCY — Corto & Lungo) | Multi-agent platform |
| **OpenSlice** | Service orchestration |
| **W3C / A2A Agent Protocol** | Agent-to-agent communication |
| **MCP** (Model Context Protocol) | Agent-to-tool communication |
| **GITER** | Agent communication |
| **Ontology-based approaches** | Semantic reasoning |

## Analysis Framework

Each technology is described through a six-layer framework:

| Layer | Concern |
|-------|---------|
| Communication | Agents exchange messages reliably |
| Discovery | Agents find and address one another |
| Orchestration | Tasks and workflows coordinated across agents |
| Security | Identity, authentication, authorisation |
| Semantics | Shared meaning of exchanged data |
| Reasoning | Inference and decision-making over that data |

## Key Protocols Covered

- **A2A (Agent-to-Agent)**: Open standard using JSON-RPC 2.0 over HTTP(S) with SSE streaming. Donated to the Linux Foundation in 2025, reached v1.0 in early 2026.
- **MCP (Model Context Protocol)**: Connects an agent to external tools and data sources.
- **SLIM (Secure Low-Latency Interactive Messaging)**: Transport layer with MLS end-to-end encryption for agent protocols.
- **OASF (Open Agent Schema Framework)**: Extensible data model for agent description and discovery.

## Findings

- Communication and interoperability layers are well covered across surveyed technologies.
- The **semantic-reasoning layer** remains comparatively underdeveloped — a significant gap for true heterogeneous agent cooperation.
- No single platform covers all six layers; real deployments will need to compose multiple standards.

## Report

📄 [`Agentic-AI-Platforms-AZIZ.pdf`](./Agentic-AI-Platforms-AZIZ.pdf) — Full 17-page report with architecture diagrams and comparative analysis.

## Academic Context

- **Course / Programme**: Research project — Master's in Internet of Things (IoT)  
- **Institution**: EURECOM, Sophia Antipolis, France  
- **Date**: June 2026  
- **Supervisor**: Prof. Jérôme Härri
