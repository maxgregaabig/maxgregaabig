<p align="center">
  <img src="./assets/profile-header.svg" alt="Max Regan — dependable AI, from model to production" width="100%" />
</p>

# Hi, I'm Max.

**Staff Software Engineer · AI Systems & ML Infrastructure**  
Miami, Florida · Carnegie Mellon CS

I build the infrastructure that makes AI dependable in production: agent workflows that recover from failure, retrieval systems that preserve evidence, and inference services that respect latency and cost budgets.

At **Google DeepMind**, I work on enterprise agent orchestration. Previously, I worked on large-model serving at **Google** and spent seven years at **Amazon**, moving from distributed backend services into personalization and shared ML infrastructure. I stay hands-on with implementation while defining interfaces and technical direction across teams.

## Selected projects

Small tools and open-source labs for inspecting the systems behind reliable software.

### Agent execution, retrieval & inference

**[durableflow](https://github.com/maxgregaabig/durableflow) — What survives when an agent crashes?**  
A Python/SQLite lab for checkpoints, persistent approvals, model fallback, and failure injection. My repository includes a [merged workshop curriculum](https://github.com/maxgregaabig/durableflow/pull/2) with exercises and capstones that make those mechanics easier to explore. Based on [Marcos Polanco's DurableFlow](https://github.com/marcospolanco/durableflow).

**[pgvector-rag](https://github.com/maxgregaabig/pgvector-rag) — Retrieval with inspectable evidence.**  
A FastAPI document-search service with PostgreSQL/pgvector, Redis caching, chunk-level citations, and an evaluation harness. Deterministic providers make the core behavior testable without API keys. An exploration of [H4mid2019's project](https://github.com/H4mid2019/pgvector-rag).

**[model-serving-stack](https://github.com/maxgregaabig/model-serving-stack) — Serving is a systems problem.**  
A reference environment for vLLM, Triton, and Ray Serve, with Kubernetes deployment configurations and GPU observability. The FastAPI gateway targets vLLM; alternative runtimes have separate deployment paths. Based on [TylrDn's serving stack](https://github.com/TylrDn/model-serving-stack).

**[autoresearch](https://github.com/maxgregaabig/autoresearch) — A bounded loop for autonomous experimentation.**  
Exploring [Andrej Karpathy's autoresearch](https://github.com/karpathy/autoresearch): an agent edits training code, runs a fixed-budget experiment, evaluates the result, and keeps or reverts the change. The interesting boundary is the experiment contract: what may change, what stays fixed, and what counts as improvement.

### Developer tools

| Project | What it makes visible |
| --- | --- |
| **[FlakeLedger](https://github.com/maxgregaabig/FlakeLedger)** | Flaky tests across reruns of the same commit, with a transparent model for retry compute and developer waiting costs. Python; offline JUnit XML analysis. |
| **[ReviewTide](https://github.com/maxgregaabig/ReviewTide)** | Review waiting times and code-ownership concentration from PR and Git exports. Reports sample sizes and process bottlenecks without ranking individual productivity. Python; offline analysis. |
