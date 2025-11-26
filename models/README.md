# Trained Models

## Download from Zenodo

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17727438.svg)](https://doi.org/10.5281/zenodo.17727438)

**Download link:** https://doi.org/10.5281/zenodo.17727438

## Files Included

1. **sleipner_ccgan_generator_weighted.keras** (256 MB)
   - Generator model (63.9M parameters)
   - Input: permeability, porosity, time
   - Output: CO₂ saturation maps

2. **sleipner_ccgan_discriminator_dual.keras** (53 MB)
   - Dual-output PatchGAN discriminator (4.4M parameters)

3. **training_history_improved.json** (7 KB)
   - Training metrics for 200 epochs (loss curves, R² progression)

## Usage

``````

## Citation

If using these models, cite:

Padder, A. (2025). Hybrid Neural PDE and Conditional GAN Framework for Sparse CO₂ Plume Prediction - Trained Models and Code. Zenodo. https://doi.org/10.5281/zenodo.17727438

- **Dataset:** Sleipner 2019 Benchmark (DOI: 10.11582/2020.00004)
- **Training:** 200 epochs, R² = 0.007269 (see paper/readme for details)
