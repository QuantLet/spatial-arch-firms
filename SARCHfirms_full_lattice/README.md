<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: SARCHfirms_full_lattice

Published in: Spatial Effects in Local Productivity Volatility: A Non-Dynamic Spatial ARCH Analysis of Romanian Localities

Description: Checks that nothing is lost by restricting the analysis to the 666 localities with at least 50 firms. Moran I on the squared residuals is recomputed on the full queen contiguity lattice of 3152 localities, and the model itself is attempted on that lattice with sparse matrices and warm starts. The estimation does not converge after three hours against 84 seconds on the reduced lattice, which is the feasibility statement reported in the paper. Produces the last two rows of Table 2.

Keywords: full lattice, queen contiguity, sparse matrices, convergence, feasibility, Moran I, sample selection, Romania

Author: Codruta Mare, Mihai-Adrian Achim, Gabriela-Mihaela Muresan

Submitted: 23. Nov 2026, Mihai-Adrian Achim

Input: panel_uat.rds and spatial_weights.rds from SARCHfirms_data

Output: moran_retea_completa.csv, sparch_full_lattice.csv

```
