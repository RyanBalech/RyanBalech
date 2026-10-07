# Ryan Balech

MSc **Data Science** at **École Polytechnique**, joint degree with **HEC Paris**. Electrical and Communications Engineering graduate from the **American University of Beirut**, with a **minor in Mathematics**. Software and data engineering experience at **Amazon** and **Inmind.ai**.

I work on machine learning, software systems and quantitative research: implementing models, designing experiments and building reproducible evaluation pipelines.

## Research & engineering

| Project | Technical focus | Evidence |
| --- | --- | --- |
| [CUDA GEMM Performance](https://github.com/RyanBalech/cuda-deep-learning-performance) | C++, CUDA, shared-memory tiling, strict-FP32 cuBLAS, Nsight Compute | 30-shape FP64-reference validation; **1.30×** tiled/direct speedup at 512³ and 1024³ on RTX 4050 Laptop GPU; raw kernel timings and sanitizer logs |
| [Repository-Level LLM Agent Evaluation](https://github.com/RyanBalech/llm-agent-evaluation) | SWE-bench Verified localization; BM25, Transformer retrieval and reciprocal-rank fusion | Fixed 20-instance BM25 baseline: Recall@5 **0.425**, MRR **0.279**, nDCG@5 **0.297** |
| [Flow Matching — Independent Reproduction](https://github.com/RyanBalech/Flow-Matching-Reproduction) | PyTorch vector fields, Euler/RK4 neural ODE integration, MMD evaluation | Five matched-compute seeds; RK4 mean MMD² ~8% lower, with a bootstrap interval spanning zero |
| [Limit Order Book Research](https://github.com/RyanBalech/limit-order-book-research) | Order-flow imbalance, microprice, forward labels and chronological evaluation | Logistic, boosted-tree and DeepLOB-style baselines; reproducibility checks and cost-aware analysis |
| [QRT Historical Reconstruction](https://github.com/RyanBalech/qrt-asset-allocation-reconstruction) | Overlap matching, exchange calendars, adaptive ridge and CatBoost | **76.21%** on 47,192 reserved rows; historical batch reconstruction, with evaluation provenance documented |
| [Recidivism Forecasting](https://github.com/RyanBalech/recidivism-forecasting-analysis) | Logistic regression, XGBoost and TabICLv2; calibration, interpretation and proxy/fairness auditing | 25K+ records; approximately **0.73 ROC AUC** |

I also built **Allocation Lab**, a Docker-packaged Streamlit application with validated data imports, interactive ML evaluation and automated tests. Its source currently requires repository access.

## Technical background

**Python · SQL · C++ · Java · PyTorch · PySpark · scikit-learn · NumPy · Pandas · Hugging Face Transformers · Git · Docker · GitHub Actions · Palantir Foundry**

CMA CGM Excellence Scholarship · GRE Quantitative **170/170** · AUB graduate with Distinction.

**Languages:** English — Fluent · Arabic — Native · French — Intermediate.
