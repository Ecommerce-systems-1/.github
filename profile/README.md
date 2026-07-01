# Ecommerce-systems

23 production-grade ecommerce engineering projects — from ML-powered cart recovery to distributed order management at scale.

Each project follows a rigorous PM → architecture → synthetic data → TDD implementation → live demo pipeline.

## Projects

| # | Project | Domain | Stack | Status |
|---|---------|--------|-------|--------|
| 01 | [Smart Cart Abandonment Predictor](https://github.com/Ecommerce-systems-1/smart-cart-abandonment-predictor) | Checkout & Conversion | Python · XGBoost · FastAPI · Streamlit | [🟢 Live Demo](https://huggingface.co/spaces/RishabhHajela/smart-cart-abandonment-predictor) |
| 02 | [Fraud Detection & Risk Scoring API](https://github.com/Ecommerce-systems-1/fraud-detection-risk-scoring-api) | Checkout & Conversion | Python · RandomForest · SHAP · FastAPI · Streamlit | [🟢 Live Demo](https://huggingface.co/spaces/RishabhHajela/fraud-detection-risk-scoring) |
| 03 | [Semantic Search & Auto-Suggest Engine](https://github.com/Ecommerce-systems-1/semantic-search-auto-suggest) | Search & Discovery | Python · Sentence-Transformers · Qdrant · Next.js | [🟢 Live Demo](https://huggingface.co/spaces/RishabhHajela/semantic-search-auto-suggest) |
| 04 | AI Guardrails Service | Platform Trust | Python · Anthropic API · FastAPI | 🔜 Coming soon |
| 05 | High-Volume Flash Sale Simulator | Platform Infrastructure | Go · Redis · PostgreSQL · k6 | 🔜 Coming soon |
| 06–23 | Full pipeline in progress | Various | Varied | 🔜 Coming soon |

## Shared Tooling

[`synthetic-data-toolkit`](https://github.com/Ecommerce-systems-1/synthetic-data-toolkit) — Domain-specific synthetic data generators used across all 23 projects. Pip-installable.

## Design Philosophy

Every project in this org is designed around the same framework:
- **Problem-first:** 5-Questions doc + BRD before a line of code is written
- **Systems thinking:** Explicit CAP theorem trade-offs, concurrency strategy, failure modes
- **Synthetic data:** Parameterized generators for happy path, edge cases, and stress tests
- **Live demos:** Every project is deployed and accessible without local setup
