# Prasad Thiriveedi

I help organizations ship governed AI systems without the compliance debt that derails most AI initiatives. Federal or commercial.
Now builds, deploys, and governs AI agents end to end.

---

## What I'm Building

**[Meridian](https://github.com/tvprasad/meridian)** **[Live](https://products.vplsolutions.com)** — Control plane for governed RAG systems.
Deterministic retrieval · Explicit refusal semantics · Citation validation · Structured telemetry
   
Prevents the compliance failures and audit gaps that surface when RAG systems are deployed without governance.

Validated through real-world agent workflows, including failure diagnosis and controlled execution under production-like conditions.

> *AI systems fail from architectural ambiguity, not model weakness.*

---

**[AgentBond](https://github.com/tvprasad/AgentBond)** — Capability-based enforcement layer for agent delegation and tool access.

Issues scoped, non-redelegable tokens that bind:
- allowed tools  
- resource boundaries  
- time constraints (TTL)  

Every action is validated at execution time:
signature · scope · policy · audit

Prevents confused-deputy problems and limits blast radius even under orchestrator compromise.

Forms the hard trust boundary between agent intent and system execution.

---

**[aiPolaris](https://github.com/tvprasad/aipolaris)** (Feature Product) -
Regulated AI agent orchestration stalls on compliance gaps, audit failures, and capability boundaries that aren't enforced until production. aiPolaris prevents that — from the first commit.

> *AI systems fail from architectural ambiguity, not model weakness.*

**Next:** Enterprise Agentic RAG — LangGraph multi-agent system with
Graph API, ADLS Gen2, Azure AI Search, Entra ID auth, and
GCCH-scoped Terraform. Built to demonstrate the full delivery process
from intake to ATO-ready release records.

---

**[Dead Letter Oracle](https://github.com/tvprasad/deadletter)** — MCP-based agent system for diagnosing and safely replaying failed messages with governed execution and audit traceability.

---

## How I Work

Regulated AI initiatives stall because there is no delivery process —
not because the engineering is wrong. Every engagement runs the same
five-phase loop: intake, parallel execution, integration, delivery,
and continuous operations. The compliance evidence accumulates as the
system is built, not after.

| Role mode        | What it produces                                     |
|------------------|------------------------------------------------------|
| Business Analyst | Use cases, system boundary doc, acceptance criteria  |
| ML / AI Engineer | Agent graph, eval harness, prompt versioning         |
| Data Engineer    | Graph API connectors, ADLS pipeline, AI Search index |
| DevOps / MLOps   | Terraform (commercial + GCCH), CI/CD, release records|
| Security         | Threat model, NIST control mapping, SAST gates       |

---

## Stack

| Domain              | Technologies                                          |
|---------------------|-------------------------------------------------------|
| AI Orchestration    | LangGraph, Semantic Kernel, AutoGen, MCP tool servers |
| Retrieval           | Azure AI Search, pgvector, Chroma, RAG pipelines      |
| LLMs                | Azure OpenAI, Claude (Opus/Sonnet), Ollama (local)    |
| Data                | Graph API, ADLS Gen2, Azure Data Factory, Kafka, NATS |
| Backend             | Python, FastAPI, C#/.NET Core, TypeScript, gRPC       |
| Cloud & Infra       | Azure (GCCH-ready), AWS, Kubernetes, Terraform, AKS   |
| Compliance          | NIST 800-53, FedRAMP, ATO-ready, active secret clearance |

---

## Certifications

- **Anthropic:** Developing Applications with Claude API
- **Anthropic:** Mastering Claude AI — Prompting, APIs, RAG, and MCP
- **Anthropic:** Claude Code in Action · Introduction to MCP
- **AWS:** Generative AI & AI Agents with Amazon Bedrock
- **AWS:** Security Governance at Scale
- **Microsoft:** Azure Cognitive Services
- **Microsoft:** AI agent fundamentals with Azure AI Foundry 

 
---

## Philosophy

Control precedes generation. 
Observability precedes scale.
Governance precedes automation.

I design systems where failure modes are explicit, validated, and controlled before production.

---

## Representative Scenarios
- DLQ failure diagnosis and governed replay
- Schema mismatch detection with validation loops
- Controlled tool execution via MCP enforcement boundary
- Agent decision traceability with audit reconstruction

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/tvprasad)
