# Learning K-Nearest Neighbors

Small scikit-learn examples demonstrating nearest-neighbor classification and regression on generated datasets.

## Contents

- `KNN_classification.ipynb`: generates 1,000 samples with three features, fits a five-neighbor classifier, and reports classification metrics.
- `KNN_Regression.ipynb`: generates 1,000 samples with two features, fits a six-neighbor regressor, and reports R², MAE, and MSE.

## Run locally

Use Python 3 and run Jupyter from the repository directory.

```bash
git clone https://github.com/Sanskar1314/Learning_KNN.git
cd Learning_KNN
python -m venv .venv
source .venv/bin/activate
python -m pip install jupyterlab numpy pandas matplotlib seaborn scikit-learn
jupyter lab
```

On Windows, activate the environment with `.venv\Scripts\activate`. Open the notebook listed above and run its cells in order. Results and visualizations appear in the notebook.

## Reproduction notes

No external data files are needed. The classification notebook ends with an unfinished GridSearchCV exercise written as plain text in a code cell; skip that cell or convert it to Markdown. Some classification metrics use reversed arguments; use true labels first for per-class interpretation.
