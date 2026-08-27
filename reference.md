# MCP Governance & Risk — Reference Links

This document consolidates external references for the **MCP Governance & Risk Model** guide, including every URL cited in the guide chapters, related resources from the broader MCP security and AI governance ecosystem, and additional links useful for threat modeling, vendor review, compliance mapping, and control validation.

---

## URLs Cited in This Guide

These links appear in the [MCP Governance & Risk Framework v1.0](mcp-governance-risk-framework-v1.0.md) and related documents.


| Resource | URL |
|----------|-----|
| MCP Specification | https://spec.modelcontextprotocol.io/ |
| MCP Authorization Specification (2025-11-25) | https://spec.modelcontextprotocol.io/specification/2025-11-25/basic/authorization/ |
| MCP Security Best Practices | https://modelcontextprotocol.io/specification/draft/basic/security_best_practices |
| OWASP MCP Top 10 | https://owasp.org/www-project-mcp-top-10/ |
| OWASP Top 10 for LLM Applications | https://owasp.org/www-project-top-10-for-large-language-model-applications/ |
| NIST AI Risk Management Framework (AI RMF 1.0) | https://www.nist.gov/itl/ai-risk-management-framework |
| ISO/IEC 42001:2023 | https://www.iso.org/standard/81230.html |
| Awesome MCP Security List | https://github.com/awesome-mcp-security/awesome-mcp-security |
| Awesome MCP CVE | https://github.com/awesome-mcp-security/awesome-mcp-cve |
| NIST SP 800-61 Rev. 2 (Incident Response) | https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final |


---

## Internal Guide Documents


| Document                         | Path                                                                                                   | Purpose                                        |
| -------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------- |
| MCP Governance & Risk Framework  | [mcp-governance-risk-framework-v1.0.md](mcp-governance-risk-framework-v1.0.md)                         | Main v1.0 guide: six chapters plus appendix    |
| README / guide index             | [README.md](README.md)                                                                                 | Navigation and audience routing                |
| Framework Mapping Appendix       | [framework-mapping.md](framework-mapping.md)                                                           | OWASP, NIST AI RMF, ISO 42001, SOC 2 alignment |
| Reference Links                  | [reference.md](reference.md)                                                                           | Curated external URLs and quick topic index    |

**Planned for future releases (not in this repository):** intake forms, risk register templates, vendor questionnaires, and approval decision forms. Use the in-guide [Evidence Pack](mcp-governance-risk-framework-v1.0.md#evidence-pack-tier-2-approvals) and practitioner checklists until those artifacts ship.


---

## MCP Official Protocol & Security


| Resource                                              | URL                                                                                                                                                                              |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Model Context Protocol (main site)                    | [https://modelcontextprotocol.io/](https://modelcontextprotocol.io/)                                                                                                             |
| MCP documentation index (`llms.txt`)                  | [https://modelcontextprotocol.io/llms.txt](https://modelcontextprotocol.io/llms.txt)                                                                                             |
| MCP Specification (spec site)                         | [https://spec.modelcontextprotocol.io/](https://spec.modelcontextprotocol.io/)                                                                                                   |
| MCP Specification (2025-11-25)                        | [https://spec.modelcontextprotocol.io/specification/2025-11-25/](https://spec.modelcontextprotocol.io/specification/2025-11-25/)                                                 |
| MCP Authorization (2025-11-25)                        | [https://modelcontextprotocol.io/specification/2025-11-25/basic/authorization](https://modelcontextprotocol.io/specification/2025-11-25/basic/authorization)                     |
| MCP Authorization (spec site, 2025-11-25)             | [https://spec.modelcontextprotocol.io/specification/2025-11-25/basic/authorization/](https://spec.modelcontextprotocol.io/specification/2025-11-25/basic/authorization/)         |
| MCP Specification (2025-06-18)                        | [https://modelcontextprotocol.io/specification/2025-06-18](https://modelcontextprotocol.io/specification/2025-06-18)                                                             |
| MCP Key Changes (2025-06-18)                          | [https://modelcontextprotocol.io/specification/2025-06-18/changelog](https://modelcontextprotocol.io/specification/2025-06-18/changelog)                                         |
| MCP Authorization (2025-06-18)                        | [https://modelcontextprotocol.io/specification/2025-06-18/basic/authorization](https://modelcontextprotocol.io/specification/2025-06-18/basic/authorization)                     |
| MCP Transports (2025-06-18)                           | [https://modelcontextprotocol.io/specification/2025-06-18/basic/transports](https://modelcontextprotocol.io/specification/2025-06-18/basic/transports)                           |
| MCP Tools (2025-06-18)                                | [https://modelcontextprotocol.io/specification/2025-06-18/server/tools](https://modelcontextprotocol.io/specification/2025-06-18/server/tools)                                   |
| MCP Sampling (2025-06-18)                             | [https://modelcontextprotocol.io/specification/2025-06-18/client/sampling](https://modelcontextprotocol.io/specification/2025-06-18/client/sampling)                             |
| MCP Elicitation (2025-06-18)                          | [https://modelcontextprotocol.io/specification/2025-06-18/client/elicitation](https://modelcontextprotocol.io/specification/2025-06-18/client/elicitation)                       |
| MCP Roots (2025-06-18)                                | [https://modelcontextprotocol.io/specification/2025-06-18/client/roots](https://modelcontextprotocol.io/specification/2025-06-18/client/roots)                                   |
| MCP Specification (2025-03-26, historical)            | [https://spec.modelcontextprotocol.io/specification/2025-03-26/](https://spec.modelcontextprotocol.io/specification/2025-03-26/)                                                 |
| MCP Authorization (2025-03-26, historical)            | [https://modelcontextprotocol.io/specification/2025-03-26/basic/authorization](https://modelcontextprotocol.io/specification/2025-03-26/basic/authorization)                     |
| MCP Authorization (spec site, 2025-03-26, historical) | [https://spec.modelcontextprotocol.io/specification/2025-03-26/basic/authorization/](https://spec.modelcontextprotocol.io/specification/2025-03-26/basic/authorization/)         |
| MCP Security Best Practices (draft spec path)         | [https://modelcontextprotocol.io/specification/draft/basic/security_best_practices](https://modelcontextprotocol.io/specification/draft/basic/security_best_practices)           |
| MCP Security Best Practices (2025-11-25)              | [https://modelcontextprotocol.io/specification/2025-11-25/basic/security_best_practices](https://modelcontextprotocol.io/specification/2025-11-25/basic/security_best_practices) |
| MCP Security Best Practices (docs tutorial)           | [https://modelcontextprotocol.io/docs/tutorials/security/security_best_practices](https://modelcontextprotocol.io/docs/tutorials/security/security_best_practices)               |
| MCP Logging utility (2025-11-25)                      | [https://modelcontextprotocol.io/specification/2025-11-25/server/utilities/logging](https://modelcontextprotocol.io/specification/2025-11-25/server/utilities/logging)           |
| Understanding Authorization in MCP                    | [https://modelcontextprotocol.io/docs/tutorials/security/authorization](https://modelcontextprotocol.io/docs/tutorials/security/authorization)                                   |
| MCP Client Best Practices                             | [https://modelcontextprotocol.io/docs/develop/clients/client-best-practices](https://modelcontextprotocol.io/docs/develop/clients/client-best-practices)                         |
| Connect to remote MCP servers                         | [https://modelcontextprotocol.io/docs/develop/connect-remote-servers](https://modelcontextprotocol.io/docs/develop/connect-remote-servers)                                       |
| MCP Inspector                                         | [https://modelcontextprotocol.io/docs/tools/inspector](https://modelcontextprotocol.io/docs/tools/inspector)                                                                     |
| MCP SDKs                                              | [https://modelcontextprotocol.io/docs/sdk](https://modelcontextprotocol.io/docs/sdk)                                                                                             |
| Anthropic: Introducing MCP                            | [https://www.anthropic.com/news/model-context-protocol](https://www.anthropic.com/news/model-context-protocol)                                                                   |
| MCP GitHub organization                               | [https://github.com/modelcontextprotocol](https://github.com/modelcontextprotocol)                                                                                               |
| MCP specification repository                          | [https://github.com/modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol)                                                     |
| Official MCP Registry                                 | [https://registry.modelcontextprotocol.io/](https://registry.modelcontextprotocol.io/)                                                                                           |
| MCP Registry: about                                   | [https://modelcontextprotocol.io/registry/about](https://modelcontextprotocol.io/registry/about)                                                                                 |
| MCP Registry: charter                                 | [https://modelcontextprotocol.io/community/registry/charter](https://modelcontextprotocol.io/community/registry/charter)                                                         |
| MCP Registry: GitHub                                  | [https://github.com/modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry)                                                                             |
| MCP Registry launch announcement                      | [https://blog.modelcontextprotocol.io/posts/2025-09-08-mcp-registry-preview/](https://blog.modelcontextprotocol.io/posts/2025-09-08-mcp-registry-preview/)                       |


### MCP Governance, Community, and Security Process


| Resource                                     | URL                                                                                                                                                                                      |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MCP Governance and Stewardship               | [https://modelcontextprotocol.io/community/governance](https://modelcontextprotocol.io/community/governance)                                                                             |
| MCP Security Policy                          | [https://modelcontextprotocol.io/community/security](https://modelcontextprotocol.io/community/security)                                                                                 |
| MCP Security Interest Group Charter          | [https://modelcontextprotocol.io/community/interest-groups/security](https://modelcontextprotocol.io/community/interest-groups/security)                                                 |
| MCP Authorization Interest Group Charter     | [https://modelcontextprotocol.io/community/interest-groups/auth](https://modelcontextprotocol.io/community/interest-groups/auth)                                                         |
| MCP Enterprise-Managed Authorization Charter | [https://modelcontextprotocol.io/community/interest-groups/enterprise-managed-authorization](https://modelcontextprotocol.io/community/interest-groups/enterprise-managed-authorization) |
| MCP Working and Interest Groups              | [https://modelcontextprotocol.io/community/working-interest-groups](https://modelcontextprotocol.io/community/working-interest-groups)                                                   |
| MCP Feature Lifecycle and Deprecation Policy | [https://modelcontextprotocol.io/community/feature-lifecycle](https://modelcontextprotocol.io/community/feature-lifecycle)                                                               |
| MCP Roadmap                                  | [https://modelcontextprotocol.io/development/roadmap](https://modelcontextprotocol.io/development/roadmap)                                                                               |
| MCP SEPs index                               | [https://modelcontextprotocol.io/seps/index](https://modelcontextprotocol.io/seps/index)                                                                                                 |


### Security-Relevant MCP SEPs


| Resource                                                                        | URL                                                                                                                                                                                          |
| ------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SEP-932: Model Context Protocol Governance                                      | [https://modelcontextprotocol.io/seps/932-model-context-protocol-governance](https://modelcontextprotocol.io/seps/932-model-context-protocol-governance)                                     |
| SEP-1024: MCP Client Security Requirements for Local Server Installation        | [https://modelcontextprotocol.io/seps/1024-mcp-client-security-requirements-for-local-server-](https://modelcontextprotocol.io/seps/1024-mcp-client-security-requirements-for-local-server-) |
| SEP-414: OpenTelemetry Trace Context Propagation Conventions                    | [https://modelcontextprotocol.io/seps/414-request-meta](https://modelcontextprotocol.io/seps/414-request-meta)                                                                               |
| SEP-985: Align OAuth 2.0 Protected Resource Metadata with RFC 9728              | [https://modelcontextprotocol.io/seps/985-align-oauth-20-protected-resource-metadata-with-rf](https://modelcontextprotocol.io/seps/985-align-oauth-20-protected-resource-metadata-with-rf)   |
| SEP-990: Enterprise IdP Policy Controls During MCP OAuth Flows                  | [https://modelcontextprotocol.io/seps/990-enable-enterprise-idp-policy-controls-during-mcp-o](https://modelcontextprotocol.io/seps/990-enable-enterprise-idp-policy-controls-during-mcp-o)   |
| SEP-991: URL-Based Client Registration Using OAuth Client ID Metadata Documents | [https://modelcontextprotocol.io/seps/991-enable-url-based-client-registration-using-oauth-c](https://modelcontextprotocol.io/seps/991-enable-url-based-client-registration-using-oauth-c)   |
| SEP-1046: OAuth Client Credentials Flow in Authorization                        | [https://modelcontextprotocol.io/seps/1046-support-oauth-client-credentials-flow-in-authoriza](https://modelcontextprotocol.io/seps/1046-support-oauth-client-credentials-flow-in-authoriza) |
| SEP-2207: OIDC-Flavored Refresh Token Guidance                                  | [https://modelcontextprotocol.io/seps/2207-oidc-refresh-token-guidance](https://modelcontextprotocol.io/seps/2207-oidc-refresh-token-guidance)                                               |
| SEP-2243: HTTP Header Standardization for Streamable HTTP Transport             | [https://modelcontextprotocol.io/seps/2243-http-standardization](https://modelcontextprotocol.io/seps/2243-http-standardization)                                                             |
| SEP-2468: Recommend Issuer Claim for Auth                                       | [https://modelcontextprotocol.io/seps/2468-recommend-issuer-claim-for-auth](https://modelcontextprotocol.io/seps/2468-recommend-issuer-claim-for-auth)                                       |
| SEP-2577: Deprecate Roots, Sampling, and Logging                                | [https://modelcontextprotocol.io/seps/2577-deprecate-roots-sampling-and-logging](https://modelcontextprotocol.io/seps/2577-deprecate-roots-sampling-and-logging)                             |


### OAuth & Transport Standards (referenced by MCP auth spec)


| Resource                                                           | URL                                                                                                                              |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| OAuth 2.1 (IETF draft)                                             | [https://datatracker.ietf.org/doc/html/draft-ietf-oauth-v2-1-11](https://datatracker.ietf.org/doc/html/draft-ietf-oauth-v2-1-11) |
| OAuth 2.0 Security Best Current Practice (RFC 9700)                | [https://datatracker.ietf.org/doc/html/rfc9700](https://datatracker.ietf.org/doc/html/rfc9700)                                   |
| OAuth 2.0 Authorization Server Metadata (RFC 8414)                 | [https://datatracker.ietf.org/doc/html/rfc8414](https://datatracker.ietf.org/doc/html/rfc8414)                                   |
| OAuth 2.0 Dynamic Client Registration (RFC 7591)                   | [https://datatracker.ietf.org/doc/html/rfc7591](https://datatracker.ietf.org/doc/html/rfc7591)                                   |
| OAuth 2.0 Token Exchange (RFC 8693)                                | [https://datatracker.ietf.org/doc/html/rfc8693](https://datatracker.ietf.org/doc/html/rfc8693)                                   |
| IETF Internet-Draft: Secure MCP (message signing & tool integrity) | [https://datatracker.ietf.org/doc/draft-secure-mcp/](https://datatracker.ietf.org/doc/draft-secure-mcp/)                         |


---

## OWASP MCP Top 10


| Resource                             | URL                                                                                                  |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| OWASP MCP Top 10 (project page)      | [https://owasp.org/www-project-mcp-top-10/](https://owasp.org/www-project-mcp-top-10/)               |
| OWASP MCP Top 10 (GitHub repository) | [https://github.com/OWASP/www-project-mcp-top-10/](https://github.com/OWASP/www-project-mcp-top-10/) |


### Individual Risk Categories (2025 v0.1)


| ID    | Risk                                                              | URL                                                                                                                                                                                                                                          |
| ----- | ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MCP01 | Token Mismanagement & Secret Exposure                             | [https://owasp.org/www-project-mcp-top-10/2025/MCP01-2025-Token-Mismanagement-and-Secret-Exposure](https://owasp.org/www-project-mcp-top-10/2025/MCP01-2025-Token-Mismanagement-and-Secret-Exposure)                                         |
| MCP02 | Privilege Escalation via Scope Creep                              | [https://owasp.org/www-project-mcp-top-10/2025/MCP02-2025-%E2%80%93Privilege-Escalation-via-Scope-Creep](https://owasp.org/www-project-mcp-top-10/2025/MCP02-2025-%E2%80%93Privilege-Escalation-via-Scope-Creep)                             |
| MCP03 | Tool Poisoning                                                    | [https://owasp.org/www-project-mcp-top-10/2025/MCP03-2025-%E2%80%93Tool-Poisoning](https://owasp.org/www-project-mcp-top-10/2025/MCP03-2025-%E2%80%93Tool-Poisoning)                                                                         |
| MCP04 | Software Supply Chain Attacks & Dependency Tampering              | [https://owasp.org/www-project-mcp-top-10/2025/MCP04-2025-%E2%80%93Software-Supply-Chain-Attacks&Dependency-Tampering](https://owasp.org/www-project-mcp-top-10/2025/MCP04-2025-%E2%80%93Software-Supply-Chain-Attacks&Dependency-Tampering) |
| MCP05 | Command Injection & Execution                                     | [https://owasp.org/www-project-mcp-top-10/2025/MCP05-2025-%E2%80%93Command-Injection&Execution](https://owasp.org/www-project-mcp-top-10/2025/MCP05-2025-%E2%80%93Command-Injection&Execution)                                               |
| MCP06 | Intent Flow Subversion / Prompt Injection via Contextual Payloads | [https://owasp.org/www-project-mcp-top-10/2025/MCP06-2025-%E2%80%93Prompt-InjectionviaContextual-Payloads](https://owasp.org/www-project-mcp-top-10/2025/MCP06-2025-%E2%80%93Prompt-InjectionviaContextual-Payloads)                         |
| MCP07 | Insufficient Authentication & Authorization                       | [https://owasp.org/www-project-mcp-top-10/2025/MCP07-2025-%E2%80%93Insufficient-Authentication&Authorization](https://owasp.org/www-project-mcp-top-10/2025/MCP07-2025-%E2%80%93Insufficient-Authentication&Authorization)                   |
| MCP08 | Lack of Audit and Telemetry                                       | [https://owasp.org/www-project-mcp-top-10/2025/MCP08-2025-%E2%80%93Lack-of-Audit-and-Telemetry](https://owasp.org/www-project-mcp-top-10/2025/MCP08-2025-%E2%80%93Lack-of-Audit-and-Telemetry)                                               |
| MCP09 | Shadow MCP Servers                                                | [https://owasp.org/www-project-mcp-top-10/2025/MCP09-2025-%E2%80%93Shadow-MCP-Servers](https://owasp.org/www-project-mcp-top-10/2025/MCP09-2025-%E2%80%93Shadow-MCP-Servers)                                                                 |
| MCP10 | Context Injection & Over-Sharing                                  | [https://owasp.org/www-project-mcp-top-10/2025/MCP10-2025-%E2%80%93ContextInjection&OverSharing](https://owasp.org/www-project-mcp-top-10/2025/MCP10-2025-%E2%80%93ContextInjection&OverSharing)                                             |


---

## OWASP LLM, GenAI & Agentic Security


| Resource                                          | URL                                                                                                                                                                                                              |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OWASP Top 10 for LLM Applications (project page)  | [https://owasp.org/www-project-top-10-for-large-language-model-applications/](https://owasp.org/www-project-top-10-for-large-language-model-applications/)                                                       |
| OWASP Top 10 for LLM Applications (GitHub)        | [https://github.com/OWASP/Top10LLMForLLMApp](https://github.com/OWASP/Top10LLMForLLMApp)                                                                                                                         |
| OWASP GenAI Security Project                      | [https://genai.owasp.org/](https://genai.owasp.org/)                                                                                                                                                             |
| OWASP LLM Top 10 (latest)                         | [https://genai.owasp.org/llm-top-10/](https://genai.owasp.org/llm-top-10/)                                                                                                                                       |
| OWASP Top 10 for Agentic Applications (2026)      | [https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/)                                             |
| OWASP GenAI: Contribute                           | [https://genai.owasp.org/contribute/](https://genai.owasp.org/contribute/)                                                                                                                                       |
| OWASP GenAI: Meetings                             | [https://genai.owasp.org/meetings/](https://genai.owasp.org/meetings/)                                                                                                                                           |
| OWASP MCP Security Cheat Sheet                    | [https://cheatsheetseries.owasp.org/cheatsheets/MCP_Security_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/MCP_Security_Cheat_Sheet.html)                                                     |
| OWASP AI Security Verification Standard (AISVS)   | [https://owasp.org/www-project-ai-security-verification-standard/](https://owasp.org/www-project-ai-security-verification-standard/)                                                                             |
| OWASP AISVS: C10 MCP Security                     | [https://github.com/OWASP/AISVS/blob/main/1.0/en/0x10-C10-MCP-Security.md](https://github.com/OWASP/AISVS/blob/main/1.0/en/0x10-C10-MCP-Security.md)                                                             |
| OWASP SSRF Prevention Cheat Sheet                 | [https://cheatsheetseries.owasp.org/cheatsheets/Server_Side_Request_Forgery_Prevention_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Server_Side_Request_Forgery_Prevention_Cheat_Sheet.html) |
| OWASP AI Agent Security Cheat Sheet               | [https://cheatsheetseries.owasp.org/cheatsheets/AI_Agent_Security_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/AI_Agent_Security_Cheat_Sheet.html)                                           |
| OWASP LLM Prompt Injection Prevention Cheat Sheet | [https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/LLM_Prompt_Injection_Prevention_Cheat_Sheet.html)               |
| OWASP RAG Security Cheat Sheet                    | [https://cheatsheetseries.owasp.org/cheatsheets/RAG_Security_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/RAG_Security_Cheat_Sheet.html)                                                     |
| OWASP Logging Cheat Sheet                         | [https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Logging_Cheat_Sheet.html)                                                               |
| OWASP Secrets Management Cheat Sheet              | [https://cheatsheetseries.owasp.org/cheatsheets/Secrets_Management_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Secrets_Management_Cheat_Sheet.html)                                         |
| OWASP Software Supply Chain Security Cheat Sheet  | [https://cheatsheetseries.owasp.org/cheatsheets/Software_Supply_Chain_Security_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Software_Supply_Chain_Security_Cheat_Sheet.html)                 |


---

## AI Governance & Risk Frameworks


| Resource                                              | URL                                                                                                                                                                                                  | Relevance                                                                                      |
| ----------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| NIST AI Risk Management Framework (AI RMF 1.0)        | [https://www.nist.gov/itl/ai-risk-management-framework](https://www.nist.gov/itl/ai-risk-management-framework)                                                                                       | Govern, Map, Measure, Manage: [Framework Mapping Appendix](framework-mapping.md)               |
| NIST AI RMF Playbook                                  | [https://airc.nist.gov/airmf-resources/playbook/](https://airc.nist.gov/airmf-resources/playbook/)                                                                                                   | Implementation guidance                                                                        |
| NIST AI RMF Playbook (overview page)                  | [https://www.nist.gov/itl/ai-risk-management-framework/nist-ai-rmf-1-0](https://www.nist.gov/itl/ai-risk-management-framework/nist-ai-rmf-1-0)                                                       | NIST overview and download links                                                               |
| NIST AI RMF Crosswalk Documents                       | [https://airc.nist.gov/airmf-resources/crosswalks/](https://airc.nist.gov/airmf-resources/crosswalks/)                                                                                               | Compliance mappings                                                                            |
| NIST Cybersecurity Framework 2.0                      | [https://www.nist.gov/cyberframework](https://www.nist.gov/cyberframework)                                                                                                                           | Mapped in COMPEL MCP baseline                                                                  |
| NIST SP 800-61 Rev. 3: Incident Response              | [https://csrc.nist.gov/pubs/sp/800/61/r3/final](https://csrc.nist.gov/pubs/sp/800/61/r3/final)                                                                                                       | Current primary IR reference                                                                   |
| NIST SP 800-61 Rev. 3 DOI                             | [https://doi.org/10.6028/NIST.SP.800-61r3](https://doi.org/10.6028/NIST.SP.800-61r3)                                                                                                                 | Stable DOI for citation                                                                        |
| NIST SP 800-61 Rev. 2: Incident Response (historical) | [https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final](https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final)                                                                   | Historical IR reference; see [Detection and Incident Response](mcp-governance-risk-framework-v1.0.md#detection-and-incident-response) in the v1.0 appendix |
| NIST AI RMF: Generative AI Profile                    | [https://www.nist.gov/itl/ai-risk-management-framework/generative-artificial-intelligence-profile](https://www.nist.gov/itl/ai-risk-management-framework/generative-artificial-intelligence-profile) | GenAI-specific RMF guidance                                                                    |
| NIST SP 800-207: Zero Trust Architecture              | [https://csrc.nist.gov/pubs/sp/800/207/final](https://csrc.nist.gov/pubs/sp/800/207/final)                                                                                                           | OWASP AISVS MCP controls                                                                       |
| ISO/IEC 42001:2023: AI management systems             | [https://www.iso.org/standard/81230.html](https://www.iso.org/standard/81230.html)                                                                                                                   | Formal AI governance programs                                                                  |
| EU AI Act (official text)                             | [https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689)                                                         | Regulated AI system obligations                                                                |


---

## Standards, Baselines & Certification

Testable control frameworks useful for tier alignment, vendor questionnaires, and audit evidence.


| Resource                                   | URL                                                                                                                                                                      | Notes                                              |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- |
| MCP Server Security Standard (MSSS)        | [https://github.com/mcp-security-standard/mcp-server-security-standard](https://github.com/mcp-security-standard/mcp-server-security-standard)                           | 24 controls, 4 levels (L1–L4), deployment profiles |
| COMPEL: MCP 12-Control Hardening Baseline  | [https://www.compelframework.org/articles/model-context-protocol-security-standards](https://www.compelframework.org/articles/model-context-protocol-security-standards) | Maps to NIST CSF 2.0 and ISO 42001                 |
| SlowMist MCP Security Checklist            | [https://github.com/slowmist/MCP-Security-Checklist](https://github.com/slowmist/MCP-Security-Checklist)                                                                 | Server, client, host, multi-MCP scenarios          |
| Appsecco: Pentesting MCP Servers Checklist | [https://github.com/appsecco/pentesting-mcp-servers-checklist](https://github.com/appsecco/pentesting-mcp-servers-checklist)                                             | Traffic, auth, tool behavior, injection            |
| SAF-MCP: Secure Agentic Framework          | [https://github.com/safe-agentic-framework/safe-mcp](https://github.com/safe-agentic-framework/safe-mcp)                                                                 | MITRE ATT&CK-style MCP TTP taxonomy                |
| MCPSEC: MCP Security Benchmark             | [https://github.com/paolovella/vellaveto/tree/main/mcpsec](https://github.com/paolovella/vellaveto/tree/main/mcpsec)                                                     | 10 properties, 105 attack test cases               |


---

## Cloud & Enterprise Governance Guides


| Resource                                       | URL                                                                                                                                                                                                                                                                | Focus                                    |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------- |
| AWS: MCP Strategies (introduction)             | [https://docs.aws.amazon.com/prescriptive-guidance/latest/mcp-strategies/introduction.html](https://docs.aws.amazon.com/prescriptive-guidance/latest/mcp-strategies/introduction.html)                                                                             | Tool design, hosting, governance pillars |
| AWS: MCP Governance Strategy                   | [https://docs.aws.amazon.com/prescriptive-guidance/latest/mcp-strategies/mcp-governance-strategy.html](https://docs.aws.amazon.com/prescriptive-guidance/latest/mcp-strategies/mcp-governance-strategy.html)                                                       | Auth, rate limits, metrics, distribution |
| AWS: MCP Hosting Strategy                      | [https://docs.aws.amazon.com/prescriptive-guidance/latest/mcp-strategies/mcp-hosting-strategy.html](https://docs.aws.amazon.com/prescriptive-guidance/latest/mcp-strategies/mcp-hosting-strategy.html)                                                             | Local vs remote, registries, gateways    |
| AWS: MCP Strategies (PDF)                      | [https://docs.aws.amazon.com/pdfs/prescriptive-guidance/latest/mcp-strategies/mcp-strategies.pdf](https://docs.aws.amazon.com/pdfs/prescriptive-guidance/latest/mcp-strategies/mcp-strategies.pdf)                                                                 | Full guide download                      |
| AWS: AgentCore OBO Token Exchange              | [https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/on-behalf-of-token-exchange.html](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/on-behalf-of-token-exchange.html)                                                                   | Confused-deputy mitigation pattern       |
| Microsoft: MCP Azure Security Guide            | [https://github.com/microsoft/mcp-azure-security-guide](https://github.com/microsoft/mcp-azure-security-guide)                                                                                                                                                     | OWASP MCP Top 10 on Azure                |
| Microsoft: MCP Azure Security Guide (site)     | [https://microsoft.github.io/mcp-azure-security-guide/](https://microsoft.github.io/mcp-azure-security-guide/)                                                                                                                                                     | Published controls and architectures     |
| Microsoft: Agent Governance Toolkit            | [https://github.com/microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit)                                                                                                                                                     | MCP OWASP compliance mapping             |
| Microsoft: MCP for Beginners (Security module) | [https://github.com/microsoft/mcp-for-beginners/tree/main/02-Security](https://github.com/microsoft/mcp-for-beginners/tree/main/02-Security)                                                                                                                       | Learning path with OWASP mapping         |
| Microsoft: State of MCP Security in 2026       | [https://techcommunity.microsoft.com/blog/microsoft-security-blog/the-state-of-mcp-security-in-2026/4531327](https://techcommunity.microsoft.com/blog/microsoft-security-blog/the-state-of-mcp-security-in-2026/4531327)                                           | Industry threat landscape summary        |
| Microsoft: APIM as MCP Auth Gateway            | [https://techcommunity.microsoft.com/blog/integrationsonazureblog/azure-api-management-your-auth-gateway-for-mcp-servers/4402690](https://techcommunity.microsoft.com/blog/integrationsonazureblog/azure-api-management-your-auth-gateway-for-mcp-servers/4402690) | Gateway enforcement pattern              |


---

## Platform Implementation References


| Resource                                      | URL                                                                                                                                                                | Focus                                     |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------- |
| OpenAI API: MCP and Connectors                | [https://developers.openai.com/api/docs/guides/tools-connectors-mcp](https://developers.openai.com/api/docs/guides/tools-connectors-mcp)                           | Hosted MCP and connectors                 |
| OpenAI Agents SDK: MCP                        | [https://openai.github.io/openai-agents-python/mcp/](https://openai.github.io/openai-agents-python/mcp/)                                                           | Transports, approvals, filtering, tracing |
| OpenAI Apps SDK examples                      | [https://developers.openai.com/apps-sdk/build/examples](https://developers.openai.com/apps-sdk/build/examples)                                                     | MCP Apps and interactive components       |
| Microsoft Semantic Kernel: MCP concept sample | [https://learn.microsoft.com/semantic-kernel/concepts/plugins/adding-mcp-plugins](https://learn.microsoft.com/semantic-kernel/concepts/plugins/adding-mcp-plugins) | MCP plugins on Semantic Kernel            |


---

## Research, Taxonomies & Threat Models

Academic and formal frameworks that inform classification, threat modeling, and vendor review.


| Resource                                                           | URL                                                                                                                                                              | Notes                                                    |
| ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| MCP Landscape, Security Threats & Future Research (Hou et al.)     | [https://arxiv.org/abs/2503.23278](https://arxiv.org/abs/2503.23278)                                                                                             | Lifecycle threat taxonomy; 16 scenarios                  |
| MCP Landscape: HTML version                                        | [https://arxiv.org/html/2503.23278v3](https://arxiv.org/html/2503.23278v3)                                                                                       | Same paper, web format                                   |
| MCP Landscape: data repository                                     | [https://github.com/security-pride/MCP_Landscape](https://github.com/security-pride/MCP_Landscape)                                                               | Case studies and implementation examples                 |
| SoK: Security and Safety in the MCP Ecosystem                      | [https://arxiv.org/html/2512.08290](https://arxiv.org/html/2512.08290)                                                                                           | Security vs safety taxonomy; context weaponization       |
| MCPShield: Formal Security Framework for MCP Agents                | [https://arxiv.org/abs/2604.05969](https://arxiv.org/abs/2604.05969)                                                                                             | 7 categories, 23 attack vectors, verification model      |
| Simplified and Secure MCP Gateways (enterprise integration)        | [https://arxiv.org/abs/2504.19997](https://arxiv.org/abs/2504.19997)                                                                                             | Gateway architecture for enterprise AI                   |
| Wiz: MCP Security Research Briefing                                | [https://www.wiz.io/blog/mcp-security-research-briefing](https://www.wiz.io/blog/mcp-security-research-briefing)                                                 | Remote server risk analysis                              |
| Invariant Labs: Tool Poisoning Attacks                             | [https://invariantlabs.ai/blog/mcp-security-notification-tool-poisoning-attacks](https://invariantlabs.ai/blog/mcp-security-notification-tool-poisoning-attacks) | Rug pulls and description injection                      |
| Breaking the Protocol: Security Analysis of MCP (arxiv)            | [https://arxiv.org/abs/2601.17549](https://arxiv.org/abs/2601.17549)                                                                                             | Protocol-level security analysis; MCPBench / MCPSec      |
| SMCP: Secure Model Context Protocol                                | [https://arxiv.org/abs/2602.01129](https://arxiv.org/abs/2602.01129)                                                                                             | Proposed secure MCP variant with identity, policy, audit |
| MCPShield: Security Cognition Layer for Adaptive Trust Calibration | [https://arxiv.org/abs/2602.14281](https://arxiv.org/abs/2602.14281)                                                                                             | Runtime trust and tool validation research               |
| Making REST APIs Agent-Ready: OpenAPI to MCP Servers               | [https://arxiv.org/abs/2507.16044](https://arxiv.org/abs/2507.16044)                                                                                             | API-to-MCP governance and generated server review        |
| Making OpenAPI Documentation Agent-Ready                           | [https://arxiv.org/abs/2605.14312](https://arxiv.org/abs/2605.14312)                                                                                             | API documentation quality and tool-readiness governance  |


---

## Security Testing, Audit & Discovery Tools

Tools that support governance evidence collection, third-party review, and continuous monitoring.


| Resource                                | URL                                                                                                                            | Use in governance                           |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------- |
| mcp-scan (Invariant Labs)               | [https://github.com/invariantlabs-ai/mcp-scan](https://github.com/invariantlabs-ai/mcp-scan)                                   | Tool poisoning / shadowing detection        |
| MCP Tool Poisoning Experiments          | [https://github.com/invariantlabs-ai/mcp-injection-experiments](https://github.com/invariantlabs-ai/mcp-injection-experiments) | Prompt injection via tool output research   |
| SecureMCP                               | [https://github.com/makalin/SecureMCP](https://github.com/makalin/SecureMCP)                                                   | Vulnerability and misconfiguration auditing |
| MCP Audit Extension (VS Code / Copilot) | [https://github.com/Agentity-com/mcp-audit-extension](https://github.com/Agentity-com/mcp-audit-extension)                     | Tool call logging for review evidence       |
| ToolHive (Stacklok)                     | [https://github.com/StacklokLabs/toolhive](https://github.com/StacklokLabs/toolhive)                                           | MCP server isolation and lifecycle          |
| MCP Defender                            | [https://github.com/MCP-Defender/MCP-Defender](https://github.com/MCP-Defender/MCP-Defender)                                   | MCP-specific defense tooling                |
| AI-Infra-Guard (Tencent)                | [https://github.com/Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard)                                         | AI infrastructure security scanning         |


---

## MCP Security Community Resources


| Resource                                             | URL                                                                                                                                                      |
| ---------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Awesome MCP Security List                            | [https://github.com/awesome-mcp-security/awesome-mcp-security](https://github.com/awesome-mcp-security/awesome-mcp-security)                             |
| Awesome MCP CVE                                      | [https://github.com/awesome-mcp-security/awesome-mcp-cve](https://github.com/awesome-mcp-security/awesome-mcp-cve)                                       |
| Awesome MCP Security (Puliczek, actively maintained) | [https://github.com/Puliczek/awesome-mcp-security](https://github.com/Puliczek/awesome-mcp-security)                                                     |
| Awesome MCP Security: contributing guide             | [https://github.com/Puliczek/awesome-mcp-security/blob/main/CONTRIBUTING.md](https://github.com/Puliczek/awesome-mcp-security/blob/main/CONTRIBUTING.md) |


---

## Industry Analysis & Practitioner Articles

Selected articles useful for executive briefings, threat modeling, and reviewer education. For exhaustive lists, see Awesome MCP Security.


| Resource                                           | URL                                                                                                                                                                                                                                                                              | Topic                            |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- |
| Trail of Bits: MCP servers attack before first use | [https://blog.trailofbits.com/2025/04/21/jumping-the-line-how-mcp-servers-can-attack-you-before-you-ever-use-them/](https://blog.trailofbits.com/2025/04/21/jumping-the-line-how-mcp-servers-can-attack-you-before-you-ever-use-them/)                                           | Supply chain / install-time risk |
| Trail of Bits: MCP conversation history theft      | [https://blog.trailofbits.com/2025/04/23/how-mcp-servers-can-steal-your-conversation-history](https://blog.trailofbits.com/2025/04/23/how-mcp-servers-can-steal-your-conversation-history)                                                                                       | Data exfiltration                |
| Trail of Bits: Insecure credential storage in MCP  | [https://blog.trailofbits.com/2025/04/30/insecure-credential-storage-plagues-mcp/](https://blog.trailofbits.com/2025/04/30/insecure-credential-storage-plagues-mcp/)                                                                                                             | MCP01 token mismanagement        |
| Trail of Bits: Security layer MCP needed           | [https://blog.trailofbits.com/2025/07/28/we-built-the-security-layer-mcp-always-needed/](https://blog.trailofbits.com/2025/07/28/we-built-the-security-layer-mcp-always-needed/)                                                                                                 | Gateway / policy enforcement     |
| Block Goose: Securing MCP                          | [https://block.github.io/goose/blog/2025/03/31/securing-mcp/](https://block.github.io/goose/blog/2025/03/31/securing-mcp/)                                                                                                                                                       | Enterprise MCP hardening         |
| Simon Willison: MCP prompt injection               | [https://simonwillison.net/2025/Apr/9/mcp-prompt-injection/](https://simonwillison.net/2025/Apr/9/mcp-prompt-injection/)                                                                                                                                                         | Cross-tool injection demo        |
| Auth0: MCP and Authorization intro                 | [https://auth0.com/blog/an-introduction-to-mcp-and-authorization/](https://auth0.com/blog/an-introduction-to-mcp-and-authorization/)                                                                                                                                             | OAuth patterns for MCP           |
| Aaron Parecki: OAuth for MCP                       | [https://aaronparecki.com/2025/04/03/15/oauth-for-model-context-protocol](https://aaronparecki.com/2025/04/03/15/oauth-for-model-context-protocol)                                                                                                                               | Authorization design             |
| Obot: MCP Security Best Practices (2026 guide)     | [https://obot.ai/resources/learning-center/mcp-security/](https://obot.ai/resources/learning-center/mcp-security/)                                                                                                                                                               | Defense-in-depth framework       |
| Cisco: MCP and Security                            | [https://community.cisco.com/t5/security-blogs/ai-model-context-protocol-mcp-and-security/ba-p/5274394](https://community.cisco.com/t5/security-blogs/ai-model-context-protocol-mcp-and-security/ba-p/5274394)                                                                   | Enterprise security perspective  |
| Windows: Securing MCP on Windows                   | [https://blogs.windows.com/windowsexperience/2025/05/19/securing-the-model-context-protocol-building-a-safer-agentic-future-on-windows/](https://blogs.windows.com/windowsexperience/2025/05/19/securing-the-model-context-protocol-building-a-safer-agentic-future-on-windows/) | Platform-level controls          |


---

## Related Ecosystem (Referenced in This Project)

The [README](README.md) describes this repository as part of the broader MCP security ecosystem:


| Resource                                     | Status                | URL / Notes                                                                                                                                                    |
| -------------------------------------------- | --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **MCP Governance & Risk Model** (this guide) | v1.0 published        | [Main guide](mcp-governance-risk-framework-v1.0.md) in this repository                                                                                         |
| **MCP Security Taxonomy**                    | URL TBD               | Shared risk language; see [MCP Landscape paper](#research-taxonomies--threat-models) and [SAF-MCP](#standards-baselines--certification) for interim taxonomies |
| **MCP Testing Guide**                        | URL TBD               | Validates whether controls work; see [MCPSEC](#standards-baselines--certification) and [Appsecco checklist](#standards-baselines--certification)               |
| **OWASP MCP Top 10**                         | Published (beta v0.1) | Defines *what* can go wrong — see [OWASP MCP Top 10](#owasp-mcp-top-10)                                                                                        |
| **Awesome MCP CVE / Awesome MCP Security**   | Published             | Threat models and vendor review — see [MCP Security Community Resources](#mcp-security-community-resources)                                                    |
| **MSSS**                                     | Published (v0.1)      | Certifiable control standard — see [MSSS](#standards-baselines--certification)                                                                                 |


---

## Quick Reference by Guide Topic


| Guide topic                       | Primary URLs                                                                                                                                                                                                                                                                                                                                            |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Approval & authorization          | [MCP Authorization Spec (2025-11-25)](https://spec.modelcontextprotocol.io/specification/2025-11-25/basic/authorization/), [MCP Security Best Practices](https://modelcontextprotocol.io/specification/2025-11-25/basic/security_best_practices), [OWASP MCP Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/MCP_Security_Cheat_Sheet.html) |
| Classification & risk scoring     | [OWASP MCP Top 10](https://owasp.org/www-project-mcp-top-10/), [MSSS levels](https://github.com/mcp-security-standard/mcp-server-security-standard), [Framework Mapping Appendix](framework-mapping.md)                                                                                                                                                 |
| Asset inventory & registry        | [Official MCP Registry](https://registry.modelcontextprotocol.io/), [MCP Registry about](https://modelcontextprotocol.io/registry/about)                                                                                                                                                                                                                |
| Third-party / supply chain review | [OWASP MCP04](https://owasp.org/www-project-mcp-top-10/2025/MCP04-2025-%E2%80%93Software-Supply-Chain-Attacks&Dependency-Tampering), [Awesome MCP CVE](https://github.com/awesome-mcp-security/awesome-mcp-cve), [Evidence Pack — SBOM](mcp-governance-risk-framework-v1.0.md#evidence-pack-tier-2-approvals)                                                                        |
| Shadow MCP & inventory            | [OWASP MCP09](https://owasp.org/www-project-mcp-top-10/2025/MCP09-2025-%E2%80%93Shadow-MCP-Servers), [Ch. 4 — Approved vs. Shadow MCP](mcp-governance-risk-framework-v1.0.md#approved-vs-shadow-mcp)                                                                                                                                                                        |
| Audit & monitoring                | [OWASP MCP08](https://owasp.org/www-project-mcp-top-10/2025/MCP08-2025-%E2%80%93Lack-of-Audit-and-Telemetry), [MCP Audit Extension](https://github.com/Agentity-com/mcp-audit-extension)                                                                                                                                                                |
| High-risk / HITL scenarios        | [OWASP MCP06](https://owasp.org/www-project-mcp-top-10/2025/MCP06-2025-%E2%80%93Prompt-InjectionviaContextual-Payloads), [OWASP LLM Top 10](https://genai.owasp.org/llm-top-10/)                                                                                                                                                                        |
| Incident response                 | [NIST SP 800-61 Rev. 3](https://csrc.nist.gov/pubs/sp/800/61/r3/final), [Detection and Incident Response](mcp-governance-risk-framework-v1.0.md#detection-and-incident-response)                                                                                                                                                                                               |
| Compliance mapping                | [Framework Mapping Appendix](framework-mapping.md), [COMPEL baseline](https://www.compelframework.org/articles/model-context-protocol-security-standards), [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework)                                                                                                                         |
| Enterprise rollout                | [AWS MCP Governance Strategy](https://docs.aws.amazon.com/prescriptive-guidance/latest/mcp-strategies/mcp-governance-strategy.html), [Microsoft MCP Azure Security Guide](https://microsoft.github.io/mcp-azure-security-guide/)                                                                                                                        |
| Reviewer prompts & evidence       | [Hard Gates](mcp-governance-risk-framework-v1.0.md#hard-gates-non-negotiable), [Evidence Pack](mcp-governance-risk-framework-v1.0.md#evidence-pack-tier-2-approvals), [Formal Control Catalog](mcp-governance-risk-framework-v1.0.md#formal-control-catalog)                                                                                                                                                                                                                                                                |


- **OWASP MCP Top 10:** Currently in beta (v0.1). Risk names and URLs may change at final release. Note: published OWASP MCP risk names differ slightly from some internal guide chapter mappings; reconcile during final release.
- **Current spec version:** This guide targets MCP Specification **2025-11-25** as the current authorization reference. Older versions (2025-03-26, 2025-06-18) remain listed for historical comparison.
- **Dual spec hosts:** MCP documentation appears on both `modelcontextprotocol.io` and `spec.modelcontextprotocol.io`. Verify which version your deployment targets.
- **Link rot:** Community awesome lists and blog posts change frequently. Prefer standards bodies, official MCP docs, and GitHub repos as canonical sources.
- **Contributions:** Add new URLs via pull request. Prefer governance, risk, compliance, and MCP-specific security sources over general AI news.

---

## Internet Review Additions — 2026-06-30

The recommendations from this review were incorporated into the sections above during v1.0 publication. This heading is retained for change traceability only.

---

[MCP Governance & Risk Framework v1.0](mcp-governance-risk-framework-v1.0.md) · [Guide Home](README.md) · [Framework Mapping](framework-mapping.md)
