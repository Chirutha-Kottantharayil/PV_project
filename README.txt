# PV_raw_code
Written in 2022-2023 for processing PV data and remove seasonal variations (periodic in nature) in PV data. 
There are two site that are attached here - evergreen and kaneka

## File arrangement is as follows:
1. report_evergreen - calculate pr and temperature corrected pr. Also determines the degradation rate of these quantities.
2. evergreen_fft_pr_final - perform fft to remove/isolate seasonal variations
3. evergreen_degradation_rate - it is used to determine degradation of seasonal corrected pr and temperature corrected pr.
4. soiling_rdtools - is used to determine the soiling rate of pr and temperature corrected pr.


The same nomenclature is used for all the other sites. Please go through the code to understand the .csv files

Reference-
Research papers -
* Dierauf, Timothy, et al. Weather-corrected performance ratio. No. NREL/TP--5200-57991. National Renewable Energy Laboratory (NREL), Golden, CO (United States), 2013.
* C. Kottantharayil, S. De, D. M.U. and A. Kottantharayil, "A Signal Processing Method for the Reduction of Seasonal Variations in Performance Ratio Estimations of PV Powerplants," 2024 IEEE 52nd Photovoltaic Specialist Conference (PVSC), Seattle, WA, USA, 2024, pp. 0704-0707, doi: 10.1109/PVSC57443.2024.10748702.


Code and modelling - 
* pvlib - https://pvlib-python.readthedocs.io/en/stable/
* rdtools - https://rdtools.readthedocs.io/en/stable/
* dka data - https://dkasolarcentre.com.au/download?location=alice-springs
* Sandia PV modelling report - https://pvpmc.sandia.gov/modeling-guide/5-ac-system-output/pv-performance-metrics/performance-ratio/

