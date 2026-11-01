# Machine Learning Algorithms

A practical notebook collection for exploring fundamental machine learning techniques in Python. This repository is a study workspace: run an example, inspect its results, and experiment with parameters to understand how the model behaves.

## At a glance

| Notebook | Focus | What to explore |
| --- | --- | --- |
| [KNN.ipynb](KNN.ipynb) | K-nearest neighbors | Neighborhood size, predictions and evaluation |
| [SVM.ipynb](SVM.ipynb) | Support vector machines | Classification and decision boundaries |
| [Logistic_Regression.ipynb](Logistic_Regression.ipynb) | Logistic regression | A baseline classification workflow |
| [Model_Training.ipynb](Model_Training.ipynb) | Model training | Fitting models and working with predictions |

These are the **four notebooks currently included**, rather than a claim that the entire ML curriculum has been implemented.

## Run the notebooks

You'll need Python 3 and a Jupyter-compatible environment. Clone this repository and install commonly used data science packages:

```bash
git clone https://github.com/rohitbiswas1/Machine-Learning-Algorithms.git
cd Machine-Learning-Algorithms
python -m venv .venv
source .venv/bin/activate
python -m pip install jupyter numpy pandas scikit-learn matplotlib seaborn
jupyter notebook
```

On Windows, activate the environment using `.venv\Scripts\activate` (Command Prompt) or `.venv\Scripts\Activate.ps1` (PowerShell), then run the remaining commands.

You can also open the `.ipynb` files in Google Colab without installing Jupyter locally. Notebook dependencies may vary by example.

## How to learn from each example

1. Read through the code and identify the dataset, features and target.
2. Run the cells in order, checking intermediate outputs.
3. Change one parameter at a time and compare the result.
4. Inspect evaluation metrics; avoid judging a model only by training accuracy.
5. Record what changed, what improved and what did not.

## Concepts to practise next

- **Data preparation:** missing values, encoding, scaling, and train/test splits
- **Supervised learning:** linear regression, decision trees, random forests, and Naive Bayes
- **Unsupervised learning:** K-means clustering and principal component analysis
- **Evaluation:** cross-validation, precision, recall, F1 score, and confusion matrices
- **Model improvement:** pipelines and hyperparameter searches

These are learning directions, **not files that are already present**.

## Repository layout

```text
Machine-Learning-Algorithms/
├── KNN.ipynb
├── Logistic_Regression.ipynb
├── Model_Training.ipynb
├── SVM.ipynb
├── README.md
└── LICENSE
```

## Maintainer

Maintained as a machine-learning learning repository by [Rohit Biswas](https://github.com/rohitbiswas1).

## Source acknowledgment and license

The initial notebooks in this repository were copied from [Basic-Machine-Learning-Codes](https://github.com/soumojit-dev/Basic-Machine-Learning-Codes). This README has been rewritten for the present repository. The original project's Apache 2.0 license remains in [LICENSE](LICENSE); see that file for the applicable license terms.
