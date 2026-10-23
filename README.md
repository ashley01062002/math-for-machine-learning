# Mathematics for Machine Learning (From First Principles) 🧠📐

Welcome to my self-study portfolio dedicated to learning the mathematical foundations of Machine Learning. 

This repository serves as my structured transition into high-dimensional data structures, multivariable optimization, and advanced statistical theory. Every concept here has been derived by hand on a physical sandbox, summarised in my personal knowledge base, and implemented in pure code.

## 🗺️ Core Methodology & Philosophy
Rather than relying on high-level black-box frameworks (like PyTorch or Scikit-Learn), my goal is to bridge the gap between abstract equations and execution. 
1. **Theory:** Sourced from **MIT OpenCourseWare (OCW)** and standard academic literature.
2. **Intuition:** Geometric visualizations and plain-English breakdowns.
3. **Execution:** Writing the underlying algorithms from scratch using raw **NumPy**.

---

## 📚 Curriculum Roadmap & Current Progress

| Domain | Core Focus Areas | Status | Portfolio Notebook Link |
| :--- | :--- | :---: | :--- |
| **Linear Algebra** | Vector Spaces, Matrices, Eigenvalues/Eigenvectors, SVD | 🟡 In Progress | [View Notebook](./notebooks/linear_algebra_foundations.ipynb) |
| **Multivariable Calculus** | Partial Derivatives, Gradients, Chain Rule, Backpropagation | ⚪ Planned | [Coming Soon](#) |
| **Probability & Stats** | Continuous PDFs, Bayes' Theorem, Maximum Likelihood (MLE) | ⚪ Planned | [Coming Soon](#) |

---

## 🛠️ Main Projects & Implementations

### 1. Dimensionality Reduction (PCA from Scratch)
*   **The Math:** Empirical covariance matrices, variance maximization, and Eigendecomposition (Σ v = λ v).
*   **The Code:** Center the data, calculate the matrix transpose dot product, extract eigenvalues via `np.linalg.eig`, and project data onto principal components.
*   **Dataset:** MNIST Handwritten Digits.
*   👉 **[PCA Project Notebook](./notebooks/pca_from_scratch.ipynb)**

### 2. The Engine of Optimization (Backpropagation Calculus)
*   **The Math:** Application of the multivariable chain rule to flow error derivatives backwards through a computational graph.
*   **The Code:** Vectorised matrix updates for a Multi-Layer Perceptron (MLP) using raw gradient descent.
*   👉 **[Calculus & Backprop Notebook](./notebooks/backprop_calculus.ipynb)**

### 3. Probabilistic Learning (Maximum Likelihood Estimation)
*   **The Math:** Deriving Binary Cross-Entropy loss by taking the log-likelihood of a Bernoulli distribution.
*   **The Code:** Optimisation of a Logistic Regression boundary line.
*   👉 **[Probability & MLE Notebook](./notebooks/mle_logistic_regression.ipynb)**

---

## 🔬 Study Resources & Attributions
*   **MIT OCW 18.06** – Linear Algebra (Prof. Gilbert Strang)
*   **Stanford University** – Introduction to Statistical Learning (ISLR)

