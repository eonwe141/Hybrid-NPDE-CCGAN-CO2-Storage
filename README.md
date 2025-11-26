# Hybrid-NPDE-CCGAN-CO2-Storage
Hybrid Neural PDE and Conditional GAN Framework for Sparse CO₂ Plume Prediction



## 📦 Pre-trained Models

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

