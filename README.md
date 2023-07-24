# Repository for Cargese lecture on : "Numerical simulations of lattice models of Many-Body Localization"

[Quantum Localization & Glassy Physics](https://sites.google.com/view/qlgp-cargese-2023/home)

Cargese School, July 18th -28th, 2023

Fabien Alet (fabien.alet@cnrs.fr)

# Important Remark

Both notes and C++ codes date from 2019 and have not been re-tested again. There might be some very minor adaptations in case you use more recent version of Python or PETSc - SLEPc libraries. If you find something does not work anymore, please send an email, or better, do a PR with the correction. Thanks!


# Tutorials

There are 5 notebooks on the following topics (in order of complexity):

- Basic illustration of the Lanczos algorithm
- Static properties of the XXZ random field chain
- Dynamical properties of the XXZ random field chain
- Floquet Quantum circuits and time crystals
- Scars in the PXP and related models

These tutorials and the associated python codes have been written by Nicolas Macé, some time ago. Many thanks to him. Please drop him an email [  n [dot] mace [at] protonmail [dot] com ] if you like them and definitively contact him if you use the Python libraries in ```lib``` for your research!

See ```Setup.md``` for the setup for the Python Notebooks

# C++ codes

There are also three C++ codes that you should be able to use to perform large scale simulations of MBL problems (all for the random-field XXZ spin chain model, but pretty easy to adapt)

- Shift-invert code to get interior eigenpairs
- Krylov time evolution code
- Basic TEBD code

# Notes

There is a draft of lectures notes, prepared for a summer school in Les Houches in 2019. They have been slightly refreshed and adapted for this school. A more complete update will be done in fall 2023. Stay tuned!

