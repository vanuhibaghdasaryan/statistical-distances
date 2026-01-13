# Statistical Distances (Վիճակագրական հեռավորություններ)

Master’s research project (Yerevan State University, 2025) on **statistical distances and divergences** between probability distributions, including theory (definitions, properties, inequalities), applications, and numerical experiments.

## Contents
- 📄 **Paper (PDF):** `paper/Statistical_Distances.pdf
- 🧪 **Experiments (Notebook):** `experiments/Stat_dist.ipynb

## Distances & Divergences Covered
- **Kullback–Leibler (KL) divergence**
- **Jensen–Shannon (JS) divergence**
- **Total Variation (TV) distance**
- **Hellinger distance**
- **Wasserstein (W1) distance**

## What’s in the Paper
### 1) Definitions & Key Properties
Definitions for discrete/continuous settings and key properties (non-negativity, symmetry when applicable, boundedness, convexity).

### 2) Applications
Use cases in statistics and machine learning (goodness-of-fit, variational methods, GANs/WGANs, optimal transport, robust statistics).

### 3) Relationships & Inequalities
Includes key bounds such as:
- **Pinsker’s inequality:** relates KL divergence and Total Variation distance
- Bounds connecting **TV** and **Hellinger** distances

### 4) Numerical Experiments
- Synthetic sample from **N(0,1)**
- Compare **empirical distribution** vs **fitted Normal** (estimated μ, σ²)
- Compute KL, JS, TV, Hellinger, Wasserstein distances
- **Bootstrap** for stability + 95% confidence intervals
- Study effect of **sample size** on distances

Example results (n = 5000): TV ≈ 0.0327, Hellinger ≈ 0.0307, JS ≈ 0.00095, KL ≈ 0.00377, Wasserstein ≈ 0.0223.

## Language
The full paper is written in **Armenian**. 

## Author
**Vanuhi Baghdasaryan**  
Yerevan State University — MSc Applied Statistics & Data Science (2025)
