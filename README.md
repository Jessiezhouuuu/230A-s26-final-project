# 230A-s26-final-project

Estimating the Causal Effect of Extracurricular Activities on Student Performance

This repository contains the code, data, figures, and report for the UC Berkeley STAT 230A (Spring 2026) final project.

**Project goal:** estimate causal effects of participation in extracurricular activities on student academic outcomes using observational data and modern causal inference methods.

**Quick links**
- Notebook: code/230a_proj.ipynb
- Data: data/StudentPerformanceFactors.csv
- Report (LaTeX): report/report.tex

**Repository structure**
- code/: analysis notebooks and scripts
- data/: raw and processed datasets
- figs/: generated figures
- report/: LaTeX source and bibliography
- results/: generated table snippets for the report

Getting started

1. Install requirements (recommended to use a virtual environment).

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter pandas numpy scipy scikit-learn statsmodels matplotlib seaborn
```

2. Open the analysis notebook:

```bash
jupyter lab code/230a_proj.ipynb
```

Data

The primary dataset is `data/StudentPerformanceFactors.csv`. Inspect `code/230a_proj.ipynb` for how the data are cleaned and processed.

Reproducible outputs

- Figures are written to `figs/` by the notebook.
- Tables used in the report are in `results/` as TeX fragments.



This repository is for course work; check with course policy for reuse and attribution.

