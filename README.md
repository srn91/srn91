# Sathwik Rao Nadipelli

**AI/Data Systems Engineer | M.S., Data Science, Rutgers | RAG, ML Platforms, Streaming Data, MLOps**

I build AI, ML, and data systems with runnable code, documented tradeoffs, evaluation outputs, and deployment paths. Most of my work is around data pipelines for ML, retrieval systems, model lifecycle infrastructure, monitoring, and applied decision systems.

## Projects

| Project | System | Notes |
|---|---|---|
| [rag-ops-platform](https://github.com/srn91/rag-ops-platform)<br>[Live demo](https://rag-ops-platform.onrender.com) | RAG service with hybrid retrieval, reranking, source citations, FastAPI endpoints, and evaluation reports. | `retrieval_hit_rate@3=1.0`, citation hit rate `1.0`, MRR `1.0`, 11 passing tests. |
| [streaming-feature-platform](https://github.com/srn91/streaming-feature-platform)<br>[Live demo](https://streaming-feature-platform-demo.onrender.com) | Streaming feature platform using Redpanda/Kafka, Redis, DuckDB, FastAPI, quality checks, and Prometheus metrics. | Online/offline checks, freshness metrics, GCP Pub/Sub and BigQuery dry-run assets. |
| [ml-training-serving-platform](https://github.com/srn91/ml-training-serving-platform)<br>[Live demo](https://ml-training-serving-platform.onrender.com) | ML lifecycle service with scikit-learn/PyTorch artifacts, versioned manifests, FastAPI serving, and monitoring output. | Offline-online parity delta `<=1e-6`, rollback metadata, multi-version serving. |
| [model-monitoring-drift-lab](https://github.com/srn91/model-monitoring-drift-lab)<br>[API docs](https://model-monitoring-drift-lab.onrender.com/docs) | Drift and delayed-outcome monitoring service with incident reports and read-only APIs. | 2,000 reference rows, 5 rolling windows, PSI `2.0372`, KS `0.6170`. |
| [ranking-serving-engine](https://github.com/srn91/ranking-serving-engine)<br>[API docs](https://ranking-serving-engine.onrender.com/docs) | Ranking service with query-item features, model comparison, NDCG/MAP evaluation, and top-k APIs. | 12 query groups, NDCG@5/MAP@5 model selection, feature-level score traces. |
| [recommendation-studio](https://github.com/srn91/recommendation-studio) | Recommendation workflow with candidate scoring, cold-start fallback, diversity-aware reranking, and serving APIs. | 18 users, diversity@5 `0.4 -> 0.6`, novelty@5 `0.19 -> 0.5004`. |

## Data and Platform Work

- [lakehouse-reliability-lab](https://github.com/srn91/lakehouse-reliability-lab): bronze/silver/gold reliability workflow with deduplication, late-arrival handling, revenue reconciliation, and freshness checks.
- [cdc-data-contract-hub](https://github.com/srn91/cdc-data-contract-hub): CDC schema compatibility checks with downstream lineage, expiring exceptions, and break alerts.
- [job-ops](https://github.com/srn91/job-ops): job-search operations platform with job ingest, dedupe, fit scoring, application artifacts, CRM timeline, analytics, FastAPI, and Next.js.
- [job-tracker](https://github.com/srn91/job-tracker): Dockerized full-stack tracker with React, Node/Express, PostgreSQL, and a persistence API.

## Applied ML Work

- [uplift-decision-engine](https://github.com/srn91/uplift-decision-engine): treatment-effect targeting across 2,400 customers with uplift-at-top-quartile `0.5957`, Qini-style evaluation, and net-value recommendations.
- [experimentation-lab](https://github.com/srn91/experimentation-lab): A/B testing workflow over 4,000 users with CUPED lift, variance reduction `0.514`, observed power `1.0`, MDE, and ship/no-ship output.
- [document-intelligence-copilot](https://github.com/srn91/document-intelligence-copilot): invoice extraction workflow with 3 line items, confidence metadata, validation issues, OCR-readiness checks, and correction feedback.
- [agent-workflow-studio](https://github.com/srn91/agent-workflow-studio): supervisor-worker workflow with bounded tools, retry handling, human approval gates, JSONL traces, SQLite run records, and FastAPI endpoints.

## Research Systems

- [multi-agent-trading-system](https://github.com/srn91/multi-agent-trading-system): multi-agent trading research over 2012-2026 and 100 stocks with +19.8% CAGR, 0.95 Sharpe, -28% max drawdown, and 722 trades under stated assumptions.
- [gtaa-multi-agent-system](https://github.com/srn91/gtaa-multi-agent-system): tactical allocation workflow with 8 agents, 2020-2025 backtest, 20.9% CAGR, 0.92 Sharpe, -21.3% max drawdown, and 10,000 Monte Carlo paths.
- [systematic_trading_research_engine](https://github.com/srn91/systematic_trading_research_engine): leakage-aware quant research engine with purged walk-forward validation, sealed holdout gates, baselines, and deploy/no-deploy decisions.

## Stack

**Data:** Python, SQL, Spark, Kafka/Redpanda, Airflow, dbt, Snowflake, Databricks, BigQuery, DuckDB, Redis, CDC, data contracts<br>
**AI/ML:** scikit-learn, PyTorch, TensorFlow, LightGBM, ranking, recommendations, uplift modeling, A/B testing, causal inference<br>
**Retrieval:** RAG, LangChain, LangGraph patterns, embeddings, vector retrieval, hybrid BM25+dense retrieval, reranking, citations, evaluation<br>
**Platform:** FastAPI, Docker, Kubernetes, MLflow-style artifact tracking, model serving, CI/CD, Prometheus metrics, drift detection
