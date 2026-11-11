# Quick Pricing and Elasticity Analysis

Companion material for the video lesson **["Quick and dirty": data analysis with Python — pricing and elasticity](https://youtu.be/Vn45DCpdXNw)**.

The notebook [`precificacao_elasticidade.ipynb`](precificacao_elasticidade.ipynb) generates synthetic data, aggregates observations into bins, visualizes price and customer acquisition, and fits linear and quadratic approximations. The aim is to demonstrate a short, reproducible exploratory workflow.

## Interpretation

In economic theory, the price elasticity of demand is defined as

\[
\varepsilon_{Q,P}=\frac{\partial Q}{\partial P}\frac{P}{Q}.
\]

In the notebook's synthetic dataset, the `Elasticidade` column is constructed using a function chosen for teaching purposes. Strictly speaking, it is a **synthetic index**, rather than an elasticity estimated from observational or experimental variation. Similarly, the curve called `Laffer` in the code is a visual analogy for customer acquisition; the classical Laffer curve refers to the relationship between tax rates and tax revenue.

## Analytical limitations

An association between price and demand may reflect segmentation, promotions, seasonality, customer selection, and simultaneity. An applied analysis should define the estimand, control for relevant confounders, and favor experiments, quasi-experiments, or appropriate causal models. The notebook does not replace that research design.

## Running the notebook

From the repository root:

```bash
conda activate ai-data-citizen
jupyter lab data_science/quick_dirty_analytics/precificacao_elasticidade.ipynb
```

All data are generated locally with a fixed seed; no real commercial data are used.
