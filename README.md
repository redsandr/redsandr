<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" width="640" alt="Rihhadatul Aimi — NLP &amp; Behavioral Finance AI">
  </picture>
</p>

<p align="center">
  <b>Building grounded NLP systems for financial decision intelligence.</b>
</p>

<p align="center">
  <a href="https://rag-variance-explainer.vercel.app">Landing</a> ·
  <a href="https://github.com/redsandr/rag-variance-explainer">RAG Variance Explainer</a> ·
  <a href="https://github.com/redsandr/cognifi">Cognifi</a> ·
  <a href="mailto:aimirihad@gmail.com">Email</a>
</p>

---

## Featured Project

### <a href="https://github.com/redsandr/rag-variance-explainer"><code>rag-variance-explainer</code></a>

**A multi-sector financial RAG pipeline that answers "why did this metric move?" from real SEC 10-K/10-Q filings — with every claim cited to the exact page.**

| Metric | Value |
|--------|-------|
| recall@10 | **0.81** |
| MRR | **0.54** |
| Faithfulness (restaurant) | **74.24%** strict |
| Companies indexed | **7** (4 sectors) |
| Chunks / Filings | **1,079 / 56** |
| Retrieval gaps | **0** |

**What makes it different:** Most RAG demos work on one domain. This one was built and tested to generalize across restaurant, retail, healthcare, and energy — with zero per-sector tuning. Full ablation study, LLM-as-judge eval, and 40 passing tests in CI.

> `local RAG pipeline · cross-encoder re-ranking · query expansion · Qwen2.5-7B-Instruct · ChromaDB · Streamlit · Next.js`

---

## All Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**RAG Variance Explainer**](https://github.com/redsandr/rag-variance-explainer) | Multi-sector financial RAG — ask why a metric changed, get a sourced answer | Python, ChromaDB, llama.cpp, Streamlit, Next.js |
| [**Cognifi**](https://github.com/redsandr/cognifi) | Rule-based NLP for real-time cognitive bias detection in Indonesian investor text. 94.7% accuracy (+18.3pp over Gemini 3 Flash) | Python, NLP |
| [**Sebastianisme**](https://github.com/redsandr/Sebastianisme) | A thinking framework — challenging objective reality, rejecting dogma and systemic bias | — |

---

## Tooling

<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white" alt="Streamlit"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white" alt="scikit-learn"> <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white" alt="NumPy">
