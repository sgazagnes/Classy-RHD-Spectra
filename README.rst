Interpreting the Si II and C II Line Spectra from CLASSY Using a High-resolution Radiation-hydrodynamic Simulation
==================================================================================================================

This repository contains data, code, and plots associated with:

**Gazagnes et al. (2023), ApJ 952, 164**  
DOI: https://doi.org/10.3847/1538-4357/acda2c

Summary
-------

We investigate how mock ultraviolet (UV) spectra, generated from a single high-resolution radiation-hydrodynamic simulation, can reproduce and interpret observations of low-ionization Si II and C II metal lines in galaxies.

Specifically:

- `22,500 mock C II and Si II spectra were created from a simulated galaxy and compared to observations of 45 star-forming galaxies from the CLASSY survey.`
- `We show that the simulated spectra successfully replicate the observed line properties and shape for 87% of the CLASSY sample.`
- `We demonstrate that fluorescent emission features are sensitive to aperture losses and originate from extended regions of the ISM.`
- `Our results highlight that realistic galaxy simulations can be used to interpret complex ISM diagnostics in UV observations.`

Reproducing these results require the RHD simulation data which is not public, but available upon reasonable request.

Contents
--------

- `Animation/` — Files to create the animated figures
- `ClassySpectra/` — Observational data from the CLASSY survey
- `Measurements/` —  The csv files containing the relevant data measurements.
- `Paper/` — Contains the article pdf
- `Notebooks/` — Jupyter notebooks for making the analysis and producing the paper figures
- `Plots/` — Figures from the paper (see examples below)

Result figures:
---------------

This is an overview of the main figures in the paper, which are reproducible using the python notebooks. The paper provides the details and context for the interested reader. 

1. General properties comparison:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/VirtualGalClassyprop.png" width="85%" />
      </div>

2. Lines properties comparison:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/GlobalProp_dep.png" width="60%" />
      </div>

3.  Profile fitting:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/j0127-0619depletionVR1.png" width="80%" />
          <img src="Plots/j0337-0502COSdep_paper.png" width="80%" />
      </div>


4. Chi square comparison:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/chisquare_dep.png" width="40%" />
      </div>

4. Spatial analysis:

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/contourJ0926_SiIIV3.png" width="60%" />
      </div>

5. Physical interpretation

   .. raw:: html

      <div style="display: flex; justify-content: space-between;">
          <img src="Plots/SFR_histogram_sketch.png" width="55%" />
      </div>


Citing
------

If you use this code, data, or results, please cite:

Gazagnes et al. (2023), *The Astrophysical Journal*, 952, 164  
https://doi.org/10.3847/1538-4357/acda2c

License
-------

This work is licensed under the Creative Commons Attribution 4.0 License.
