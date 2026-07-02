# Irregularity–Enhanced Energy Dissipation in Metamaterials

Code to reproduce the figures in the paper, all the code is in python. If you have any questions, please email pietrozanin2027@u.northwestern.edu

See the reference below for more details. If you use this code, please cite:

- Y Zhao, P Zanin, E Stanifer, AE Motter. Irregularity-Enhanced Energy Dissipation in Metamaterials. (2026)

# Usage

- Fig2.ipynb : Code to reproduce figure 2. It optimizes the area distribution in the 1D continuum case for a certain set of values of the viscosity and the Young's modulus in both the low and high strain limit.
- Fig7.ipynb : Code to reproduce figure 7. It calculates the trajectory with the optimized heterogeneous damping as compared to the optimum homogeneous damping. 1D discrete case with fixed boundary conditions.
- Fig8.ipynb : Code to reproduce figure 8. It calculates the optimized discrete damping for different sizes. 2D discrete case with fixed boundary conditions.
- Fig9.ipynb : Code to reproduce figure 9. It calculates the optimized continuous damping for different number of modes. 2D continuous case with fixed boundary conditions.
- Geometry figures.ipynb : Code to reproduce figures 3-6. It calculates results for geometrically irregular networks under different strain. Example data are saved in data2.npy, 1D_e.npy, 1D_l.npy, 1D_e_085.npy.
# License

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

The full text of the GNU General Public License can be found in the file "LICENSE.txt".
