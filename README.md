# EAMPA_Mercator_MNHN
Codes produced during the joint training programme between Mercator Ocean International and the MNHN in 2026.

The various data sets used were retrieved via the CMEMS portal: https://data.marine.copernicus.eu/products?pk_vid=dd9828ea6d27d3b617881598795a876b

Other data not retrieved via this portal are listed below:
- Bathymetry: https://ibcso.org/ibcso-2025-annual-release/
- WOA23 climate temperature data: https://www.ncei.noaa.gov/access/world-ocean-atlas-2023/bin/woa23.pl
- Tracking of Adélie penguin movements: https://doi.org/10.1016/j.biocon.2025.111507

In the particular cas of the sea ice, which, for the period 2033–2025, was obtained from three different data products:
- 2003–2020: https://data.marine.copernicus.eu/product/SEAICE_GLO_SEAICE_L4_REP_OBSERVATIONS_011_009/services  =>  osisaf_obs-si_glo_phy_sic-south_my_amsr_cdr_P1D-m
- 2020–2023: https://osi-saf.eumetsat.int/products/osi-408-a
- 2023–2026: https://data.marine.copernicus.eu/product/SEAICE_GLO_SEAICE_L4_NRT_OBSERVATIONS_011_001/services  =>  osisaf_obs-si_glo_phy-sic-south_nrt_amsr2_l4_P1D-m

In the case of pelagic and benthic clustering, when using the hierarchical method with Ward’s algorithm, processing all the data points (~180,000 points) requires 52 GB of RAM.
