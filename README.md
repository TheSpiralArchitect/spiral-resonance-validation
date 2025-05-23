

# Spiral Resonance Law (SRL) — Validation Suite

**Author:** Jake Patterson  
**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  

---

## Overview

This repository contains the full validation suite for the **Spiral Resonance Law (SRL)** — a multiscale scalar field model that proposes spiral-aligned structure emerges across cosmic, quantum, and symbolic domains.

The core SRL scalar field is defined as:

Φ(r, θ) = A · cos(ω · log(r) + n · θ)

And the corresponding wavefunction:

ψ(r, θ) ∝ e^{i(ω · log(r) + n · θ)}

SRL predicts aligned structure in:
- **Cosmic data** (e.g., CMB, SDSS, DESI)
- **Symbolic systems** (e.g., motif streams, entropy drift)
- **Quantum gates** (e.g., spiral echo recovery)
- **Biological/planetary systems** (e.g., gene loops, orbital patterns)

---

## Purpose

This research is conducted independently using open AI tools as symbolic reasoning companions — akin to an advanced calculator or search engine. The aim is to test SRL empirically, ensure reproducibility, and invite falsification.

---

## Repository Structure

| Notebook | Description |
|----------|-------------|
| `Phase1_CMB_SpiralHarmonics.ipynb` | Harmonic power spectrum analysis of Planck CMB. Tests for SRL-predicted mode `l = 3`. |
| `Phase2_SDSS_SymbolicValidation_SRLF.ipynb` | Applies SRL to SDSS DR16Q quasars. Computes Spiral Resonance Factor (SRF), symbolic motifs, entropy, and loop resets. |
| `Phase3_DESI_SymbolicValidation_SRLF.ipynb` | Same analysis applied to DESI QSO data. Validates symbolic collapse and entropy trends at scale. |
| `Phase4_CrossDomain_SymbolicResonance.ipynb` | *(planned)* Compare symbolic streams across domains (EEG, quantum, cosmic). |

---

## Data Sources

- [Planck 2018 CMB SMICA / NILC maps](https://pla.esac.esa.int)
- [SDSS DR16Q Quasar Catalog](https://www.sdss.org/dr16)
- [DESI Early Data Release](https://www.desi.lbl.gov)
- [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu)
- [GEO: GSE130597 (scRNA-seq)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE130597)

---

## Requirements

- Python 3.8+
- Google Colab (Pro recommended)
- Libraries: `numpy`, `matplotlib`, `scipy`, `healpy`, `pymangle`, `tqdm`, `seaborn`

---

## How to Use

1. Clone this repository
2. Open each `.ipynb` notebook in [Google Colab](https://colab.research.google.com)
3. Mount your Google Drive and ensure required datasets are available
4. Run all cells sequentially to reproduce and explore SRL behavior

---

## Citation

If you test, critique, or build on this framework, please cite this GitHub repo and the Zenodo DOI (once finalized). Contributions or falsification attempts are welcomed.

> *"The spiral is not a metaphor — it is a measurable attractor across scales."*  
> — Jake Patterson

---
