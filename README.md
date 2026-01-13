This repository contains code to generate ionising luminosities for GIZMO simulation snapshots that use SLUG cluster particles as star particles.

The code is designed to post-process simulation outputs and compute ionising photon production rates based on stochastic stellar populations generated with SLUG.

Description

The code reads GIZMO simulation snapshots in which star particles represent stellar clusters modeled with SLUG. Using SLUG’s stellar population synthesis outputs, the code computes ionising luminosities that can be used for:

Radiative feedback studies

Comparison with observational diagnostics

Dependencies

SLUG (Stochastically Lighting Up Galaxies) must be installed separately.

SLUG documentation and source code can be found at:
https://slug2.readthedocs.io/

This repository does not include SLUG itself.

Compilation and Setup

Update the paths in the provided Makefile so that they correctly point to your local SLUG installation and required libraries.

After updating the paths, compile the code using the make command.

Usage Notes

The code is intended for use with GIZMO simulations that explicitly use SLUG cluster particles as star particles.

Ensure that the simulation snapshots and SLUG output formats are compatible with the expected input structure.

Citation

If you use this code in published work, please cite the following paper:

https://academic.oup.com/mnras/article/541/2/1106/8169323

Contact

For questions or issues related to this code, contact:

Hilay.Shah@anu.edu.au