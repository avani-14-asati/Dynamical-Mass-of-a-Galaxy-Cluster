In this project we have used galaxy cluster data from Sload Digital Sky Survey (SDSS) to estimate
 various parameters like the velocity dispersion and the dynamical mass of the cluster

#Technologies used
Python ,Jupyter Notebook, Matplotlib,Pandas,Numpy


# How to Run
1. Open `Dynamical_Mass.ipynb`
2. Run all cells sequentially
3.Make sure u have Matplotlib,Pandas and NumPy installed on your device


1. The original dataset contained multiple objects with measured spectroscopic redshift
(specz) values.
2. A histogram and boxplot of redshift values was plot which revealed the general
distribution of redshifts in the cluster field.
3. 90 Galaxies were filtered out by removing any galaxies 3 standard deviations away from
the mean redshift
4. The mean cluster redshift was calculated as 0.07989, indicating the relative velocity of
the cluster due to cosmic expansion.
5. The dynamical mass was estimated using the virial theorem formula: M=3⋅σ2⋅RG
6. The resulting dynamical mass of the cluster was calculated as approximately.
M≈4.35×10^45 s^2 kg/m^3 solar masses. This is within the expected range for massive
galaxy clusters.
7. The large mass estimate suggests that the cluster is very massive and gravitationally
bound.
8. This dynamical mass is typically much larger than the luminous mass (from visible
stars), hinting at the presence of dark matter — a key conclusion in cluster astrophysics.

