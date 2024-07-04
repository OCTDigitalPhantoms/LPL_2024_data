The OCT numerical phantom used in the following paper:

Alexey A Zykov, Alexander L Matveyev, Lev A Matveev, Maher Assaad and Vladimir Y Zaitsev
Computationally efficient adaptive optimization of vector-method parameters for phase-sensitive strain estimation in optical coherence elastography
Published 2 July 2024 
Laser Physics Letters, Volume 21, Number 8
https://doi.org/10.1088/1612-202X/ad552c

Filenames correspond to figure numbers.
Structure: Three-dimensional double precision complex-valued array (depth, X, Scans). 
Two B-scans before (:,:,1) and after (:,:,2) applying strains.

The OCT digital phantom cloud-based simulation tool can be found on the OpticElastograph platform: https://www.opticelastograph.com/

When using for your purposes, please cite the above-mentioned paper.

Acknowledgments:
Generation of simulated datasets and numerical testing was supported by the Ajman University, Grant No 2023-IRG-ENIT-44.

----------------------
Figure5.mat: File Description

For the simulation of the OCT image, the following parameters were used:

Number of A-scans: N_Ascans = 200

Lateral distance between the pixel centers: Xpx = 16 µm

Axial distance between the pixel centers in air: Hpx_air = 8 µm

Central wavelength of the OCT source spectrum in air: La0_air = 1.3 µm

Refractive index of the tissue: n = 1.3

Number of pixels in the axial direction: 251

Number of scatterers: Nsc = 40160

Full depth of the image: H = (Hpx_air / n) * (N - 1) = 1.54 mm

There are 2 consecutive images acquired at the same position (there is no motion of the OCT probe along the axis perpendicular to the B-scan plane).

There are 3 distinct layers in the image with the following axial sizes:

L1: H / 6

L2: H / 6

L3: 2 * H / 3

Strain level in L1 is approximately 1.01 * 10^-2; in L2, it is approximately 9.1 * 10^-4; and in L3, it changes in the range [-5.46 * 10^-3 : 2.73 * 10^-3].

----------------------

