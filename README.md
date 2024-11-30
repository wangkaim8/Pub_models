# Pub_models

Cecal.model.3D- A 3D model of central California constructed by Alternating adjoint tomography of ambient noise and telesemisc P waves.

Reference: Wang, K., Yang, Y., Jiang, C., Wang, Y., Tong, P., Liu, T. and Liu, Q., 2021. Adjoint tomography of ambient noise data
and teleseismic P waves: Methodology and applications to central California. Journal of Geophysical Research: Solid Earth, 126(6), p.e2021JB021648.


Model format: 

longtitude  latitude  depth (m) vs (m/s)        vp (m/s)        rho (g/cm3)

-121.800002 34.751637 0.000000  3483.203        5819.202        2706.369

-121.772694 34.751365 0.000000  3483.357        5821.479        2708.980

-121.745387 34.751087 0.000000  3483.185        5823.716        2711.970

-121.718080 34.750802 0.000000  3482.110        5825.709        2715.422

...

Note: 1. The original 3D model is build on a finite-element mesh with irregular Cartesian XYZ grid points (minimum distance of 500 m) using the SPECFEM3D software.
      2. I convert the irregular grid to an regular grid with a increment of 2.5 km and finally convert XYZ to lon/lat.
