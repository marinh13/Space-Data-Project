# Space-Data-Project

You can find the analysis for four seismic events performed using the **JPL mascons 0.25° dataset** in the following notebooks:

- `Project_Sumatra_2004.ipynb`
- `Project_Tohoku_2011.ipynb`
- `Project_Maule_2010.ipynb`
- `Project_IndianOcean_2012.ipynb`

Run each notebook to walk through the full processing pipeline for each event:

1. Data extraction from JPL mascons
2. PCA analysis and variance mode selection
3. Seafloor vertical displacement estimation
4. Displaced water volume calculation

> **Note:** The log-log plot code is located at the end of `Project_Maule_2010.ipynb`.

### Dataset

The analysis uses the JPL mascons dataset at 0.25° resolution:

- **Primary dataset:** `CSR_GRACE_GRACE-FO_RL06_Mascons_all-corrections.nc`, install from https://www2.csr.utexas.edu/grace/RL06_mascons.html
- **Ocean mask:** `CSR_GRACE_GRACE-FO_RL06_Mascons_v02_OceanMask.nc` — can be used to mask the data to ocean regions only.
