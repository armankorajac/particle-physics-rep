
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
- Processes simulated signal and background events generated via the usual MadGraph/POWHEG + Pythia + Delphes pipeline. Note that the ttbar background was generated using the hvq model in POWHEG. 
- Applies a baseline cut-and-count analysis following the ATLAS search.
- Constructs three Boosted Decision Trees (BDTs) for each dominant background to enhance signal-background separation, in accordance to the information given in the PhD thesis [here](https://inspirehep.net/files/1e0c3c7a061e00a13ecab29a73d7ed62).

### 3. `u1_digitize_plots.ipynb`
An analysis of resonant U1 leptoquark production cross-sections, comparing theoretical predictions with relevant CMS experimental sensitivity bounds from [this search](https://arxiv.org/pdf/2308.06143). 
The notebook:
- Calculates theoretical cross-sections for the resonant U1 leptoquark production, using a built POWHEG generator that is available [here](https://github.com/peterkrack/3rd-Lepton-Quark-Fusion).
- Has incorporated CMS sensitivity data that are found [here](https://www.hepdata.net/record/ins2687527), which are re-derived in the code for the vector leptoquark case.
- Compares the bounds that are derived through this novel production mechanism with existing bounds from other experiments sensitive to the parameters of the U1 leptoquark.
- For more information, the accompanying paper is available [via this link](https://link.springer.com/article/10.1140/epjc/s10052-024-12618-8). 

### 4. `ttbar_physlite_2101_SRD_analysis.ipynb` 

A Jupyter notebook to showcase how to efficiently extract physically relevant information from PHYSLITE, the default lightweight event format used in ATLAS analyses. It includes basic data cleaning procedures tailored for this format, functions to define physical objects according to the definitions given by ATLAS and derive important kinematical variables. 


## 🛠️ Dependencies

To run these notebooks, ensure the following tools and libraries are installed:

- [POWHEG-BOX-RES](https://powhegbox.mib.infn.it/)
- [MadGraph5_aMC@NLO](https://launchpad.net/mg5amcnlo)
- [Pythia](https://pythia.org/)
- [Delphes](https://delphes.gitlab.io/)
- [ROOT](https://root.cern/)
- Python packages: `numpy`, `matplotlib`, `scikit-learn`, `pandas`, `seaborn`, `awkward`, `uproot`, `regex`.

Please refer to each notebook for specific setup instructions and data requirements.


## 📄 License

These projects are licensed under the MIT License. 

