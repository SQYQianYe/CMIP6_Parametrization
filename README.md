# CMIP6 Parametrization

## Details of 37 CMIP6 models, their cloud-convection parametrization schemes, and resolutions
| Category | Model             | Reference Atmospheric Model          | Resolution (°)       | Deep Convection            | Shallow Convection          | Cloud Microphysics            | Cloud Macrophysics            |
|----------|------------------|--------------------------------------|----------------------|----------------------------|------------------------------|------------------------------|------------------------------|
| UM       | ACCESSCM2         | UM10.6                              | 1.875 × 1.25        | Gregory and Rowntree (1990) | Gregory and Rowntree (1990) | Wilson et al. (2008)        | Wilson et al. (2008)        |
| UM   | ACCESSESM1-5      | UM7.3 GA1                          | 1.875 × 1.25        | Gregory and Rowntree (1990) | Gregory and Rowntree (1990) | Wilson et al. (2008)        | Wilson et al. (2008)        |
| UM     | KACE-1–0-G       | UM                                 | 1.875 × 1.25        | Gregory and Rowntree (1990) | Gregory and Rowntree (1990) | Wilson et al. (2008)        | Wilson et al. (2008)        |
| BCC      | BCC-CSM2-MR      | BCCAGCM3-MR                        | 1.125 × 1.125       | Modified Wu (2012)         | Hack (1994)                 | Rasch and Kristjánsson (1998) | Wu et al. (2019)           |
| BCC | BCC-ESM1         | BCCAGCM3chem                      | 2.8 × 2.8           | Modified Wu (2012)         | Hack (1994)                 | Rasch and Kristjánsson (1998) | Wu et al. (2019)           |
| EC       | EC-Earth3        | ECMWF-IFS 36r4                    | 0.7 × 0.7           | Bechtold et al. (2014)     | Bechtold et al. (2014)       | Tiedtke (1993)              | Tiedtke (1993)              |
| EC       | EC-Earth3-Veg    | ECMWF-IFS 36r4                    | 0.7 × 0.7           | Bechtold et al. (2014)     | Bechtold et al. (2014)       | Tiedtke (1993)              | Tiedtke (1993)              |
| EC       | EC-Earth3-Veg-LR | IFS cy36r4                        | 1.125 × 1.125       | Bechtold et al. (2014)     | Bechtold et al. (2014)       | Tiedtke (1993)              | Tiedtke (1993)              |
| ECHAMP   | CAMS-CSM1-0      | ECHAM5.4                          | 1.125 × 1.125       | Nordeng (1994)             | Tiedtke (1989)               | Lohmann and Roeckner (1996)              | Tompkins (2002)            |
| ECHAMP  | MPI-ESM1-2-HR   | ECHAM6.3                          | 0.9 × 0.9           | Nordeng (1994)             | Tiedtke (1989)               | Lohmann and Roeckner (1996)  | Sundqvist et al. (1989)    |
| ECHAMP  | MPI-ESM1-2-LR   | ECHAM6.3                          | 1.875 × 1.875       | Nordeng (1994)             | Tiedtke (1989)               | Lohmann and Roeckner (1996)  | Sundqvist et al. (1989)    |
| ECHAMP     | NESM3            | ECHAM6.3                          | 1.875 × 1.875       | Nordeng (1994)             | Tiedtke (1989)          | Yang & Wang (2019)              | Sundqvist et al. (1989)         |
| CAM5      | NorCPM1          | CAM4-Oslo                         | 2.5 × 1.875         | Zhang & McFarlane (1995)   | Park & Bretherton (2009)     | Rasch and Kristjánsson (1998) | Slingo (1987)       |
| CAM5  | FIO-ESM-2–0     | CAM5                              | 1.25 × 0.9          | Zhang & McFarlane (1995)   | Park & Bretherton (2009)     | Gettelman et al. (2010)      | Park et al. (2014)         |
| CAM5    | CIESM            | CIESMAM1.0 (Modified CAM5)       | 1 × 1               | Zhang & McFarlane (1995)   | Gettelman et al. (2010)          | Park & Bretherton (2009)     | Qin et al(2018)|
| CAM5     | CMCC-CM2-HR4     | CAM5                              | 1.25 × 0.9          | Zhang & McFarlane (1995)   | Park & Bretherton (2009)     | Morrison and Gettelman (2008) | Park et al. (2014)         |
| CAM5     | CMCC-CM2-SR5     | CAM5                              | 1.25 × 0.9          | Zhang & McFarlane (1995)   | Park & Bretherton (2009)     | Morrison and Gettelman (2008) | Park et al. (2014)         |
| CAM6      | E3SM-1–0        | EAM (v1.0) based on CAM5.3       | ~ 1 × 1            | Zhang and McFarlane (1995) | CLUBB              | Gettelman and Morrison (2015) | CLUBB           |
| CAM6      | E3SM-2–0        | EAM (v1.0) based on CAM5.3       | ~ 1 × 1            | Zhang and McFarlane (1995) | CLUBB, updated              | Gettelman and Morrison (2015) | CLUBB, updated            |
| CAM6     | CESM2            | CAM6                              | 1.25 × 0.9          | Zhang & McFarlane (1995)   | CLUBB                        | Gettelman and Morrison (2015) | CLUBB                      |
| CAM6     | CESM2-WACCM      | CAM6                              | 1.25 × 0.9          | Zhang & McFarlane (1995)   | CLUBB                        | Gettelman and Morrison (2015) | CLUBB                      |
| CAM6   | NorESM2-LM       | CAM-OSLO Based on CAM6           | 2.5 × 1.875         | Zhang and McFarlane (1995) | CLUBB Toniazzo et al. (2020)                        | Gettelman and Morrison (2015)        | CLUBB |
| INM      | INM-CM4-8        | INM-AM4-8                        | 2 × 1.5            | Betts (1986)               | Betts (1986)                 | Galin (1998)                  | Galin (1998)                |
| INM      | INM-CM5-0        | INM-AM5-0                        | 2 × 1.5            | Betts (1986)               | Betts (1986)                 | Tiedtke (1993)                | Tiedtke (1993)               |
| GFDL     | GFDL-ESM4         | GFDL-AM4.1                         | 1 × 1                | Zhao et al. (2018)          | Zhao et al. (2018)          | Rotstayn (1997)            | Tiedtke (1993)              |
| GFDL     | GFDL-CM4          | GFDL-AM4                          | 1 × 1                | Zhao et al. (2018)          | Zhao et al. (2018)          | Rotstayn (1997)            | Tiedtke (1993)              |
| SAM      | SAM0-UNICON       | SAM0-UNICON                       | 1.25 × 0.9           | UNICON, Park (2014)        | UNICON, Park (2014)        | Morrison and Gettelman (2008) | Park et al. (2014)     Zhang et al. (2003)         |
| SAM    | KIOST-ESM        | GFDL-AM2.0                        | 1.875 × 1.875        | UNICON, Park (2014)        | UNICON, Park (2014)        | Rotstayn (1997)            | Tiedtke (1993)              |
| SAM   | TaiESM1          | TaiAM1 based on GFDL AM2          | 1.25 × 0.9           | UNICON, Park (2014)        | UNICON, Park (2014)        | Rotstayn (1997)            | Tiedtke (1993)              |
| MIROC    | MIROC6           | CCSR AGCM                         | 1.4 × 1.4            | Chikira & Sugiyama (2010)   | Park & Bretherton (2009)    | Wilson and Ballard (1999)    | Watanabe et al. (2009)      |
| MIROC    | MIROC-ES2L       | CCSR AGCM                         | 2.8 × 2.8            | Chikira & Sugiyama (2010)   | Park & Bretherton (2009)    | Wilson and Ballard (1999)    | Watanabe et al. (2009)      |
| MRI      | MRI-ESM2-0       | MRIAGCM3.5                        | 1.125 × 1.125        | Yoshimura et al. (2015)     | Yoshimura et al. (2015)     | Lohmann et al. (2007)       | Kawai (2005) Kawai et al. (2017) |
| Can      | CanESM5          | CanAM5                            | 2.8 × 2.8            | Zhang and McFarlane (1995) | von Salzen et al. (2005)    | von Salzen et al. (2005)      | von Salzen et al. (2005)    |
| CAS      | CAS-ESM2-0       | IAPAGCM5.0                         | 1.4 × 1.4            | Tiedtke (1989)             | Park and Bretherton (2009)  | Morrison and Gettelman (2008)| Zhang et al. (2020)       |
| GAMIL    | FGOALS-g3         | GAMIL3                             | 2 × 2               | Wu et al. (2007)           | Wu et al. (2007)            | Morrison and Gettelman (2008) | Guo and Zhou (2014)        |
| GAMIL   | FGOALS-f3-L       | FAMIL2.2                           | 1 × 1               | Nordeng (1994)Tiedtke (1989)            | Nordeng (1994)Tiedtke (1989)             | Lin et al.(1983)              | Xu&Randall (1996)              |
| IPSL     | IPSL-CM6A-LR      | LMDZ6                              | 2.5 × 1.259         | Emanuel (1991) Rio et al. (2009)            | Rio and Hourdin (2008)          | Madeleine et al. (2020)      | Madeleine et al. (2020)      |

## References

- Bechtold et al. (2014): Representing equilibrium and nonequilibrium convection in large-scale models.
- Gregory and Rowntree (1990): A mass flux convection scheme with representation of cloud ensemble characteristics and stability-dependent closure.
- Wilson et al. (2008): Design and performance of a new cloud microphysics parameterization developed for the ECHAM general circulation model.
- Hack (1994): Parameterization of moist convection in the National Center for Atmospheric Research Community Climate Model (CCM2).
- Rasch and Kristjánsson (1998): A comparison of the CCM3 model climate using diagnosed and predicted condensate parameterizations.
- Wu et al. (2019): The Beijing climate center climate system model (BCC-CSM): the main progress from CMIP5 to CMIP6.
- Döscher et al. (2022): The EC-Earth3 earth system model for the coupled model intercomparison project 6.
- Nordeng (1994): Extended versions of the convective parameterization scheme at ECMWF and their impact on the mean and transient activity of the model in the tropics.
- Tiedtke (1989): A comprehensive mass flux scheme for cumulus parameterization in large-scale models.
- Tiedtke (1993): Representation of clouds in large-scale models.
- Rong et al. (2019): CAMS-CSM model and its participation in CMIP6.
- Lohmann and Roeckner (1996): Design and performance of a new cloud microphysics parameterization developed for the ECHAM general circulation model.
- Tompkins (2002): A prognostic parameterization for the subgrid-scale variability of water vapor and clouds in large-scale models and its use to diagnose cloud cover.
- Bethke et al. (2021): NorCPM1 and its contribution to CMIP6 DCPP.
- Zhang and McFarlane (1995): Sensitivity of climate simulations to the parameterization of cumulus convection in the Canadian climate center general-circulation model.
- Park and Bretherton (2009): A new two-moment bulk stratiform cloud microphysics scheme in the community atmosphere model, version 3 (CAM3).
- Rasch and Kristjánsson (1998): A comparison of the CCM3 model climate using diagnosed and predicted condensate parameterizations.
- Morrison and Gettelman (2008): A new two-moment bulk stratiform cloud microphysics scheme in the community atmosphere model, version 3 (CAM3).
- Cherchi et al. (2019): Global mean climate and main patterns of variability in the CMCC-CM2 coupled model.
- Xie et al. (2018): Understanding cloud and convective characteristics in version 1 of the E3SM atmosphere model.
- Golaz et al. (2022): The DOE E3SM model version 2: overview of the physical model and initial model evaluation.
- Danabasoglu et al. (2020): The community earth system model version 2 (CESM2).
- Volodin et al. (2021): Simulation of the present-day climate with the climate model INMCM5.
- Betts (1986): A new convective adjustment scheme. part i: observational and theoretical basis.
- Galin (1998): Parametrization of radiative processes in the DNM atmospheric model.
- Zhao et al. (2018): Structure and performance of GFDL’s CM4.0 climate model.
- Held et al. (2019): Structure and performance of GFDL’s CM4.0 climate model.
- Pak et al. (2021): Korea institute of ocean science and technology earth system model and its simulation characteristics.
- Wang et al. (2021): Performance of the Taiwan earth system model in simulating climate variability compared with observations and CMIP6 model simulations.
- Tatebe et al. (2019): Description and basic evaluation of simulated mean state, internal variability, and climate sensitivity in MIROC6.
- Chikira and Sugiyama (2010): A cumulus parameterization with state-dependent entrainment rate.
- Watanabe et al. (2009): A PDF-based hybrid prognostic cloud scheme for general circulation models.
- Wilson and Ballard (1999): A microphysically based precipitation scheme for the UK meteorological office unified model.
- Kawai et al. (2017): Interpretation of factors controlling low cloud cover and low cloud feedback using a unified predictive index.
- Yukimoto et al. (2019): The meteorological research institute earth system model version 2.0, MRI-ESM2.0.
- Swart et al. (2019): The Canadian Earth system model version 5 (CanESM5.0.3).
- CAS-ESM2-0 Zhang et al. (2020): Description and climate simulation performance of CAS-ESM version 2.
- Li et al. (2020): The flexible global ocean-atmosphere-land system model grid-point version 3 (FGOALS-g3).
- He et al. (2019): CAS FGOALS-f3-L model datasets for CMIP6 historical atmospheric model intercomparison project simulation.
- Lin et al. (1983): Bulk parameterization of the snow field in a cloud model.
- Xu and Randall (1996): A semiempirical cloudiness parameterization for use in climate models.
