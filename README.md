# Computational Statistics

This repository contains the materials and code for the final project of the **Statistics and Probability** course. The project applies statistical techniques (the Fisher Scoring algorithm and the Metropolis-Hastings algorithm) **implemented from scratch including**, to fit a Probit regression model for the prediction of coronary heart disease (CHD) using the SAheart dataset.

---

## 📘 Project Overview
- **Course**: Statistics and Probability 
- **Academic Year**: 2023/2024  
- **Team**: Mariapia Tedesco (me), Valentina Brivio, Pasquale Caponio, Enrico Cipolla, Arianna Zottoli

---

## 🏗️ Repository Structure
- `FinalProject_Report.pdf`: The final project report detailing methods, algorithms, and results.
- `FisherScoring.ipynb`: A Jupyter Notebook implementing the Fisher Scoring algorithm.
- `MetropolisHastings.ipynb`: A Jupyter Notebook implementing the Metropolis-Hastings algorithm.
- `SAheart.txt`: The dataset used in the analysis.

---

## 🚀 Features
1. **Fisher Scoring Algorithm**:
   - Iteratively optimizes parameters using the observed Fisher Information matrix.
   - Includes convergence diagnostics and log-likelihood tracking.

2. **Metropolis-Hastings Algorithm**:
   - A Bayesian approach using single-site updates.
   - Evaluates parameter convergence using autocorrelation plots and posterior probabilities.

3. **SAheart Dataset Analysis**:
   - Predicts coronary heart disease (CHD) based on risk factors like tobacco use, cholesterol levels, age, and family history.
   - Outputs marginal effects for interpretable insights into the impact of each covariate.

4. **Comparison of Algorithms**:
   - Coefficient estimates, marginal effects, and convergence diagnostics are compared between Fisher Scoring and Metropolis-Hastings methods.

---

## 🔧 Technologies Used
- **Python**: Core programming language for algorithm implementation.
- **Jupyter Notebooks**: For interactive exploration and reporting.
- **Libraries**:
  - `numpy`, `scipy`, `matplotlib`, `pandas`: For data manipulation and visualization.

---

## 📊 Key Findings
1. **Significant Covariates**:
   - Family history of heart disease, cholesterol levels (LDL), tobacco consumption, and age showed a statistically significant positive impact on CHD risk.
  
2. **Marginal Effects**:
   - Family history has the largest impact on CHD probability, increasing it by 15.5% (Fisher Scoring) or 11.1% (Metropolis-Hastings).
  
3. **Algorithm Comparison**:
   - Both algorithms produce consistent results for significant variables.
