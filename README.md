# Awesome AI Governance [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, and resources for governing autonomous AI agents safely.

AI agents are getting powerful. This list focuses on **keeping them safe, compliant, and accountable**.

## Contents

- [Governance Frameworks](#governance-frameworks)
- [Safety & Guardrails](#safety--guardrails)
- [Identity & Trust](#identity--trust)
- [Compliance](#compliance)
- [Monitoring & Observability](#monitoring--observability)
- [Policy Engines](#policy-engines)
- [Multi-Agent Coordination](#multi-agent-coordination)
- [Industry Solutions](#industry-solutions)
- [Research & Papers](#research--papers)
- [Standards & Protocols](#standards--protocols)

---

## Governance Frameworks

*Complete frameworks for governing AI agent behavior.*

- **[Agent OS](https://github.com/imran-siddique/agent-os)** - Kernel architecture for AI agents with POSIX-inspired primitives. Deterministic policy enforcement. ![Stars](https://img.shields.io/github/stars/imran-siddique/agent-os?style=social)
- **[AgentMesh](https://github.com/imran-siddique/agent-mesh)** - Trust layer for multi-agent systems. Identity, trust scoring, delegation chains. ![Stars](https://img.shields.io/github/stars/imran-siddique/agent-mesh?style=social)
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - Add guardrails to LLM applications.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - NVIDIA's toolkit for adding guardrails to LLM apps.
- [LangChain](https://github.com/langchain-ai/langchain) - Framework with built-in safety callbacks.

## Safety & Guardrails

*Tools for preventing harmful agent actions.*

- [Rebuff](https://github.com/protectai/rebuff) - Prompt injection detection.
- [LLM Guard](https://github.com/protectai/llm-guard) - Security toolkit for LLM interactions.
- [Lakera Guard](https://www.lakera.ai/) - Real-time prompt injection protection.
- [Vigil](https://github.com/deadbits/vigil-llm) - LLM security scanner.

## Identity & Trust

*Agent identity, authentication, and trust verification.*

- **[AgentMesh IATP](https://github.com/imran-siddique/agent-mesh)** - Inter-Agent Trust Protocol implementation.
- [Decentralized Identifiers (DIDs)](https://www.w3.org/TR/did-core/) - W3C standard for decentralized identity.
- [Verifiable Credentials](https://www.w3.org/TR/vc-data-model/) - W3C standard for credentials.

## Compliance

*Tools for regulatory compliance (GDPR, HIPAA, SOC2, etc.)*

- **[Agent OS Compliance](https://github.com/imran-siddique/agent-os)** - Built-in SOC2, GDPR, HIPAA, PCI-DSS frameworks.
- [Drata](https://drata.com/) - SOC2 automation platform.
- [Vanta](https://www.vanta.com/) - Compliance automation.

## Monitoring & Observability

*Track what your agents are doing.*

- [LangSmith](https://www.langchain.com/langsmith) - LLM observability and debugging.
- [Weights & Biases](https://wandb.ai/) - ML experiment tracking.
- [Helicone](https://www.helicone.ai/) - LLM observability platform.
- [Langfuse](https://langfuse.com/) - Open-source LLM observability.

## Policy Engines

*Define and enforce policies on agent behavior.*

- **[Agent OS Policy Engine](https://github.com/imran-siddique/agent-os)** - YAML-based deterministic policy enforcement.
- [Open Policy Agent (OPA)](https://www.openpolicyagent.org/) - General-purpose policy engine.
- [Cedar](https://www.cedarpolicy.com/) - Amazon's policy language.

## Multi-Agent Coordination

*Governance for multi-agent systems.*

- **[AgentMesh](https://github.com/imran-siddique/agent-mesh)** - Trust layer for agent-to-agent communication.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's multi-agent framework.
- [CrewAI](https://github.com/joaomdmoura/crewAI) - Framework for orchestrating AI agents.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Build stateful multi-agent applications.

## Industry Solutions

*Governance solutions for specific industries.*

### Healthcare (HIPAA)
- [Agent OS Healthcare Template](https://github.com/imran-siddique/agent-os/tree/master/examples/healthcare) - HIPAA-compliant agent governance.

### Finance (SOC2)
- [Agent OS Finance Template](https://github.com/imran-siddique/agent-os/tree/master/examples/finance) - SOC2-compliant agent governance.

### Legal
- Coming soon

### DevOps
- Coming soon

## Research & Papers

*Academic research on AI agent safety and governance.*

- [Constitutional AI](https://arxiv.org/abs/2212.08073) - Anthropic's approach to harmless AI.
- [Sleeper Agents](https://arxiv.org/abs/2401.05566) - Research on deceptive AI behavior.
- [AI Alignment Forum](https://www.alignmentforum.org/) - Community for AI safety research.

## Standards & Protocols

*Emerging standards for AI agents.*

- [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - Anthropic's protocol for AI-tool interaction.
- [Agent-to-Agent Protocol (A2A)](https://github.com/google/A2A) - Google's inter-agent communication standard.
- [Inter-Agent Trust Protocol (IATP)](https://github.com/imran-siddique/agent-os) - Trust verification between agents.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Imran Siddique](https://github.com/imran-siddique) has waived all copyright and related or neighboring rights to this work.
