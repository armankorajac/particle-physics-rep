
# Particle Physics Notebooks (particle-physics-rep)

This repository showcases a collection of my Jupyter notebooks developed for projects in collider physics, emphasizing effective field theory analyses, reinterpretation of LHC searches, and machine learning applications for enhancing the sensitivity of an experimental collider search.

## 📘 Notebooks Overview

### 1. `higgs-vv-cross-sections.ipynb`
A MadGraph-integrated workflow that computes cross-sections for Higgs–vector boson processes influenced by specific bosonic operators in the SILH basis. The notebook:
- Automates cross-section calculation using MadGraph.
- Analyzes the dependence of cross-sections on operator coefficients.
- Identifies parameter space directions constrained by high-energy lepton collider measurements. These processes may enhance the current sensitivity towards these operators and they will be advertised as part of the future lepton colliders programme

### 2. `ATLAS_2101_SRD_Recast.ipynb`
A recast of the ATLAS search for events with missing transverse energy and b-jets ([arXiv:2101.12527](https://arxiv.org/abs/2101.12527)). This notebook:
- Processes simulated signal and background events generated via MadGraph/POWHEG, Pythia, and Delphes.
- Applies a baseline cut-and-count analysis.
- Constructs three Boosted Decision Trees (BDTs) to enhance signal-background separation.

### 3. `u1_digitize_plots.ipynb`
An analysis of resonant U1 leptoquark production cross-sections, comparing theoretical predictions with CMS experimental sensitivities. The notebook:
- Calculates theoretical cross-sections for U1 leptoquark production.
- Incorporates CMS sensitivity data.
- Evaluates the compatibility of theoretical models with experimental constraints.

## 🛠️ Dependencies

To run these notebooks, ensure the following tools and libraries are installed:

- [MadGraph5_aMC@NLO](https://launchpad.net/mg5amcnlo)
- [Pythia](https://pythia.org/)
- [Delphes](https://delphes.gitlab.io/)
- [ROOT](https://root.cern/)
- Python packages: `numpy`, `matplotlib`, `scikit-learn`, `xgboost`, `uproot`

Please refer to each notebook for specific setup instructions and data requirements.


## 📄 License

This project is licensed under the MIT License. 

