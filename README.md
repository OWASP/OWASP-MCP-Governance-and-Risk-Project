
# MCP Governance & Risk Framework

A practical governance framework for organizations adopting the [Model Context Protocol (MCP)](https://modelcontextprotocol.io/), the open standard that lets AI agents connect to external tools, data sources, and systems.

MCP adoption is accelerating across engineering teams. Agents can read wikis, open pull requests, post to Slack, and trigger production workflows often at machine speed and without the user seeing every intermediate step. This repository provides a structured way to answer the central governance question:

> **Should this MCP server be allowed in our environment, and under what controls?**

---

## What's in this repository


| Document                                                                       | Description                                                                                                      |
| ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| [mcp-governance-risk-framework-v1.0.md](mcp-governance-risk-framework-v1.0.md) | **Main guide (v1.0)**: inventory, classification, risk scoring, governance principles, and rollout guidance      |
| [framework-mapping.md](framework-mapping.md)                                   | **Framework mapping**: control mappings to OWASP MCP Top 10, OWASP LLM Top 10, NIST AI RMF, ISO 42001, and SOC 2 |
| [reference.md](reference.md)                                                   | **Reference links**: curated external URLs for MCP security, threat modeling, vendor review, and standards       |


---

## Key governance rules


| Rule                                     | Implication                                                |
| ---------------------------------------- | ---------------------------------------------------------- |
| **No owner = No approval**               | Every MCP server requires a named owner before approval    |
| **No logging = No production use**       | Servers without audit trails cannot operate in production  |
| **No scope definition = No access**      | Data and action scope must be documented before connection |
| **No review = No enterprise deployment** | Periodic review is mandatory by risk tier                  |


### Six principles at a glance


| #   | Principle                                | One-line rule                                                         |
| --- | ---------------------------------------- | --------------------------------------------------------------------- |
| 1   | No MCP Without Ownership                 | No owner = no approval                                                |
| 2   | Classify Before You Connect              | Know the risk tier before connecting                                  |
| 3   | Least Privilege for Tools                | Minimum permissions per tool, not per server name                     |
| 4   | Human Approval Must Be Meaningful        | HITL must show what, where, who, and impact                           |
| 5   | Auditability Requires Production Logging | No logging = no production use                                        |
| 6   | The Approved Path Must Beat Shadow IT    | Pre-approved patterns and SLAs must be faster than unofficial install |


---

## Quick start (30 days)

1. **Inventory**: Capture every known MCP server, including suspected shadow deployments
2. **Classify**: Assign Tier 0–4 based on the highest-risk tool each server exposes
3. **Score**: Apply [hard gates](mcp-governance-risk-framework-v1.0.md#hard-gates-non-negotiable) first, then the [eight-factor risk model](mcp-governance-risk-framework-v1.0.md#the-eight-risk-factors) for nuanced decisions
4. **Publish policy**: Adopt the four governance rules and tier-based control requirements
5. **Assign owners**: Name business and technical owners for every Tier 2+ server
6. **Report metrics**: Track inventory coverage, shadow MCP count, and overdue reviews monthly

---

## Classification tiers at a glance


| Tier  | Description                  | Example                             | Approval authority                     |
| ----- | ---------------------------- | ----------------------------------- | -------------------------------------- |
| **0** | Public data, read-only       | Public docs, weather API            | Lightweight review                     |
| **1** | Internal, non-sensitive read | Internal wiki search                | Security + business owner              |
| **2** | Sensitive read               | CRM, HR knowledge base              | Security + data owner                  |
| **3** | Write-capable                | GitHub PR merge, CI/CD trigger      | Security architecture + platform owner |
| **4** | Privileged / critical        | Cloud admin, IAM, production deploy | CISO or risk board                     |


---

## External references and compliance mapping

- **[framework-mapping.md](framework-mapping.md)** maps guide controls to OWASP MCP Top 10, OWASP LLM Top 10, NIST AI RMF, ISO/IEC 42001, and SOC 2 — use this for audits, gap assessments, and program integration.
- **[reference.md](reference.md)** consolidates external links for MCP specification and authorization requirements, OWASP and NIST/ISO source documents, and MCP security community resources and CVE tracking.

---

## Contributing

This framework is intended to evolve with the MCP ecosystem. It is maintained as part of the [MCP Security Project](https://github.com/mcp-security-project). If you use it in your organization or have feedback on classification, scoring, or policy language, open an issue or submit a pull request.

---


[Main guide](mcp-governance-risk-framework-v1.0.md) · [Framework mapping](framework-mapping.md) · [Reference links](reference.md)
