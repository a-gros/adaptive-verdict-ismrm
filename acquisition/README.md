# Acquisition

`NV.scheme` is the diffusion acquisition scheme used for the simulations in this repository.

It contains:

- 153 total measurements;
- 22 reference measurements;
- 131 diffusion-weighted measurements used as the ordered MLP input.

Notebook 01 converts NV.scheme into the numerical format required for simulation. The converted file is generated automatically when the notebook is run.

The scheme contains acquisition parameters only, not patient images or patient metadata.
