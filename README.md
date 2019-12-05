# MagneticField-Engine

The folder `Regression` contains reference files for regression test of magnetic field maps, for use with `MagneticField/Engine/test/regression.py`. 

Each file corresponds to one valid MF configuration. It contains a large number of points with the corresponding field value, stored as binary 32-bit floats in the format:

`px py pz bx by bz`

where `px py pz` are the global coordinates in cm, and `bx by bz` are the values of the B vector in T.
