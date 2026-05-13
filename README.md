# Sathwik Rao Nadipelli

**AI/Data Systems Engineer | M.S. Data Science, Rutgers | RAG, Streaming Data, MLOps, ML Platforms**

I build production-style AI and data systems that are runnable, inspectable, and defensible: RAG pipelines, streaming feature platforms, model training/serving workflows, data contract checks, model monitoring, and agentic workflow automation.

My portfolio is organized around the proof hiring teams usually look for in senior AI/ML, data engineering, and platform roles: architecture, reproducible setup, API contracts, evaluation metrics, observability, reliability checks, and deployed demos.

## Flagship Proof

| Project | What it proves | Evidence to inspect |
|---|---|---|
| [rag-ops-platform](https://github.com/srn91/rag-ops-platform) | Grounded RAG, hybrid retrieval, citation-backed answers, retrieval evaluation | `retrieval_hit_rate_at_3=1.0`, `citation_hit_rate=1.0`, `MRR=1.0`, `11` passing tests, `/query`, `/evaluation` |
| [streaming-feature-platform](https://github.com/srn91/streaming-feature-platform) | Real-time feature delivery, online/offline consistency, ML-ready data exports | Redpanda, Redis, DuckDB, FastAPI, `/quality/summary`, `/metrics`, GCP Pub/Sub + BigQuery dry-run bundle |
| [ml-training-serving-platform](https://github.com/srn91/ml-training-serving-platform) | Training-to-serving lifecycle, artifact registry, multi-version inference, parity checks | scikit-learn + PyTorch artifacts, rollback metadata, `/predict`, `/models`, offline-online delta `<=1e-6` |
| [model-monitoring-drift-lab](https://github.com/srn91/model-monitoring-drift-lab) | Post-deployment model reliability and incident-style monitoring | `2,000` reference rows, `5` rolling windows, PSI `2.0372`, KS `0.6170`, log loss `0.2889 -> 0.5905` |
| [cdc-data-contract-hub](https://github.com/srn91/cdc-data-contract-hub) | Schema evolution, CDC compatibility, lineage-aware blast-radius reporting | breaking-change classification, exception expiry, impacted consumers, `/demo/report` |
| [agent-workflow-studio](https://github.com/srn91/agent-workflow-studio) | Agentic workflow orchestration with bounded tools, retries, approval gates, and traces | JSONL traces, SQLite run records, timing telemetry, manual approval endpoint, FastAPI demo |

## Portfolio Map

### GenAI / LLM Systems

- [rag-ops-platform](https://github.com/srn91/rag-ops-platform): auditable RAG pipeline with hybrid retrieval, reranking, citations, latency diagnostics, and golden-set evaluation.
- [agent-workflow-studio](https://github.com/srn91/agent-workflow-studio): supervisor-worker workflow with bounded local tools, retry handling, human approval, JSONL traces, and persisted run records.
- [document-intelligence-copilot](https://github.com/srn91/document-intelligence-copilot): document extraction, validation, human-review packets, and correction feedback loops for unstructured content.

### Data Engineering / AI Data Platforms

- [streaming-feature-platform](https://github.com/srn91/streaming-feature-platform): Kafka/Redpanda feature platform with DuckDB, Redis, FastAPI, freshness checks, reconciliation, Prometheus metrics, and GCP dry-run assets.
- [cdc-data-contract-hub](https://github.com/srn91/cdc-data-contract-hub): CDC schema governance with compatibility classification, lineage, temporary waivers, and break alerts.
- [lakehouse-reliability-lab](https://github.com/srn91/lakehouse-reliability-lab): lakehouse reliability workflow for deduplication, late-arrival handling, reconciliation, anomaly detection, and SLA-style reporting.

### MLOps / ML Platform

- [ml-training-serving-platform](https://github.com/srn91/ml-training-serving-platform): train/register/serve/validate lifecycle with scikit-learn, PyTorch, artifact manifests, rollback metadata, and FastAPI inference.
- [model-monitoring-drift-lab](https://github.com/srn91/model-monitoring-drift-lab): PSI, KS, KL divergence, delayed-outcome quality, prediction shift, incident reports, and read-only monitoring APIs.
- [ranking-serving-engine](https://github.com/srn91/ranking-serving-engine): feature-backed ranking service with offline evaluation, freshness-aware serving, and top-k APIs.

### Applied ML / Data Science

- [uplift-decision-engine](https://github.com/srn91/uplift-decision-engine): treatment-effect modeling and intervention recommendation workflow.
- [experimentation-lab](https://github.com/srn91/experimentation-lab): CUPED-based experimentation, sequential readouts, power planning, and decision reports.
- [recommendation-studio](https://github.com/srn91/recommendation-studio): candidate scoring, cold-start fallback, and diversity-aware reranking.
- [multi-agent-trading-system](https://github.com/srn91/multi-agent-trading-system): multi-agent research engine with regime/risk signals, walk-forward validation, and auditable decision logs.

## Core Stack

- **AI / GenAI:** RAG, LangChain-style orchestration, embeddings, hybrid retrieval, reranking, citations, guardrails, evaluation, agent workflows
- **Data Engineering:** Python, SQL, Spark, Kafka/Redpanda, DuckDB, Redis, BigQuery, GCP Pub/Sub, CDC, schema evolution, data contracts
- **MLOps:** MLflow-style artifacts, FastAPI, Docker, model registry patterns, drift detection, CI/CD, Prometheus metrics, rollback metadata
- **ML / Data Science:** scikit-learn, PyTorch, LightGBM, uplift modeling, experimentation, ranking, recommendation systems, statistical evaluation

## What To Check In Each Repo

- Architecture diagram and tradeoffs
- Reproducible run steps
- API or CLI examples
- Evaluation or validation metrics
- Monitoring, reliability, or failure-mode handling
- Tests, CI, or verification commands
- Deployed demo or generated artifacts

## Contact

- LinkedIn: [linkedin.com/in/sathwikraonadipelli](https://linkedin.com/in/sathwikraonadipelli)
- GitHub: [github.com/srn91](https://github.com/srn91)
