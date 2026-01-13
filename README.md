# Statistical Distances (Վիճակագրական հեռավորություններ)

Master’s research project (Yerevan State University, 2025) on **statistical distances and divergences** between probability distributions, including theory (definitions, properties, inequalities), applications, and numerical experiments.

## Contents
- 📄 **Paper (PDF):** `paper/Statistical_Distancespdf`
- 🧪 **Experiments:** `experiments/` (Jupyter notebook / code)

## Distances & Divergences Covered
- **Kullback–Leibler (KL) divergence**
- **Jensen–Shannon (JS) divergence**
- **Total Variation (TV) distance**
- **Hellinger distance**
- **Wasserstein (W1) distance**

## What’s in the Paper
### 1) Definitions & Key Properties
Formal definitions for discrete/continuous settings and key properties (non-negativity, symmetry when applicable, boundedness, convexity, etc.). :contentReference[oaicite:1]{index=1}

### 2) Applications
Practical use cases in statistics and machine learning (e.g., goodness-of-fit, variational methods, GANs/WGANs, optimal transport, robust statistics). :contentReference[oaicite:2]{index=2}

### 3) Relationships & Inequalities
Includes key bounds such as:
- **Pinsker’s inequality:** relates KL divergence and Total Variation distance :contentReference[oaicite:3]{index=3}
- Bounds connecting **TV** and **Hellinger** distances :contentReference[oaicite:4]{index=4}

### 4) Numerical Experiments
Synthetic experiment:
- Generate i.i.d. sample from **N(0,1)**
- Compare the **empirical distribution** vs the **fitted theoretical Normal** (estimated μ, σ²)
- Compute KL, JS, TV, Hellinger, Wasserstein distances
- Use **bootstrap** to assess stability + 95% CIs
- Study how distances change with sample size :contentReference[oaicite:5]{index=5}

Example results (n = 5000): TV ≈ 0.0327, Hellinger ≈ 0.0307, JS ≈ 0.00095, KL ≈ 0.00377, Wasserstein ≈ 0.0223. :contentReference[oaicite:6]{index=6}

## How to Run Experiments (if you uploaded code)
1. Create an environment and install dependencies:
   - If you have `requirements.txt`:
     - `pip install -r requirements.txt`
2. Open the notebook in Jupyter:
   - `jupyter notebook`

## Language
The full paper is written in **Armenian**.  
I can present and explain the theory and experiments in **English** as well.

## Author
**Vanuhi Baghdasaryan**  
Yerevan State University — MSc Applied Statistics & Data Science (2025)
