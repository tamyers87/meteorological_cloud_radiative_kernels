# Meteorological Cloud Radiative Kernels

*Meteorological cloud radiative kernels* quantify the response of top-of-atmosphere marine low cloud radiative effect to local large-scale meteorological perturbations.  They were developed by [Scott et al. (2020)](https://doi.org/10.1175/JCLI-D-19-1028.1) and applied in Myers et al. (2021).  These kernels are derived using cloud-controlling factor (CCF) analysis, which is based upon theoretical and high-resolution model evidence that marine boundary layer properties, including cloudiness, are predominantly determined by large-scale meteorological environmental factors.  In our analysis, these CCFs include sea-surface temperature (SST), estimated inversion strength (EIS), horizontal surface temperature advection (Tadv), relative humidity at 700 hPa (RH<sub>700</sub>), vertical velocity at 700 hPa (ω<sub>700</sub>), and near-surface wind speed (WS).  

The *meteorological cloud radiative kernels* are calculated by applying multi-linear regression of detrended interannual monthly anomalies of satellite-derived low cloud radiative flux onto anomalies in CCFs from a reanalysis and a standard SST dataset.  The resulting coefficients are the meteorological kernels.

Four sets of meteorological kernels are available for download, each based on a different passive satellite dataset.  For each set, the response of the radiative anomalies is the sum of shortwave and longwave radiative anomalies and further broken down into the total response, the response due to changes in low cloud amount, and the response due to changes in low cloud optical depth.  The total radiative response is overwhelmingly dominated by shortwave radiative anomalies and the sum of changes in cloud amount and optical depth.  The sign convention is such that a positive radiative anomaly is directed downward (i.e., causing planetary heating).  The cloud radiative responses represent changes exclusively due to low-level clouds and not due to changes in upper-level clouds that may reveal or obscure low-level clouds.  

The meteorological kernels are available over the oceans between 60°S and 60°N (beyond which passive satellite retrievals of low clouds are inaccurate) and at a 5° by 5° latitude-longitude resolution (the approximate minimum spatial scale large enough for the boundary layer to come into equilibrium with its environment as it is advected by the mean winds).

See [Scott et al. (2020)](https://doi.org/10.1175/JCLI-D-19-1028.1) and Myers et al. (2021) for full details.

## References

Myers, T. A., R .C. Scott, M. D. Zelinka, S. A. Klein, J. R. Norris, and P. Caldwell, 2021: Observational constraints on low cloud feedback reduce uncertainty of climate sensitivity. Under review. (contact T.A.M for submitted manuscript)

Scott, R. C., T. A. Myers, J. R. Norris, M. D. Zelinka, S. A. Klein, M. Sun, and D. R. Doelling, 2020: Observed sensitivity of low cloud radiative effects to meteorological perturbations over the global oceans. *J. Climate*, **33,** 7717–7734, https://doi.org/10.1175/JCLI-D-19-1028.1.
