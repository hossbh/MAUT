# Multi-Attribute Utility Theory (MAUT) for Decision and Risk Analysis

A complete multi-attribute utility model that compares four strategic options for a manufacturing company under uncertainty: sustainable product design, a gender-balanced board, a 50 % production increase and R&D investment. The options are judged on four competing objectives: profit, CO₂ emissions reduction, board gender balance and brand image.

## Notebooks

| Notebook | What it does | Key result |
|---|---|---|
| [Multi-Attribute Utility Model](Decision%20and%20Risk%20Analysis.ipynb) | Builds the consequence table, fits a utility function for each attribute from certainty-equivalent assessments, derives attribute weights with the swing-weight method, and propagates uncertainty in each option's consequences with a 1,000-sample Monte Carlo simulation using triangular distributions. | Emissions reduction carries the largest weight (0.41) and profit the smallest (0.08). The options are ranked by expected total utility. The sensitivity analysis shows that Option 4 closes the gap to Option 1 if its profit rises to about $3 M. |

## Tech stack

Python 3 · Jupyter · `numpy` · `pandas` · `matplotlib` · `scipy`

## Run it

```bash
pip install -r requirements.txt
jupyter notebook
```

## About

This work was written by **Hossein Basereh** as part of graduate coursework (Decision and Risk Analysis) and is shared as a portfolio of applied analysis. If you are taking a similar course, please follow your institution's academic-integrity policy.

## Licence

Copyright © 2024-2026 Hossein Basereh. The code is released under the [MIT License](LICENSE): you may reuse it with attribution, and it is provided "as is", without warranty. Assignment prompts quoted in the notebooks and any third-party datasets remain the property of their original authors and are not covered by this licence.
