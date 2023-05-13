# PMSM_Elec.Mech.ParameterEstimation
This repository demonstrates the model-based synchronous machine electrical & mechanical parameter estimation where the magnetic cross-coupling saturation and speed ripple caused by extra signal excitation is well considered. Eevn so, the torque ripple caused is used as a excitation in mechanical equation to estimate the inertia and damping term.

# Code Structure
This work is based on MATLAB2019b

# Citing
The DEKF-based electrical parameter observer is first introducted at:

```
  @ARTICLE{10083049,
  author={Liu, Zirui and Kong, Wubin and Fan, Xinggang and Qu, Ronghai},
  journal={IEEE Transactions on Industrial Electronics}, 
  title={Online Multi-Parameter Observation of IPM Machine with Reconstructed Nonlinear Small-Signal Model Based on Dual EKF}, 
  year={2023},
  volume={},
  number={},
  pages={1-10},
  doi={10.1109/TIE.2023.3260353}}
```