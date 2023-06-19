# GP
Gaussian process interpolation/extrapolation for Gaia spectra.

compare.ipynb makes some timing comparisons for (scalar, univariate) functions with adjustable number of samples. Shows the importance of fast solvers...

gaia_spectra.ipynb is a very basic skeleton of notebook for interpolation on gaia spectra. For now it will aim at interpolating only a scalar variable (norm of the spectra).
Once we have a (fast) gaussian process regressor handy for multi-variate, vector output functions, we will use it on Gaia spectra.

