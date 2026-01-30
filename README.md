<div align="center">

# 🧠 Topological Analysis of ATLAS Jet Data  
### Persistent Homology on CERN Open Data

**Applied Mathematics • High-Energy Physics • Topological Data Analysis**

</div>

---

## 🚀 Overview

This project applies **Topological Data Analysis (TDA)** to real **ATLAS Open Data** from CERN to study the global geometric structure of jet kinematics.  
Using **persistent homology**, we extract topological signatures that capture multi-scale correlations beyond standard physics observables.

The analysis is fully reproducible and runs entirely on **Google Colab**.

---

## 📊 Physics Motivation

Jets in high-energy collisions form complex structures in kinematic phase space.  
Traditional analyses focus on local statistics, while **topology captures global structure** such as clustering, loops, and voids.

This project explores:
- Connectivity and clustering of jets (H₀)
- Circular correlations in angular variables (H₁)
- Multi-scale robustness of event geometry

---

## 🧠 Methodology

1. Load **ATLAS Open Data** using `atlasopenmagic`
2. Extract jet kinematic features: `(pₜ, η, φ)`
3. Construct point clouds in phase space
4. Compute **persistent homology** using `ripser`
5. Visualize persistence diagrams
6. Interpret topological signatures physically

---

## 📁 Repository Structure

