# RGB Optimizer Comparison in R

This repository contains the implementation and comparison of optimization algorithms applied to a logistic regression model using RGB image features.

## 📁 Project Structure

- `data/`: Contains the input datasets and merged RGB feature-label data.
- `part-a/`: Feature extraction scripts and image preprocessing from Project 1.
- `part-b/`: Optimization algorithm comparison using multiple solvers (`BFGS`, `L-BFGS-B`, `CG`, `Nelder-Mead`).
- `part-b.Rmd`: Main R Notebook performing optimizer comparison and evaluation.
- `part-b.nb.html`: Rendered notebook output (knit from RStudio).

## 🧠 Project Overview

This project builds on RGB features extracted from image panels and compares four optimization algorithms to minimize logistic loss across three classification tasks:
- 🌳 Tree
- 🐾 Animal
- 👳‍♂️ Mythological Character

## ✅ Objectives

- Apply `optimx` solvers (`BFGS`, `L-BFGS-B`, `CG`, `Nelder-Mead`) to logistic regression.
- Compare training losses and prediction accuracy per method.
- Visualize optimizer loss paths and evaluate model performance.

## 🚀 How to Run

1. Clone this repo.
2. Open `part-b.Rmd` in RStudio.
3. Knit the document or run chunks to perform optimizer comparison.

## 📊 Final Output

- Comparative training loss plots.
- Optimizer-specific classification accuracy tables.
- Summary insights on algorithm effectiveness.

---

Let me know if you'd like a `LICENSE` file or if you need help adding GitHub Pages/docs!
