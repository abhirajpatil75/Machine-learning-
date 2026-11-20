# Machine Learning Algorithms: Beginner Projects

Sixteen notebooks: one program and one separate theory notebook for each of eight classic algorithms.

| Algorithm | Program notebook | Theory notebook |
|---|---|---|
| Linear Regression | [Program](notebooks/01_linear_regression.ipynb) | [Theory](notebooks/01_linear_regression_theory.ipynb) |
| Decision Tree | [Program](notebooks/02_decision_tree.ipynb) | [Theory](notebooks/02_decision_tree_theory.ipynb) |
| K-Means | [Program](notebooks/03_k_means.ipynb) | [Theory](notebooks/03_k_means_theory.ipynb) |
| K-Nearest Neighbors | [Program](notebooks/04_knn.ipynb) | [Theory](notebooks/04_knn_theory.ipynb) |
| Random Forest | [Program](notebooks/05_random_forest.ipynb) | [Theory](notebooks/05_random_forest_theory.ipynb) |
| Support Vector Machine | [Program](notebooks/06_svm.ipynb) | [Theory](notebooks/06_svm_theory.ipynb) |
| Naive Bayes | [Program](notebooks/07_naive_bayes.ipynb) | [Theory](notebooks/07_naive_bayes_theory.ipynb) |
| Perceptron | [Program](notebooks/08_perceptron.ipynb) | [Theory](notebooks/08_perceptron_theory.ipynb) |

## Program notebook contents

Each program notebook loads example data; inspects columns, missing values, duplicates, and (for classification) class counts; cleans duplicate rows and missing numeric values; analyzes summary statistics and plots feature distributions; prepares a train/test split where appropriate; implements and evaluates the algorithm; and inspects an example output. The included teaching datasets are already clean, so the cleaning cells demonstrate practical checks without introducing artificial errors.

Theory notebooks explain concepts separately, including the task, intuition, strengths, limitations, and relevant metrics.

## Run

Install Python 3.9+, then run `python -m pip install -r requirements.txt` and `jupyter lab`. Open notebooks under `notebooks/` and run cells from top to bottom. A virtual environment is recommended.

## Data

No separate files are required. Examples use small datasets bundled with scikit-learn or reproducibly generated synthetic data.

Educational examples only; results are not production-ready models.


## Program notebook style

Program notebooks follow a code-first, step-by-step format like the supplied Linear Regression example: import libraries, load data, inspect rows and columns, check and clean missing/duplicate data, analyze it, select features and target, split data, scale where appropriate, fit the model, evaluate it, and try a prediction. Theory remains in each separate `*_theory.ipynb` notebook. The examples load datasets bundled with scikit-learn, so no CSV download is needed.
