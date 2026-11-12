# Maths for AI

Jupyter notebooks covering the core mathematics behind machine learning, built from scratch with NumPy. Each topic follows the same pattern: the mathematical explanation in plain terms, a manual step-by-step implementation, and a check against the NumPy/SciPy equivalent.

## Notebooks

1. **01_linear_algebra.ipynb** — vectors, matrices, operations and decompositions
   - Dot products, vector projection, similarity measures, eigendecomposition
2. **02_calculus_and_optimization.ipynb** — derivatives, gradients, optimization
   - Gradients, partial derivatives, gradient descent from scratch
3. **03_probability_and_information_theory.ipynb** — probability and information
   - Expected value, covariance matrices, entropy, KL divergence
4. **04_statistics_and_metric_geometry.ipynb** — statistics and distance geometry
   - Euclidean, Manhattan and Mahalanobis distances, z-score standardization, batch centering

The low-level implementations are built manually step by step, then compared against library functions to verify correctness.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

## Dependencies

NumPy is the main engine; matplotlib, seaborn and plotly are used for visualizations; ipywidgets drives the interactive parts.
