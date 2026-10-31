# Ontology vs Semantic Model, Explained with My Running Data

Companion notebook to the article on [buckenhofer.com](https://buckenhofer.com): my Strava runs 2021 to 2025 in DuckDB, an ontology, a semantic model and a mapping in Apache Ossie YAML, and a test of whether they help an LLM write correct SQL.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abuckenhofer/ontology-vs-semantic-model/blob/main/ontology_vs_semantic_model.ipynb)

Run all cells from top to bottom. The LLM test at the end has a switch `LLM`:

| Value | LLM | Colab secret |
| --- | --- | --- |
| `colab` | Colab's built-in Gemini | none |
| `gemini_api` | Gemini API | `GEMINI_API_KEY` |
| `openrouter` | any model on OpenRouter | `OPENROUTER_API_KEY` |

All attempts behind the numbers in the article (GLM 5.1 and Llama 3.1 8B via OpenRouter) are in `results/llm_attempts.csv`.
