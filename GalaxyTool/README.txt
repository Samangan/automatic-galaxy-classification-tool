Galaxy Tool
	README

Name: Automatic Galaxy Classification in the De Vaucouleurs System of the Sloan Digital Sky Survey
Class: Capstone 
Date: Spring 2012
Authors: Harry Hull and Craig Williams
--------------------------------------------------------------------------------------------
RUNNING:
	The exe file located in /GalaxyTool4/WinForms/bin/Debug/ named WinForms.exe can be run in a windows envinoronment in order to start the application.


BUILDING:
	Opening the /GalaxyTool4/GalaxyTool 4.sln file will launch Visual Studio 2010. To Build the application first clean and rebuild the whole solution, and then do a normal build on the Winforms project only. This will avoid any errors about not having WinForms dependencies compiled. The project can now be ran and compiled from Visual Studio if desired

USING:
	To use Galaxy Tool start the application and then either load an existing classifier or create a new one (train a new classification tree or use an existing one from earlier). After training the accuracy and classifications from training will be displayed. The user can view the results of each galaxy in the top left of the application. To classify new data click the "Load Files" button and navigate to the folder containing the images to be classified. Galaxy Tool will all of the images up into batches of available memory to be used so do not worry about classifying too many images at once. In Project/GalData.zip there is the data of the 30,000 galaxies from the SDSS used to generate the final classification data.

RESULTS:
	In /GalaxyTool4/Results/ the final results can be found in Final Classifications.txt. This file stores the RA, and DEC of each galaxy classified in /galData/ folder and the classification determined by galaxy tool.

	In /GalaxyTool4/Results/SampleOutput/ galaxies are categorized into class folders to visually see the classifications.


CODE ACCESS:
	Permanent Code access can be found at https://github.com/Samangan/automatic-galaxy-classification-tool .


DATA ACCESS:
	EFIGI TRAINING:
		Project/GalTool4/galaxies/
	SDSS GALAXIES USED IN THIS PROJECT:
		Project/GalData.zip (to fit this project on the flash drive)