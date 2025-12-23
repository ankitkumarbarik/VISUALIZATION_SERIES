# Data Visualization Internals & Usage (Python)

A serious, engineering-focused **data visualization series** using Python.  
Written with a developer mindset — not for chart collectors or dashboard tutorials.

This repository is about understanding **how visualizations work**,  
**when to use which plot**, and **how to avoid misleading or useless charts**.

No hype.  
No storytelling drama.  
Just clarity, structure, and correct visual reasoning.

---

## Why This Series Exists

Most visualization content online focuses on *pretty outputs*.  
This series focuses on **visual correctness**.

The goal is to:
- Understand visualization as a **tool for reasoning**, not decoration
- Know **why a plot exists**, not just how to generate it
- Build intuition around distributions, relationships, and comparisons
- Write **clean, predictable, reusable plotting code**
- Avoid bad visualization patterns that confuse more than they explain

This is not about BI dashboards or presentations.  
This is about **thinking clearly with data**.

---

## What This Series Covers

### Foundations
- What a plot is actually representing
- Scales, axes, ranges, and resolution
- Visual noise vs visual signal
- Common interpretation mistakes

### Matplotlib (Core Control)
- Line, bar, histogram, scatter plots
- Figure and axes model
- Subplots and layout control
- Labels, legends, annotations
- Explicit styling and configuration
- Understanding defaults instead of fighting them

### Seaborn (Statistical Layer)
- Distribution plots
- Box & violin plots
- Count & categorical plots
- Heatmaps
- Pair plots
- Relationship and regression plots

Focus is on **usage + behavior**, not memorizing functions.

---

## Tech Stack

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

No visualization frameworks.  
No GUI tools.  
Just libraries and fundamentals.

---

## Setup

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

Run locally:
```bash
jupyter notebook
```

Or open directly in Google Colab.

---

## Design Philosophy

- Correctness over aesthetics
- Explicit over implicit
- Readability over clever plots
- Understand data behavior before styling
- A plot should explain something — or it shouldn’t exist

If a visualization is confusing, this series focuses on **why it is confusing**, not how to decorate it.

---

🌱  

Backend-oriented developer approaching data visualization  
with an engineering and systems mindset.
