# WW_data_points
Repository that holds code and example figures for "Urban to Rural Shifts: Quantifying the Time Lag of SARS-Cov-2 between the Bay Area and Central Valley of California through Wastewater-Based Epidemiology

Specifically, it includes the following:
### wastewater_analysis
**1025_ww_data_peak_analysis.RMD** | R Markdown file that shows how the raw SARS-CoV-2 data was smoothed using a local polynomial regression fitting (LOESS) and 10-day moving average. Smoothed LOESS data was then used to identify the peaks for corresponding waves. This requires the [fANCOV package](https://cran.r-project.org/web/packages/fANCOVA/index.html).

**0325_wavelet_analysis.RMD** | R markdown files that quantifies that lag between the SARS-CoV-2 waves based on the 10-day smoothed moving average. This requires the [WaveletComp package](https://cran.r-project.org/web/packages/WaveletComp/index.html).

Data used for this project for "Lab 1" was dowloaded from the California Open Data Portal: <https://data.ca.gov/dataset/covid-19-wastewater-surveillance-data-california>

Up-to-date SARS-CoV-2 data can be downloaded from the California Department of Public Health (CDPH) dashboard: <https://skylab.cdph.ca.gov/calwws/>

More information about the difference between Lab 1 and Lab 2 can be found here: <https://www.frontiersin.org/journals/public-health/articles/10.3389/fpubh.2023.1141097/full> 

### clinical_analysis



California's county COVID-19 case data can be downloaded from the CalHHS website: <https://data.chhs.ca.gov/dataset/covid-19-time-series-metrics-by-county-and-state/resource/046cdd2b-31e5-4d34-9ed3-b48cdbc4be7a>

California's county COVID-19 hospitalization data can be downloaded from the California Open Data Portal: <https://data.ca.gov/dataset/covid-19-hospital-data-archived>

More information about the COVID-19 variants can be found the on the U.S. Centers for Disease Control and Prevention (CDC) website: <https://www.cdc.gov/covid/php/variants/variants-and-genomic-surveillance.html>

# Licensing

