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


### Framework v1.0 scope

The v1.0 guide covers six core chapters plus a closing appendix. Treat the content in three layers: **policy** (Chapters 1 and 3), **controls** (Chapters 2–6 and the appendix control catalog), and **checklists** (chapter-end and appendix practitioner checklists). Compliance framework mappings live in the companion [framework-mapping.md](framework-mapping.md) document.

1. [Chapter 1: Executive Summary](mcp-governance-risk-framework-v1.0.md#chapter-1-executive-summary)
2. [Chapter 2: Why MCP Needs Governance](mcp-governance-risk-framework-v1.0.md#chapter-2-why-mcp-needs-governance)
3. [Chapter 3: MCP Governance Principles](mcp-governance-risk-framework-v1.0.md#chapter-3-mcp-governance-principles)
4. [Chapter 4: MCP Asset Inventory](mcp-governance-risk-framework-v1.0.md#chapter-4-mcp-asset-inventory)
5. [Chapter 5: MCP Server Classification Model](mcp-governance-risk-framework-v1.0.md#chapter-5-mcp-server-classification-model)
6. [Chapter 6: MCP Risk Scoring Model](mcp-governance-risk-framework-v1.0.md#chapter-6-mcp-risk-scoring-model)
7. [Appendix: Closing](mcp-governance-risk-framework-v1.0.md#appendix-closing) — control catalog, evidence pack, automated evidence collection and enforcement, client and host governance, cross-server trust test cases, authorization and network exposure test cases, detection and incident response, ten-question maturity check, glossary, and practitioner checklist

**Not in v1.0 (planned for future releases):** separate approval-workflow chapters, intake forms, risk register templates, and vendor questionnaires. Use the in-guide checklists and evidence pack until those artifacts ship.

---

## Start here by role

### CISO / Security leadership

Read [Chapter 1: Executive Summary](mcp-governance-risk-framework-v1.0.md#chapter-1-executive-summary) for the business case, four non-negotiable governance rules, and a [90-day rollout plan](mcp-governance-risk-framework-v1.0.md#practical-rollout-plan-90-days). Use the [Ten Questions](mcp-governance-risk-framework-v1.0.md#ten-questions-every-security-leader-should-be-able-to-answer) maturity check and [Appendix Practitioner Checklist](mcp-governance-risk-framework-v1.0.md#appendix-practitioner-checklist) before presenting to a risk committee.

### AppSec / Security architecture

Start with [Chapter 2](mcp-governance-risk-framework-v1.0.md#chapter-2-why-mcp-needs-governance) and [Chapter 3](mcp-governance-risk-framework-v1.0.md#chapter-3-mcp-governance-principles), then implement [Chapter 4: Asset Inventory](mcp-governance-risk-framework-v1.0.md#chapter-4-mcp-asset-inventory) and the [Classification Model (Chapter 5)](mcp-governance-risk-framework-v1.0.md#chapter-5-mcp-server-classification-model). Review [hard gates](mcp-governance-risk-framework-v1.0.md#hard-gates-non-negotiable), [tool chaining](mcp-governance-risk-framework-v1.0.md#tool-chaining-primary-risk), and [client and host governance](mcp-governance-risk-framework-v1.0.md#client-and-host-governance). Use [framework-mapping.md](framework-mapping.md) for OWASP and compliance control mappings; use [reference.md](reference.md) for MCP authorization spec, OWASP MCP Top 10, and other external sources.

### GRC / Compliance

Start with [framework-mapping.md](framework-mapping.md) for OWASP, NIST AI RMF, ISO 42001, and SOC 2 alignment. Use the [Formal Control Catalog](mcp-governance-risk-framework-v1.0.md#formal-control-catalog) and [Evidence Pack](mcp-governance-risk-framework-v1.0.md#evidence-pack-tier-2-approvals) in the appendix for audit evidence requirements by tier.

### Engineering / Platform teams

Review the [Tier 0–4 classification summary](mcp-governance-risk-framework-v1.0.md#step-2-classify-existing-servers) and [Recommended First Steps](mcp-governance-risk-framework-v1.0.md#recommended-first-steps). Understand that servers are classified by their **highest-risk tool**, not by server name alone. For faster adoption, use the [Pre-Approved MCP Catalog](mcp-governance-risk-framework-v1.0.md#pre-approved-mcp-catalog-paved-road). For local stdio servers, follow [Local MCP Hardening Requirements](mcp-governance-risk-framework-v1.0.md#local-mcp-hardening-requirements).

### Legal / Privacy / Procurement

Focus on data scope, third-party server review, and vendor trust factors in [Chapter 5](mcp-governance-risk-framework-v1.0.md#chapter-5-mcp-server-classification-model) and [Chapter 6: Risk Scoring](mcp-governance-risk-framework-v1.0.md#chapter-6-mcp-risk-scoring-model). Use [framework-mapping.md](framework-mapping.md) for audit and compliance alignment; external policy references are in [reference.md](reference.md).

---

## Key governance rules

These four rules are designed to be adopted as organizational policy. They are a subset of the [six governance principles](mcp-governance-risk-framework-v1.0.md#the-six-principles-at-a-glance) in Chapter 3.


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

## License

No `LICENSE` file is in this repository yet. Framework content is provided for organizational governance use; adapt policy language and forms to your environment and legal requirements.

---

[Main guide](mcp-governance-risk-framework-v1.0.md) · [Framework mapping](framework-mapping.md) · [Reference links](reference.md)