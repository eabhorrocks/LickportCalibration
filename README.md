# LickportCalibration
 Repo for performing reward volume calibration of lickports/pinch valves.
 Useful for  and ensuring individual lickports dispense similar reward volumes.
 
 Protocol:
 1) The Bonsai workflow is used to repeatedly open pinch valves with a range of user-defined open times and record the resulting weight of reward dispensed.
 2) A script is then used to generate a lookup table that enables conversion of reward weight to pinch valve open time.
 3) A Bonsai node is provided that maps reward weight to pinch valve open time.
