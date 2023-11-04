% Metadata for files "building_load.txt" and "building_GF.txt"
% Created by Josselin LE GAL LA SALLE, October 20, 2023
% TwInSolar WP4

University of La Reunion's and electricity grid operator's meters data for the buildings located in the Terre Sainte Campus 21°20'S, 55°29'E, 75m, GMT/UTC+4h
Note: Consolidated data with filtering and gap filling

Columns

All documents : 
	datetime: Timestamp, end of recording period

"ESIROI_load.txt" : 
	ESIROI_SEASOI: Electricity power demand of the ESIROI, new IUT and SEAS_OI buildings, in kW.

"CROUS_load.txt" : 
	CROUS: Electricity power demand of the CROUS buildings (Cafeteria and student residences), in kW.

"IUT_load.txt"
	Dpt_1_2: Electricity power demand of the IUT departements 1 and 2 and modular buildings, in kW.
	Dpt3_4: Electricity power demand of the IUT departements 3 and 4, in kW.
	ENERPOS: Electricity power demand of the ENERPOS building, in kW.
	Total : Total electricity power demand for the ensemble {IUT Departements 1-2-3-4+ENERPOS+modular buildings}, in kW.

"ESIROI_IUT2_HVAC.txt"
	ESIROI_IUT2_GF: Electricity power demand of the HVAC systems in ESIROI, new IUT and SEAS_OI buildings, in kW.

Filtering and checks
No filter have been applied to the data. The following verification has been done : Load data is always positive.

Gap filling
ESIROI_SEASOI: No gaps. No data before 16/06/2021 (building commissionned at this moment).
CROUS: No gaps.
Dpt_1_2: No gaps.
Dpt3_4: Gaps for some timestamps among the following dates : 2021-02-08, from 2021-07-25 16:00:00 to 2021-08-04 16:10:00,2022-12-31,2022-12-12,2021-02-14,2021-03-20,2021-08-15,2021-09-11,2021-09-29,2021-10-17,2021-12-03,2022-01-06,2022-03-30 ,2022-08-04,2022-12-02,2022-12-12. They have been filled using the analog approach, i.e. by using patterns observed from comparable dates and timestamps.
ENERPOS: Gaps for some timestamps among the following dates : 2021-02-08, from 2021-07-25 16:00:00 to 2021-08-04 16:10:00,2022-12-31,2022-12-12,2021-02-14,2021-03-20,2021-08-15,2021-09-11,2021-09-29,2021-10-17,2021-12-03,2022-01-06,2022-03-30 ,2022-08-04,2022-12-02,2022-12-12. They have been filled using the analog approach, i.e. by using patterns observed from comparable dates and timestamps.
ESIROI_IUT2_GF: Gaps for some timestamps among the following dates : 2021-07-25,2022-01-06,2022-04-21,2022-07-18,2022-12-31. They have been filled using the analog approach, i.e. by using patterns observed from comparable dates and timestamps.
