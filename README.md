# medimage-addon-ehr-medtech-evolution

__WARNING: this project has now moved to https://src.atomjump.com/atomjump/medimage-addon-ehr-medtech-evolution.git__

MedTech Evolution config for EHR Connector Add-on for MedImage



To create your own EHR connector, use this package as a template. The only files
you need to change:

1. ehrconnect.json    			- which should include queries specific to your database 
									and system tables. Make sure you have valid JSON
									(use an online json validator)
2. odbc\*             			- the ODBC driver .exe or .msi that your database requires
									 should be in here
3. medimage-installer.json    	- you should change the install commands to install your
									ODBC driver file silently
