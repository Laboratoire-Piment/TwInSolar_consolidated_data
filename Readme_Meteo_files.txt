% Metadata for files "Meteo_Terre_Sainte.txt"
% Created by Mathieu DAVID, September 22, 2023
% TwInSolar WP4

University of La Reunion's Weather station located in the Terre Sainte Campus 21°20'S, 55°29'E, 75m, GMT/UTC+4h
Note: Consolidated data with filtering and gap filling (but without quality check)

Columns
1. datetime: Timestamp, end of recording period
2. GHI: Global Horizontal Irradiance in W/m2
3. BNI: Beam Normal Irradiance in W/m2 measured on a sun tracker
4. DHI: Diffuse Horizontal Irradiance in W/m2, measured on a sun tracker
5. DBT: Dry Bulb Temperature in °C
6. RH: Relative Humidity in %
7. Ws10: Wind speed at 10m in m/s
8. Wd10: Wind direction at 10m in degrees clokwise from North (0°), East (90°), South (180°), West (270°)
9. Patmo: atmospheric pressure in mB (hPa)
10. Rainfall: Cumulative precipitation in mm

Filtering
The filters guaranty physically possible and plausible data. Filters and gap filling were applied to the 1-min data.
GHI and DHI : [0 W/m2;2000 W/m2]
BNI : [0 W/m2;1200 W/m2]
RH : [0%;100%]
DBT :[10°C;40°C]
Ws10 : [0 m/s;30 m/s] and Ws10(t+1)-Ws10(t)<10 m/s
Wd10 : [0°;360°]
Rainfall : [0 mm;100 mm]
Patmo : [900 hPa;1050 hPa]


Gap filling
GHI : No gaps thanks to multiple GHI measurements available onsite
DHI : modeled from GHI (decomposition with Erbs' model) - no valid data before 5/06/2021
BNI : modeled BNI = (GHI-DHI)/cos(zenith angle) - no valid data before 5/06/2021
RH : linear interpolation
DBT : linear interpolation
Ws10 : linear interpolation
WD10 : linear interpolation
Rainfall : 0
Patmo: linear interpolation