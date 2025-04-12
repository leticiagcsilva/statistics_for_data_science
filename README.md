# 📊 Statistics for Data Science with Python

A hands-on and professional study journey based on the book  
**_Practical Statistics for Data Scientists: 50 Essential Concepts_**  
by *Peter Bruce* and *Andrew Bruce*

This repository translates key statistical concepts into **real-world Python implementations**, with strong emphasis on **observability**, **reliability engineering (SRE)**, and **data-driven decision making** in production systems.

---

## 🎯 Purpose

This project serves as both a **learning log** and a **technical showcase**, designed to:
- Solidify foundational knowledge in applied statistics
- Build a professional portfolio using real logs and datasets
- Explore statistical thinking through code and visualizations
- Apply each topic to real-world cases (e.g., incidents, SLIs/SLOs, system behavior)
- Use tools such as Poetry, MkDocs, and Taskipy for reproducibility and structure

---

## ⚙️ Tools and Stack

- **Python 3.10+**
- **[Poetry](https://python-poetry.org/)**: dependency and virtual environment management
- **[Taskipy](https://pypi.org/project/taskipy/)**: task automation (`mkdocs`, notebooks)
- **[MkDocs](https://www.mkdocs.org/)**: project documentation
- **[Jupyter Notebooks](https://jupyter.org/)**: analysis and visualizations

---

## 📚 Chapters & Notebooks

| Chapter | Title                                         | Notebook Link |
|---------|-----------------------------------------------|----------------|
| 1       | Exploratory Data Analysis                     | [chapter_01_exploratory_data_analysis.ipynb](notebooks/1.1_exploratory_data_analysis.ipynb) |
| 1 (pt.2)| Location & Variability Estimators             | [chapter_02_location_variability_estimators.ipynb](notebooks/1.2_location_variability_estimators.ipynb) |
| ...     | *(Upcoming)*                                  | *(To be published)* |

> All notebooks use real log datasets (Apache, HDFS) from [LogHub](https://github.com/logpai/loghub).


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

## 🚀 Getting Started

```bash
# Install dependencies
poetry install

# Activate environment
source $(poetry env info --path)/bin/activate

# Launch notebooks
poetry run task notebook

# Serve docs
poetry run task docs
```

---

## 📄 License

MIT © 2025 — Built with ♥ for learning, reliability, and reproducibility
