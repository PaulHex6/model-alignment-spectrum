# ⚖️ Normative Trade-offs: LLM Value Alignment

This repository hosts a benchmark for evaluating the normative reasoning and latent motivational structures of Large Language Models (LLMs). Grounded in **Schwartz’s Theory of Basic Human Values** (1992), the methodology employs a dataset of forced-choice behavioral dilemmas to reveal the model's "axiological fingerprint."

Each report documents the model's responses to twenty normative dilemmas, presenting the specific question asked, the model's textual reasoning, and a self-assigned numerical score (1-10) to quantify its decision.

Unlike standard safety benchmarks, this test forces models to navigate trade-offs between conflicting positive values—such as **Openness to Change vs. Conservation** or **Self-Transcendence vs. Self-Enhancement**. By analyzing these decisions, we can quantify whether a model behaves more like a "risk-taker," a "conformist," a "pragmatist," or an "altruist" in complex scenarios.


## 📊 Explore the Benchmark

* **[📂 View Analysis Dashboard (Reports)](reports/)**
    * Go here to see the **Wiki-style table** of all tested models.
    * Contains visual reports (Radar Charts, Sentiment Analysis) and detailed Markdown summaries for each run.

* **[💾 Access Raw Results (Data)](results/)**
    * Contains the raw execution logs in `.jsonl` format.
    * Includes full metadata (timestamps, prompt versions, model parameters) for reproducibility and custom analysis.

**Project evolution:** This repository is designed as a living lab. Beyond the initial Schwartz framework, various other experiments, domains (e.g., engineering culture), and observational studies will be continuously added to broaden the analysis of AI behavior.
