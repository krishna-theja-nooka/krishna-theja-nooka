<h1 align="center">Krishna Theja Nooka</h1>
<p align="center"><strong>AI Engineering · Data Engineering · Applied Machine Learning</strong></p>
<p align="center">Building AI applications, data platforms, and reproducible experiments.<br/>From customer workflows to tested code, measurable results, and documented releases.</p>

<p align="center">
  <a href="#featured-projects">Explore projects</a> ·
  <a href="#tech-stack">Tech stack</a> ·
  <a href="#research-and-results">Research &amp; results</a>
</p>

---

## What I build

- **AI applications:** grounded retrieval, structured tool calling, and human approval for consequential actions.
- **Data platforms:** telemetry pipelines, validated analytics, and dashboards that explain the underlying data.
- **Applied ML:** recommendation models and controlled experiments with fixed baselines, ablations, and reported limitations.

My portfolio focuses on making systems inspectable: clear inputs, explicit permissions, useful traces, and evidence behind the output.

## Tech stack

**Languages & APIs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-334155?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**AI & machine learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-111827?style=flat-square&logo=ollama&logoColor=white)
![Meta Llama](https://img.shields.io/badge/Meta_Llama-0467DF?style=flat-square&logo=meta&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-14532D?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-475569?style=flat-square)

**Data & experimentation**

![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-0369A1?style=flat-square)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-2563EB?style=flat-square)

**Delivery & quality**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Featured projects

| Project | Engineering focus | Explore |
| :--- | :--- | :--- |
| **Fleet Intelligence Copilot** | Fleet operations workflow with policy citations, structured analytics, approval gates, and audit trails. | [Repository](https://github.com/krishna-theja-nooka/fde-enterprise-ai-capstone) |
| **Fleet Pulse** | Synthetic EV telemetry lakehouse, fleet analytics dashboard, and local Llama access to read-only analytics. | [Repository](https://github.com/krishna-theja-nooka/vehicle-telemetry-lakehouse) |
| **Gatehouse** | Reusable MCP tools with role permissions, human-approved ticket creation, rate limits, and audit records. | [Repository](https://github.com/krishna-theja-nooka/secure-mcp-enterprise-toolkit) |
| **FrameLab** | PyTorch recommendation research and a bounded LangGraph agent that tests training-data weighting changes. | [Repository](https://github.com/krishna-theja-nooka/video-recsys-research-agent) |
| **LLMOps Observability Platform** | Request tracing, latency and cost metrics, caching, rate limiting, and failure handling. | [Repository](https://github.com/krishna-theja-nooka/LLMOps-Observability-Platform) |
| **Production RAG** | Document ingestion, hybrid retrieval, grounded responses, and automated evaluation. | [Repository](https://github.com/krishna-theja-nooka/production-rag) |

## Research and results

**FrameLab — recommendation experiments with evidence**

The MovieLens 100K study compares a genre Transformer recommender, a no-content ablation, and popularity ranking. It reports Recall@10, normalized entropy, uncertainty, and measured training costs across paired seeds.

The agent rejected all three proposed data-weighting changes and retained the baseline. The report includes that outcome, alongside cold-start exclusions and the small evaluation population. Movie ratings serve as a proxy for video discovery; this is not a watch-time or production CTR benchmark.

[Read the research report](https://github.com/krishna-theja-nooka/video-recsys-research-agent/blob/main/reports/research-report.md) · [Inspect measured results](https://github.com/krishna-theja-nooka/video-recsys-research-agent/blob/main/reports/results.json)

<details>
<summary><strong>View the measured benchmark</strong></summary>

![FrameLab measured recommendation benchmark](https://raw.githubusercontent.com/krishna-theja-nooka/video-recsys-research-agent/main/reports/benchmark.png)

</details>

## How I approach engineering

| Principle | What it means in these projects |
| :--- | :--- |
| Start with the workflow | Define the user question, available data, and permitted action. |
| Make boundaries explicit | Validate inputs and keep consequential writes behind approval. |
| Measure the outcome | Compare against baselines and document unsuccessful experiments. |
| Make results reproducible | Include setup instructions, tests, experiment settings, and releases. |

<p align="center"><a href="https://github.com/krishna-theja-nooka?tab=repositories">Browse all repositories →</a></p>
