% Metadata for files "building_PV.txt"
% Created by Mathieu DAVID, October 31, 2023
% TwInSolar WP4

Simulated production of the existing PV plants installed on the roofs of the ENERPOS, ESIROI and dept. 1 and 2 buildings in the Terre Sainte Campus 21°20'S, 55°29'E, 75m, GMT/UTC+4h
Note: The production of photovoltaic installations is recorded. However, 2 power plants (ENERPOS and ESIROI) belong to private operators and the recorded data presents numerous gaps and outliers. To solve these problems, we generated synthetic time series of photovoltaic production with the python pvlib library. The time series were calibrated to match the measured data.

All documents : 
	datetime: Timestamp, end of recording period

"ESIROI_PV.txt": PV production of the ENERPOS building, in kW. Key figures: Total peak power 46.9kWp, monocrystalline silicon modules, Array 1 over-roof well ventilated (slope 9°, 14° North-East) 21.06 kWp, Array 2 over-roof well ventilated (slope 9°, 194° South-West) 33.696 kWp, commissioning year 2021


"ESIROI_PV.txt": PV production of the ESIROI building, in kW. Key figures: Total peak power 99.935 kWp, polycrystalline silicon modules, Array 1 rack mounted (slope 30°, 14° North-East) 67.94 kWp, Array 2 roof mounted (slope 30°, 103° South-East) 31.995 kWp, commissioning year 2008

"Dpt_1_2_PV.txt": PV production of the Dpt. 1 and 2 buildings, in kW. Key figures: Total peak power 11.385 kWp, polycrystalline silicon modules, Array 1 rack mounted (slope 21°, 0° North) 11.385 kWp, commissioning year 2006


Filtering and checks
No filter have been applied to the data. The PV production generated with the consolidated weather data.

