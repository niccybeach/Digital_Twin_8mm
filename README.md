# Digital_Twin_8mm
The code required for the 8mm plastic bead digital twin to function along with MFiX and Power Automate
## MFiX_file_edits
These files learn from the training data from multiple inverse problem simulations on MFiX. They then use this data to predict 
the various DEM paramters in the title of the notebook. For example, MFiX_file_edit_'insert parameter here'_8mm.ipynb. 
## Overall mfx file edit
This notebook takes all of the predictions from the seperate MFiX file edit files and combines them so that the MFiX input file (PhysTwin+bucket.rev1,mfx) can be 
executed in the MFiX application.
