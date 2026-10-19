# Electrochemical & Structural Characterization of Antimony Trioxide as an Electrodes Materials

This repository showcases experimental materials characterization and Python-based data automation tools developed for high-performance metal-ion battery applications. 

##  1. Materials Characterization (XRD)
Phase purity and crystal structure of the synthesized Antimony Trioxide active material were evaluated using X-Ray Diffraction (XRD). The pattern confirms the successful formation of the orthorhombic phase, highlighted by the dominant (121) lattice orientation.

<p align="center">
  <img src="figures/xrd_pattern.png" width="700" alt="XRD Pattern">
</p>

##  2. Electrochemical Performance (CV & GCD)
Electrochemical kinetics and charge storage behavior were assessed using Cyclic Voltammetry (CV) and Galvanostatic Charge-Discharge (GCD) testing:
* **Cyclic Voltammetry:** Illustrates clear reduction/oxidation peaks and excellent electrochemical reversibility across multi-cycle sweeps.
* **Galvanostatic Cycling:** Tracks specific capacity retention and voltage plateaus over extended cycles.

<p align="center">
  <img src="figures/cv_curves.png" width="48" alt="CV Curves">
  <img src="figures/gcd_profiles.png" width="48" alt="GCD Profiles">
</p>

##  3. Python Automation Toolkit
To bridge experimental data with digital engineering workflows, custom Python scripts are provided to automate:
- Peak identification and Scherrer crystallite size estimation from XRD data.
- Power-law b-value kinetic analysis (i = a \cdot v^b) from CV scan rates.

##  Tech Stack & Libraries
- **Language:** Python
- **Libraries:** NumPy, SciPy, Matplotlib
- **Instruments / Software:** OriginPro, EC-Lab