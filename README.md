# Machine Learning Algorithms

A practical collection of Jupyter notebooks exploring foundational machine learning techniques in Python. This repository serves as a personal workspace to experiment with baseline models, analyze decision boundaries, and tune parameters.

## Included Notebooks

| Notebook | Focus | Key Topics |
| :--- | :--- | :--- |
| **`KNN.ipynb`** | K-Nearest Neighbors | Neighborhood size ($k$), distance metrics, and prediction accuracy |
| **`SVM.ipynb`** | Support Vector Machines | Margin maximization, classification kernels, and decision boundaries |
| **`Logistic_Regression.ipynb`** | Logistic Regression | Baseline classification pipeline, decision thresholds, and log-loss |
| **`Model_Training.ipynb`** | Model Training Workflow | Estimator fitting, train/test splitting, and evaluation |

## Getting Started

### Prerequisites
* Python 3.8+
* Jupyter Notebook or Google Colab

### Installation & Local Setup

```bash
# Clone the repository
git clone [https://github.com/ranitbanik/Machine-Learning-Algorithms.git](https://github.com/ranitbanik/Machine-Learning-Algorithms.git)
cd Machine-Learning-Algorithms

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
python -m pip install jupyter numpy pandas scikit-learn matplotlib seaborn

# Launch Jupyter
jupyter notebook
