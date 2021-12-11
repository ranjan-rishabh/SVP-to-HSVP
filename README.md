# SVP-to-HSVP
Project for CSE206A: Lattice Algoithms

This repository contains a python implementation of SVP-HSVP reduction.

[SVP_to_HSVP.ipynb](SVP_to_HSVP.ipynb) contains the SageMath implementation for the reduction. This works for floating-point lattice bases and is our general working implementation.

[SVP_to_HSVP_FPLLL.ipynb](SVP_to_HSVP_FPLLL.ipynb) contains the numpy and FPLLL implementation of the reduction but it suffers from FPLLL limitation of working on only integer lattice bases (thus it will not work in most cases). This can be used to find the sublattice orthogonal to given vector (L<sub>0</sub>).
