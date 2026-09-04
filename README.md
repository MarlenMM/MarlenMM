## Marlen Melis

**B.S. Artificial Intelligence Computing + Business & Technology Management — KAIST**, Daejeon, South Korea (2026–2030)
Nazarbayev Intellectual School of Physics & Mathematics, Almaty · HIT Global Summer School, Harbin


---

### Projects

| Project | What it is | Stack |
|---|---|---|
| **[quantpulse](https://github.com/MarlenMM/quantpulse)** · [live demo](https://marlenmm.github.io/quantpulse/) | Equity research and portfolio-construction engine. Eight free data sources into a 23-table schema, seven-category composite scoring, walk-forward backtesting, and three portfolio optimisers (mean-variance, Hierarchical Risk Parity, Black-Litterman). ~17k lines of engine code, 1,466 automated tests including property-based. | Python · scikit-learn · statsmodels · FastAPI · React/TS · SQLite |
| **[code-review-ai](https://github.com/MarlenMM/code-review-ai)** | Four experiments on whether an LLM can predict and review pull requests better than a trained model: a 1,494-PR dataset I mined from five large OSS repositories, merge-prediction models, an LLM review pipeline, and a FastAPI backend plus a VS Code extension that wrap the best of both. | Python · scikit-learn · FastAPI · TypeScript |
| **[modulemate](https://github.com/MarlenMM/modulemate)** | Retrieval-grounded course assistant that answers only from staff-issued material and cites the slide it came from. Hybrid dense + BM25 retrieval, cross-encoder re-ranking, and three independent refusal layers. | Python · FAISS · sentence-transformers · Streamlit |

### The numbers I would defend in an interview

- **quantpulse** — Sharpe and CAGR are reported as moving-block bootstrap confidence intervals, never as a bare point estimate. Every forecast (ARIMA/SARIMA, gradient boosting, Monte Carlo) is graded out-of-sample against a random-walk baseline before it is allowed to ship.
- **code-review-ai** — the best LLM configuration **matched rather than beat** the trained Random Forest: 93.75% accuracy, 0.816 macro-F1, an identical confusion matrix. That was the opposite of my hypothesis, so it became the headline finding.
- **modulemate** — **zero fabricated citations** and a 1.000 refusal rate on the out-of-scope set across a 63-question gold set, with the false-refusal rate (0.038) published beside it, because a refusal rate on its own can be maximised by refusing everything.


### Research

Sole author, peer-reviewed — *"How Did Personal Loans Influence the Well-Being of Financially Unstable Families in Kazakhstan Over the Last Five Years?"*, **Central Asian Scientific Journal**, Vol. 4(23), pp. 12–21 (2024, published in Kazakh). A 101-respondent survey and two semi-structured interviews, designed, fielded and analysed alone.

### Toolkit

**Languages** — Python, TypeScript, SQL, C
**ML and data** — scikit-learn, statsmodels, pandas, NumPy, FAISS, sentence-transformers
**Systems** — FastAPI, SQLAlchemy, Alembic, React, Streamlit, SQLite
**Engineering** — pytest, Hypothesis (property-based testing), GitHub Actions CI, ruff, mypy, pre-commit
**Quantitative** — portfolio optimisation (MPT, HRP, Black-Litterman), backtesting, bootstrap confidence intervals, Monte Carlo, ARIMA/SARIMA
**Spoken** — English (IELTS 8.0), Russian (native), Kazakh (native)

### Contact

marlen.melis@kaist.ac.kr
