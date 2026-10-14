<p align="center">
  <img src="./assets/profile-header.svg" alt="Max Regan — dependable AI, from model to production" width="100%" />
</p>

# Hi, I'm Max.

**Software Engineer · AI Systems & ML Infrastructure**  
## Selected projects

### Agent execution, retrieval & inference

**[durableflow](https://github.com/maxgregaabig/durableflow) — What survives when an agent crashes?**  
A Python/SQLite lab for checkpoints, persistent approvals, model fallback, and failure injection. 

**[pgvector-rag](https://github.com/maxgregaabig/pgvector-rag) — Retrieval with inspectable evidence.**  
A FastAPI document-search service with PostgreSQL/pgvector, Redis caching, chunk-level citations, and an evaluation harness. Deterministic providers make the core behavior testable without API keys. 

**[model-serving-stack](https://github.com/maxgregaabig/model-serving-stack) — Serving is a systems problem.**  
A reference environment for vLLM, Triton, and Ray Serve, with Kubernetes deployment configurations and GPU observability. The FastAPI gateway targets vLLM; alternative runtimes have separate deployment paths. 

**[autoresearch](https://github.com/maxgregaabig/autoresearch) — A bounded loop for autonomous experimentation.**  
An agent edits training code, runs a fixed-budget experiment, evaluates the result, and keeps or reverts the change. The interesting boundary is the experiment contract: what may change, what stays fixed, and what counts as improvement.

### Developer tools

| Project | What it makes visible |
| --- | --- |
| **[FlakeLedger](https://github.com/maxgregaabig/FlakeLedger)** | Flaky tests across reruns of the same commit, with a transparent model for retry compute and developer waiting costs. Python; offline JUnit XML analysis. |
| **[ReviewTide](https://github.com/maxgregaabig/ReviewTide)** | Review waiting times and code-ownership concentration from PR and Git exports. Reports sample sizes and process bottlenecks without ranking individual productivity. Python; offline analysis. |
