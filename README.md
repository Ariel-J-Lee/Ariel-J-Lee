# Ariel Julius Lee

**Principal AI/ML Architect — retrieval evaluation, governed agent runtimes, and enterprise AI architecture.**

I build AI systems that are inspectable, citation-grounded, and audit-friendly. My public repositories translate that posture into reproducible reference implementations, with explicit boundaries between what each repo proves and what it does not.

## Public repositories

- **[production-rag-eval-harness](https://github.com/Ariel-J-Lee/production-rag-eval-harness)** — *Flagship proof.* Reproducible local harness comparing dense, sparse, hybrid, and graph-aware retrieval over a public corpus, with citation-grounded answers, a committed scored run, and reproducibility manifests. A planned regression gate is on the roadmap.
- **[agent-runtime-observability](https://github.com/Ariel-J-Lee/agent-runtime-observability)** — *Second proof lane.* Governed agent runtime reference: bounded retries, policy gates that deny unsafe tool calls, a documented failure-mode catalog with reproducible triggers, OpenTelemetry-shaped JSON traces, a five-tool layer with input-schema contracts, and a synthetic fixture corpus exercised through a deterministic stub LLM. Earlier in maturity than the retrieval harness; a committed runtime evidence run is planned next.
- **[aws-bedrock-iac-reference](https://github.com/Ariel-J-Lee/aws-bedrock-iac-reference)** — *Supporting architecture signal.* Bedrock-anchored AWS reference architecture as Terraform IaC, intended to surface security, cost, observability, and cloud-hygiene judgment. This repo is supporting signal, not the lead proof artifact.

## What this portfolio is meant to prove

- Retrieval evaluation discipline: scored local runs, citation contracts, reproducibility manifests.
- Governed agent runtime design: policy gates, failure modes, traceability, bounded tool use.
- Enterprise AI architecture judgment: AWS / Bedrock, security, cost, and operations posture.
- Honest evidence boundaries: these repos do not claim large-scale inference ownership, RLHF / DPO / LoRA training, MCP server delivery, production SaaS deployment, or customer deployment proof.

## Background

- Marine Corps Senior Intelligence Analyst (2015–2020).
- BS Cyber Engineering, Houston Christian University (2024).
- Currently a Principal AI/ML Architect.

## Connect

**LinkedIn**: [in/ariel-lee-4a6a231aa](https://linkedin.com/in/ariel-lee-4a6a231aa)
**Email**: ariel.j.lee@outlook.com
**Location**: Houston, Texas
