# AntPicnic
This repository contains all the R scripts and data files used in my master's thesis on the Ant Picnic project. All scripts are RMarkdown files with extensive descriptions of the coding process. The structure of this repository matches the structure of the R project I used for all of my thesis. Therefore, the scripts should be usable as is if the entire repository is copied into a new R project.

The R folder contains the scripts described in the Supplementary Materials section of my thesis, namely:  

* S2. The script used to randomize the sampling schedule of my fieldwork, under the file name "location_randomization.Rmd"  
* S3. The script used to extract the microclimate logger measures taken during each Ant Picnic experiment from the raw data files and calculate a mean value of each measured variable for each experiment. The file name is "climate_logger_data_extraction.Rmd”.  
* S4. The script used for the entire data analysis process, under the file name "data_analysis.Rmd”. The script is broken down into sections, with section 0 encompassing data loading and cleaning, preparing the data frames for analysis, and producing descriptive results figures and tables. Section 1 is the statistical analysis of research quesiton 1, including the correlation analysis, exploratory data analysis, model selection, model assumptions check, and plotting model results. Sections 2 and 3 respectively encompass the analysis of research questions 2 and 3, with the same components as section 1 without the correlaiton analysis but with the addition of post-hoc tests. A knitted version of the script representing the final version I used for my results is also given in HTML format.


The images folder contains all figures produced during the data analysis process (S4). 

The data folder contains all raw data files used for the data analysis process as well as all the microclimate logger raw data files.
