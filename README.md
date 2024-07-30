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
