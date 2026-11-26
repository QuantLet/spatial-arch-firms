<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: SARCHfirms_data

Published in: Spatial Effects in Local Productivity Volatility: A Non-Dynamic Spatial ARCH Analysis of Romanian Localities

Description: Aggregates about 9 million local unit records of the Romanian business register to locality level for the 16 annual cross sections from 2008 to 2023, matches the SIRUTA locality code to the Eurostat LAU 2021 geometry and builds the spatial weight matrices for both lattices, the full one of 3152 localities and the estimation one of the 666 localities with at least 50 firms. Every other Quantlet in this project reads the panel and the weight matrices written here.

Keywords: spatial weights, contiguity, k nearest neighbours, LAU, SIRUTA, business register, labour productivity, panel construction, Romania

Author: Codruta Mare, Mihai-Adrian Achim, Gabriela-Mihaela Muresan

Submitted: 23. Nov 2026, Mihai-Adrian Achim

Datafile: INS business register files date2008.CSV to date2023.CSV, not redistributable, plus lau2021.gpkg and nuts3.geojson from Eurostat GISCO

Output: panel_uat.rds, spatial_weights.rds, panel_uat_2008_2023.csv, panel_judet_2008_2023.csv

```
