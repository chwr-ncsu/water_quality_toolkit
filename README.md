# Toolkit for Assessing Performance in Concentration Regression Models
This is a repository for the Toolkit for Assessing Performance in Concentration Regression Models(TAP-CRM) 

Developer Contact:

Dominic Libera

dalibera@ncsu.edu

North Carolina State University

2501 Stinson Drive Raleigh, NC 27695-7908

Version: 1.0 	Last Updated: 10/31/17

Requirements and Notes:
-	This toolkit was built in MATLAB® Version R2017a. Using the GUIDE interface builder in MATLAB
- The (.m) and (.fig) files were compiled as a windwows application (.exe)
- The (.exe) application uses the RunRcode.f to run the WRTDS model in R Studio.
- The working directory for the .R code is set to the directory of the downloadeded file (e.g. C:/Program Files/TAP_CRM) using the Installer Application found in TAP_CRM_Download.zip.  If you wish to run the code in another directory the working directory should be changed in the .R code named "tap_crm_wrtds_model.R".
- NOTE: The TAP-CRM executable will create subdirectories for storing loadest and wrtds calibration files so make sure the application has permisson to write in the folder and subfolders.
- NOTE: If the user wants to change the block size of the resampling method they will have to do so inside the (.m) file, found in the TAP_CRM_Files.zip.
