# Repository for Les Houches lectures on : "Numerical simulations for MBL"


[Wave Localization & Many-Body Localization in Quantum Information](https://cse.umn.edu/wave/wl-mblqi-event)

Cargese School, October 24th -28th, 2022

Fabien Alet (fabien.alet@cnrs.fr)

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

There are also three (perhaps four) C++ codes that you should be able to use to perform large scale simulations of MBL problems (all for the random-field XXZ spin chain model, but pretty easy to adapt)

- Shift-invert code to get interior eigenpairs
- Krylov time evolution code
- Basic TEBD code
- (not written yet) MPO Lindblad code
