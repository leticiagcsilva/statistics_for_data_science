# Statistics for Data Science with Python ver

A professional study journey based on the book *Practical Statistics for Data Scientists: 50 Essential Concepts* by Peter Bruce and Andrew Bruce.  
All topics are translated into practical Python implementations, with a focus on observability, reliability, and real-world data scenarios.

---

## 📌 Purpose

This repository serves both as a structured study log and a professional showcase, aiming to:
- Solidify foundational knowledge in applied statistics
- Explore statistical thinking through reproducible Python code
- Apply concepts to real-world data and production-inspired use cases (SRE, metrics, incidents, SLIs, etc.)
- Document progress with MkDocs, versioning with Poetry, and automation with Taskipy

---

## ⚙️ Tools and Stack

- **Python 3.11+**
- **[Poetry](https://python-poetry.org/)**: dependency and virtual environment management
- **[Taskipy](https://pypi.org/project/taskipy/)**: task automation (`mkdocs`, notebooks)
- **[MkDocs](https://www.mkdocs.org/)**: project documentation
- **[Jupyter Notebooks](https://jupyter.org/)**: analysis and visualizations

---

## 🗂️ Project Structure

```bash
.
├── notebooks/          # Daily study notebooks (1 per topic/day)
├── src/                # Reusable Python modules (e.g., statistics, visuals)
├── data/               # Datasets used in analysis
├── logs/               # Daily progress logs
├── docs/               # MkDocs documentation site
├── pyproject.toml      # Poetry config
├── mkdocs.yml          # Documentation configuration
└── tasks.py            # Taskipy command shortcuts
```

---

## 📚 Topics Covered

Each notebook focuses on a group of related concepts from the book, using real or public datasets (Kaggle, APIs). Topics include:
- Exploratory Data Analysis (EDA)
- Data taxonomy and type optimization
- Location & variability estimators
- Percentiles and SLIs/SLOs
- Bootstrap and resampling
- Hypothesis testing (deploys, alerts, incidents)
- Tests t, ANOVA, and chi-square for platform experimentation

Full outline: [Study Plan – Days 1 to 10](docs/cronograma_dia1_a_10.md)

---

## 📖 Daily Study Logs

- [Day 1 — EDA & Data Taxonomy](logs/2025-04-08.md)
- *(More to be added daily...)*

---

## 🚀 How to Run

```bash
# install dependencies
poetry install

# activate environment
source $(poetry env info --path)/bin/activate

# open notebook server
poetry run task notebook

# serve documentation
poetry run task docs
```

---

## 📎 License

MIT © 2025
