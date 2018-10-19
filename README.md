# ScientificProgramming3
MSB1015 Scientific Programming 
Assignment 3: Parallel Computing

In this assignment, a Structure Data File (SDF) that is published on PubChem (PubChem Assay AID 624202) is used to test the duration of parallel computing when using an increasing number of the computer's cores. A R Markdown notebook (Assignment_3.Rmd) is created to integrate both the code and output of the analysis. The notebook requires a .sdf file that can be downloaded from this repository (aid624202.sdf file) or from PubChem. Users need to download this files and change the working directory in the script such that the data file can be accessed. Running the script in RStudio will install and load the required packages and import the data of the .sdf file iteratively to create a list of molecules. Next, the molecular descriptor will be calculated in parallel using an increasing number of the computer's cores. The duration of this process will be stored and the final plot provides an overview of how long the calculation of molecule descriptors per number of used cores takes. The R Markdown notebook can also be opened as an .html file which can be downloaded from this repository (Assignment_3.html).
