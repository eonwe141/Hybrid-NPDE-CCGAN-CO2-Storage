# Hybrid-NPDE-CCGAN-CO2-Storage
Hybrid Neural PDE and Conditional GAN Framework for Sparse CO₂ Plume Prediction

## 📄 Publication

**Padder, A.N.** (2025). *Hybrid Neural PDE and Conditional GAN Framework for Sparse CO₂ Plume Prediction.* EarthArXiv Preprints.

[![EarthArXiv DOI](https://img.shields.io/badge/DOI-10.31223%2FX5CB4S-blue)](https://doi.org/10.31223/X5CB4S)

**Full Paper:** https://doi.org/10.31223/X5CB4S

---

## 🎯 Key Achievements

**🚀 297-Point Breakthrough:** Achieved R² = +0.0073 from catastrophic baseline collapse (R² = -297.0)

| Metric | Value | Significance |
|--------|-------|--------------|
| **R² Score** | **+0.007269** | First positive prediction on 99.70% sparse data |
| **Data Efficiency** | **9 real + 36 augmented** | Works with minimal field observations |
| **Training Time** | **12 hours (CPU)** | Accessible hardware, fully reproducible |
| **Inference Speed** | **Seconds** | Real-time operational decision support |
| **Uncertainty** | **Dual-mode UQ** | NPDE posterior + ensemble epistemic uncertainty |
| **Statistical Significance** | **p < 10⁻²¹** | Pearson correlation r = 0.081 |

**Key Innovations:**
- ✅ **10× false-positive penalty** prevents mode collapse on extreme sparsity (99.70% zeros)
- ✅ **5× physics-informed augmentation** via symmetry-based transformations
- ✅ **Dual uncertainty quantification** for regulatory compliance and risk assessment
- ✅ **CPU-only training** ensures accessibility without GPU requirements

> **Context:** Traditional ML models fail catastrophically on 99.70% zero-inflated data (R² ≈ -297). Our hybrid NPDE-CCGAN is the first to achieve positive predictive capability in this extreme sparsity regime.

---




## 📦 Trained Models

Trained model files (310 MB) are hosted on Zenodo:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17727438.svg)](https://doi.org/10.5281/zenodo.17727438)

**[Download Models from Zenodo](https://doi.org/10.5281/zenodo.17727438)**

Includes:
- Generator model (256 MB, 64M parameters)
- Discriminator model (53 MB, 4.4M parameters)
- Training history JSON

See `models/README.md` for usage instructions.

## Dataset

This work uses the **Sleipner 2019 Benchmark Model** from Equinor/CO2DataShare:

- **DOI:** [10.11582/2020.00004](https://doi.org/10.11582/2020.00004)
- **URL:** https://co2datashare.org/dataset/sleipner-2019-benchmark-model
- **License:** SLEIPNER CO2 REFERENCE DATASET LICENSE
- **Provider:** Equinor / CO2DataShare
- **Access:** Free registration required at CO2DataShare

The dataset includes:
- Simulation grid with petrophysical properties (PERMX, PORO)
- Time-lapse CO₂ saturation snapshots (1996-2010, 9 layers)
- Well data and velocity maps

See `data/README.md` for complete dataset information and download instructions.

## Acknowledgments

We gratefully acknowledge **Equinor** and **CO2DataShare** for making the Sleipner 2019 Benchmark Model publicly available for research purposes.

