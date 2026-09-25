# Machine Learning Concepts

> A beginner-friendly series of hands-on Jupyter Notebooks covering fundamental to advanced machine learning algorithms, mathematical intuitions, pipelines, and implementations from scratch.

---

## 📌 Repository Contents

The notebooks are organized progressively, covering regression, classification, regularization, dimensionality reduction, and ensemble methods:

### 1. Regression & Foundations
* **`SLR1.ipynb`** — Simple Linear Regression fundamentals and cost function optimization.
* **`MLR1.ipynb` & `MLR2.ipynb`** — Multiple Linear Regression implementations, matrix operations, and evaluation.
* **`MulticollinearityDetection.ipynb`** — Identifying collinearity using Variance Inflation Factor (VIF) and correlation matrices.
* **`Lasso,Ridge,Elasitcnet.ipynb`** — L1, L2, and ElasticNet regularization techniques to prevent overfitting.
* **`mlr2model.pkl`** — Serialized trained linear regression model artifact.

### 2. Classification & Probabilistic Models
* **`LogisticReg.ipynb` & `LogisticReg2 (1).ipynb`** — Binary classification, sigmoid function, and log-loss intuition.
* **`LogisticReg with Hyperparameter tuning (1).ipynb`** — Logistic regression tuned with GridSearchCV/RandomizedSearchCV.
* **`MulticlassClf-1.ipynb` & `Multiclassclf-2 (1).ipynb`** — Multiclass classification approaches (One-vs-Rest / One-vs-One).
* **`GaussianNBclf.ipynb`** — Gaussian Naive Bayes probabilistic classifier for continuous features.

### 3. Instance-Based & Non-Parametric Models
* **`KNN regression with HP tuning.ipynb`** — K-Nearest Neighbors regression with optimal $k$ search.
* **`KNN classification with HP tuning.ipynb`** — K-Nearest Neighbors classification with distance metrics and cross-validation.
* **`DecisionTree.ipynb`** — Classification decision trees, entropy, and Gini impurity splits.
* **`DTregressor.ipynb`** — Regression trees utilizing variance reduction.

### 4. Support Vector Machines (SVM)
* **`Support Vector Classifier.ipynb`** — Linear SVC, decision boundaries, and margin maximization.
* **`Support Vector Regressor.ipynb`** — Support Vector Regression using $\epsilon$-insensitive tube loss.
* **`SVMKernel.ipynb`** — Non-linear classification via Kernel trick (RBF, Polynomial, Sigmoid).

### 5. Ensemble Learning
* **`1.CustomBagging.ipynb`** — Scratch implementation of bootstrap aggregating logic.
* **`2.BaggingRegressor.ipynb`** — Bagging ensembles applied to continuous regression targets.
* **`AdaboostClf.ipynb`** — Adaptive Boosting with sequential weak learners and sample re-weighting.
* **`GradientBoosting.ipynb`** — Gradient boosted decision trees minimizing residual errors.
* **`XGBoosting.ipynb`** — Extreme Gradient Boosting for speed and regularization.
* **`CatBoost.ipynb`** — Boosting optimized for categorical features without extensive pre-encoding.
* **`Stacking.ipynb`** — Heterogeneous model stacking with meta-learners.

### 6. Pipelines & Unsupervised Learning
* **`3.MultipleModelTraining,Pipeline_and_ColumnTransfer.ipynb`** — Scikit-Learn `Pipeline`, `ColumnTransformer`, preprocessing, and multi-model benchmarking.
* **`PCA.ipynb`** — Principal Component Analysis for dimensionality reduction, variance explanation, and feature compression.

---

## 🛠️ Getting Started

### Prerequisites
Make sure you have Python 3.8+ installed along with Jupyter Notebook or JupyterLab:

```bash
git clone [https://github.com/AnupamPatra001/MachineLearningConcepts.git](https://github.com/AnupamPatra001/MachineLearningConcepts.git)
cd MachineLearningConcepts
