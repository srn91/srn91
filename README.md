# Sathwik Rao Nadipelli

I build data and ML systems that are designed to be runnable, inspectable, and defensible in production. This portfolio focuses on the engineering seams that often get skipped in demos: online/offline consistency, evaluation, observability, schema safety, deployment verification, and release-time quality gates.

## Start Here

These are the six projects I would want a recruiter or hiring manager to open first:

1. [streaming-feature-platform](https://github.com/srn91/streaming-feature-platform)  
   Live demo: [streaming-feature-platform-demo.onrender.com](https://streaming-feature-platform-demo.onrender.com)  
   Focus: streaming feature computation, online/offline reconciliation, schema safety, and low-latency serving.
2. [rag-ops-platform](https://github.com/srn91/rag-ops-platform)  
   Live demo: [rag-ops-platform.onrender.com](https://rag-ops-platform.onrender.com)  
   Focus: grounded retrieval, reranking, citations, and evaluation for auditable RAG systems.
3. [ml-training-serving-platform](https://github.com/srn91/ml-training-serving-platform)  
   Live demo: [ml-training-serving-platform.onrender.com](https://ml-training-serving-platform.onrender.com)  
   Focus: reproducible training, artifact registration, batch scoring, and offline-to-online parity validation.
4. [lakehouse-reliability-lab](https://github.com/srn91/lakehouse-reliability-lab)  
   Live demo: [lakehouse-reliability-lab.onrender.com](https://lakehouse-reliability-lab.onrender.com)  
   Focus: medallion pipeline reliability, deduplication, reconciliation, and schema drift handling.
5. [ranking-serving-engine](https://github.com/srn91/ranking-serving-engine)  
   Live demo: [ranking-serving-engine.onrender.com](https://ranking-serving-engine.onrender.com)  
   Focus: feature-backed ranking, offline evaluation, freshness-aware serving, and top-k APIs.
6. [model-monitoring-drift-lab](https://github.com/srn91/model-monitoring-drift-lab)  
   Live demo: [model-monitoring-drift-lab.onrender.com](https://model-monitoring-drift-lab.onrender.com)  
   Focus: PSI / KS / KL drift detection, delayed outcomes, and incident-style monitoring summaries.

## Portfolio Map

### Data Platforms

- [streaming-feature-platform](https://github.com/srn91/streaming-feature-platform): streaming feature infrastructure with Redpanda, DuckDB, Redis, and FastAPI.
- [lakehouse-reliability-lab](https://github.com/srn91/lakehouse-reliability-lab): medallion-style lakehouse validation and reconciliation workflow.
- [cdc-data-contract-hub](https://github.com/srn91/cdc-data-contract-hub): CDC schema governance and lineage-aware contract compatibility checks.

### ML Systems

- [ml-training-serving-platform](https://github.com/srn91/ml-training-serving-platform): train-to-serve lifecycle with artifact registration and parity validation.
- [model-monitoring-drift-lab](https://github.com/srn91/model-monitoring-drift-lab): model and data drift monitoring with incident reporting.
- [uplift-decision-engine](https://github.com/srn91/uplift-decision-engine): treatment-effect targeting and intervention recommendation workflow.

### Retrieval, Ranking, and Recommendations

- [rag-ops-platform](https://github.com/srn91/rag-ops-platform): inspectable hybrid retrieval and RAG evaluation.
- [ranking-serving-engine](https://github.com/srn91/ranking-serving-engine): query-item ranking with artifact-backed serving.
- [recommendation-studio](https://github.com/srn91/recommendation-studio): candidate scoring, cold-start fallback, and diversity-aware reranking.

### AI Workflow Applications

- [agent-workflow-studio](https://github.com/srn91/agent-workflow-studio): supervisor-worker orchestration with retries, approval gates, and traces.
- [document-intelligence-copilot](https://github.com/srn91/document-intelligence-copilot): document extraction, validation, and reviewer-ready exception packets.
- [experimentation-lab](https://github.com/srn91/experimentation-lab): CUPED-based experimentation, sequential readouts, and power-planning analysis.

## What To Look For

- Every repo has a public README with problem framing, architecture, tradeoffs, run steps, validation notes, and next steps.
- Every repo has a live hosted deployment or demo URL attached at the GitHub repository level.
- Every repo was verified locally and in CI, and the live services were smoke-tested after deployment.

## Best Entry Paths

- If you care about data infrastructure, start with [streaming-feature-platform](https://github.com/srn91/streaming-feature-platform).
- If you care about LLM infrastructure, start with [rag-ops-platform](https://github.com/srn91/rag-ops-platform).
- If you care about ML lifecycle, start with [ml-training-serving-platform](https://github.com/srn91/ml-training-serving-platform).
- If you care about experimentation and ranking systems, open [experimentation-lab](https://github.com/srn91/experimentation-lab), [recommendation-studio](https://github.com/srn91/recommendation-studio), and [ranking-serving-engine](https://github.com/srn91/ranking-serving-engine).
