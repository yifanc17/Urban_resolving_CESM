# Urban_resolving_CESM

### Introduction
This repository is supplementary to the manuscript “Importance of spatially-continuous urban representation in advancing high-resolution urban-resolving Earth system modeling”.

### Data
Simulation outputs, post-processed data and validation datasets are publicly available at [Figshare](https://doi.org/10.6084/m9.figshare.29640872).

### Scripts
Scripts for generating the main text figures are provided below:

| Plot     | Title   | Simulations |
| -------- | ------- | ----------- |
| [Figure2](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure2_CTRL_TEST_surf.ipynb) | Comparison of CTRL and USURF parameters |    NA      | 
| [Figure3](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure3_LST_vs_MODIS_JJA.ipynb) | Validation of modeled vs. MODIS LST in JJA | CTRL_UHR,USURF_UHR |
| [Figure4](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure4_LST_vs_MODIS_CONUS_JJA.ipynb) | Validation of modeled vs. MODIS LST in JJA | CTRL_UHR,USURF_UHR |
| [Figure5](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure5_T2M_TMIN_TMAX_JJA.ipynb) | Comparison of CTRL and USURF T2M in JJA | CTRL_UHR,USURF_UHR |
| [Figure6](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure6_urban_stations_JJA.ipynb) | Validation of modeled vs. observed T2M & RH in JJA | CTRL_MR,USURF_MR |
| [Figure7](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure7_PLUMBER_taylor_diagram.ipynb) | Comparison of CTRL,USURF,DETAILED plumber simulations | SP_CTRL_1km,SP_USURF_1km,SP_DETAILED_1km |
| [Figure8](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure8_PLUMBER_longterm_avg.ipynb) | Comparison of CTRL,USURF,DETAILED plumber simulations | SP_CTRL_1km,SP_USURF_1km,SP_DETAILED_1km |
| [Figure9](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure9_spatial_analysis.ipynb) | Spatial scaling analysis | USURF_LR,USURF_MR,USURF_HR,USURF_UHR |
| [Figure10](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure10_PCA_info_loss_driver.ipynb) | Drivers of information loss | USURF_LR,USURF_MR,USURF_HR,USURF_UHR |
| [Figure11](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/01_simulation_eval/Figure11_PLUMBER_xScale.ipynb) | Impact of spatial resolution on surface fluxes | SP_USURF_LR,SP_USURF_MR,SP_USURF_UHR,SP_USURF_1km |


Scripts for generating the supplementary figures are provided below: 

| Plot     | Title   | Simulations |
| -------- | ------- | ----------- |
| [FigureS1](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS1_Jackson_33Regions.ipynb) | 33 urban regions defined by [Jackson et al. (2010)](https://doi.org/10.1080/00045608.2010.497328) |    NA      | 
| [FigureS2](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS2_PCT_URBAN_adjust.ipynb) | Adjusted PCT_URBAN in 3.5km surfdata |    NA      | 
| [FigureS3](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS3_PLUMBER_sites.ipynb) | 21 Urban-PLUMBER sites | NA |
| [FigureS4](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS4_LST_vs_MODIS_DJF.ipynb) | Validation of modeled vs. MODIS LST in DJF | CTRL_UHR,USURF_UHR |
| [FigureS5](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS5_LST_vs_MODIS_CONUS_DJF.ipynb) | Validation of modeled vs. MODIS LST in DJF  | CTRL_UHR,USURF_UHR |
| [FigureS6](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS6_T2M_TMIN_TMAX_DJF.ipynb) | Comparison of CTRL and USURF T2M in DJF | CTRL_UHR,USURF_UHR |
| [FigureS7](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS7_urban_stations_DJF.ipynb) | Validation of modeled vs. observed T2M & RH in DJF | CTRL_MR,USURF_MR |
| [FigureS8](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS8_cooling_trend_CONUS.ipynb) | Comparison of CTRL and USURF LST and T2M in JJA | CTRL_UHR,USURF_UHR |
| [FigureS9](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS9_TSA_diurnal_range.ipynb) | Comparison of CTRL and USURF diurnal T2M range | CTRL_UHR,USURF_UHR |
| [FigureS10](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS10_urban_stations_KS_JJA.ipynb) | KS test of modeled vs. observed T2M & RH in JJA | CTRL_UHR,USURF_UHR |
| [FigureS11](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS11_urban_stations_R2_JJA.ipynb) | Validation of modeled vs. observed T2M & RH in JJA | CTRL_MR,USURF_MR |
| [FigureS12](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS12_PLUMBER_bias_by_sites.ipynb) | Comparison of CTRL,USURF,DETAILED plumber simulations by sites | SP_CTRL_1km,SP_USURF_1km,SP_DETAILED_1km |
| [FigureS13](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/03_supplements/FigureS13_PLUMBER_bias_xScale_by_sites.ipynb) | Impact of spatial resolution on surface fluxes by sites| SP_USURF_LR,SP_USURF_MR,SP_USURF_UHR,SP_USURF_1km |

Code modifications for running single-point simulations at Urban-PLUMBER sites are documented in [02_plumber_code_mod](https://github.com/yifanc17/Urban_resolving_CESM/blob/master/02_plumber_code_mod). Lines between !KO were modified by [Dr. Keith Oleson](https://github.com/olyson).
