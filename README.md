# 📊 Bayesian MAP vs Logistic Regression for Binary Classification

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)](https://jupyter.org/)

This project compares two approaches to binary classification: a **MAP classifier** with known probabilistic distributions, and a **logistic regression model** trained via stochastic gradient descent. It includes analytical derivations, visualizations, Monte Carlo simulations, and performance comparisons.

> 🧠 This project showcases proficiency in machine learning, statistical modeling, and Python programming. Includes implementation of probabilistic classifiers (MAP, logistic regression), use of stochastic gradient descent, and performance evaluation via Monte Carlo simulation and error metrics.

## 📌 Objective

The goal is to analyze and compare two different settings for binary classification:

1. **Case 1 – Fully known model**:
   - Derive posterior probabilities analytically.
   - Visualize `p(y=+1 | x)` for different variances (easy vs. difficult classification).
   - Estimate classification error using Monte Carlo simulation for both scenarios.

2. **Case 2 – Supervised learning**:
   - Train a logistic regression classifier using stochastic gradient descent (SGD).
   - Estimate classification error empirically using synthetic datasets.
   - Compare performance with the MAP classifier.

## 🌍 Language Note

All code comments are written in Italian, as this project was originally developed in an academic setting in Italy. Nonetheless, the structure, organization, and methodology follow international best practices in data science and statistical modeling.

The project_brief and the report are available both in English and Italian.

## 🛠️ Techniques and Methods

- 📈 **Bayesian classification** with known priors and Gaussian class-conditionals.
- 🧠 **Logistic regression** trained with SGD (with and without Monte Carlo averaging).
- 📊 **Monte Carlo simulation** for empirical error evaluation.
- 🔁 **Performance analysis** based on varying variance and data richness.

## 🧪 Results Summary

- Lower variance leads to sharper posteriors and reduced classification error.
- Logistic regression trained with Monte Carlo-averaged β coefficients yields more stable performance.
- As expected, the MAP classifier achieves slightly lower error, especially when data is limited.

## 📂 Repository Structure

```
📦 BAYESIAN-MAP-VS-LOGISTIC-REGRESSION/
│
├── 📁 instructions/
│   ├── project_brief_ENGLISH.pdf
│   └── project_brief_ITALIAN.pdf
│
├── 📁 notebooks/
│   ├── case1_bayesian_map.ipynb
│   └── case2_logistic_regression.ipynb
│
├── 📁 report/
│   ├── classification_comparison_ENGLISH.pdf
│   └── classification_comparison_ITALIAN.pdf
│
├── .gitignore
├── LICENSE
└── README.md
```

## 📊 Technologies Used

- **Language**: Python
- **Environment**: Jupyter Notebook
- **Libraries**: `NumPy`, `Matplotlib`, `SciPy`

## 🎓 About the Project

This project was created as part of the *Data Science & Data Analysis* course (2024/2025) for the Master’s Degree in Computer Engineering at the **University of Salerno**.

## 👥 Team – University of Salerno
    
* [@francescopiocirillo](https://github.com/francescopiocirillo)
    
* [@alefaso-lucky](https://github.com/alefaso-lucky)

## 📬 Contacts

✉️ Got feedback or want to contribute? Feel free to open an Issue or submit a Pull Request!

## 📈 SEO Tags

```
Bayesian classification, logistic regression, MAP estimation, supervised learning, binary classification, statistical modeling, Python, Jupyter Notebook, Monte Carlo simulation, machine learning, pattern recognition, probabilistic models, data science project, AI model comparison, classification algorithms
```

## 📄 License

This project is licensed under the **MIT License**, a permissive open-source license that allows anyone to use, modify, and distribute the software freely, as long as credit is given and the original license is included.

> In plain terms: **use it, build on it, just don’t blame us if something breaks**.

> ⭐ Like what you see? Consider giving the project a star!
