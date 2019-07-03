# Mortgage-Valuation
Valuation of Mortgage Pools using Cox Ingersoll Ross model and Richard and Roll Prepayment Model

LIBOR.csv contains the daily 1 Month LIBOR from 2000 to 2018

WeeklyMR.csv contains the Weekly Average Mortgage Rates from 2000 to 2018

Valuation Process:

	1. Calibrate CIR Process
			MAXIMUM LIKELIHOOD ESTIMATION OF THECOX-INGERSOLL-ROSS PROCESS: THE MATLAB IMPLEMENTATION
			----Kamil Klad´ıvko1
	2. Simulate Short Rates Using Calibrated Parameters
	
	3. Simulate Cash Flows Using Richard Roll Model (Prepayment Model)
	
	4. Calculate Present Value, Duration and Convexity for the Mortgage Pool
