# Digital_Twin_8mm
The code required for the 8mm plastic bead digital twin to function along with MFiX and Power Automate
## MFiX_file_edits
These files learn from the training data from multiple inverse problem simulations on MFiX. They then use this data to predict 
the various DEM paramters in the title of the notebook. For example, MFiX_file_edit_'insert parameter here'_8mm.ipynb. 
## Overall mfx file edit
This notebook takes all of the predictions from the seperate MFiX file edit files and combines them so that the MFiX input file (PhysTwin+bucket.rev1,mfx) can be 
executed in the MFiX application. The predictions made in this section were made with a linear regression.
### Notes
The two above files need to be run in Power Automate before the MFiX simulation is run in the MFiX application. The files below are run after the MFiX simulation
is complete. 
## CSV converter
This notebook extracts the output monitor readings after the MFiX simulation has been conducted so that the results from the DEM input parameter predictions can be analysed. After it exctracts the files from MFiX, it can proccess them and add them to different files where we can look at a summary of the input parameters for the respective DEM run and its output average and maximum velocities. 
## Filtered V at exit region
This file is a by product of the CSV_converter that is then used later in subsequent procesesses. 
