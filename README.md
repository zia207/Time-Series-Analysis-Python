# Time Series Analysis in Python

From statistical modeling to machine learning — a 12-part applied tutorial.

**Website:** [https://zia207.github.io/Time-Series-Analysis-Python/](https://zia207.github.io/Time-Series-Analysis-Python/)

Every part is an executed Jupyter notebook. Read it on the site, or open the `.ipynb` files under [`notebooks/`](notebooks/) and run them yourself.

## The parts

| Part | Notebook |
|------|----------|
| 1. Foundations & Data Handling | [part-01-foundations.ipynb](notebooks/part-01-foundations.ipynb) |
| 2. Statistical Properties & Decomposition | [part-02-stationarity.ipynb](notebooks/part-02-stationarity.ipynb) |
| 3. Smoothing & Exponential Methods | [part-03-smoothing.ipynb](notebooks/part-03-smoothing.ipynb) |
| 4. The ARIMA Family | [part-04-arima.ipynb](notebooks/part-04-arima.ipynb) |
| 5. Advanced Statistical & Multivariate Models | [part-05-advanced-multivariate.ipynb](notebooks/part-05-advanced-multivariate.ipynb) |
| 6. Evaluation, Backtesting & Baselines | [part-06-evaluation-backtesting.ipynb](notebooks/part-06-evaluation-backtesting.ipynb) |
| 7. Feature Engineering & the ML Reduction | [part-07-feature-engineering.ipynb](notebooks/part-07-feature-engineering.ipynb) |
| 8. Machine Learning Forecasting | [part-08-ml-forecasting.ipynb](notebooks/part-08-ml-forecasting.ipynb) |
| 9. Deep Learning for Sequences | [part-09-deep-learning.ipynb](notebooks/part-09-deep-learning.ipynb) |
| 10. Modern Deep Forecasting Architectures | [part-10-modern-dl.ipynb](notebooks/part-10-modern-dl.ipynb) |
| 11. Specialized Topics | [part-11-specialized-topics.ipynb](notebooks/part-11-specialized-topics.ipynb) |
| 12. Deployment & Capstone | [part-12-deployment-capstone.ipynb](notebooks/part-12-deployment-capstone.ipynb) |

## Running the notebooks

```bash
jupyter lab
```

The dataset (`monthly_price.csv`) sits alongside the notebooks.

## Building the website

```bash
quarto render     # writes HTML into ./docs
quarto preview    # live local preview
```

Pushing to `main` deploys the site via GitHub Actions (Settings → Pages → Source: **GitHub Actions**).
