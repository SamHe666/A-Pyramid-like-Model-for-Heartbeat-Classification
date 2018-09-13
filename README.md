# A-Pyramid-like-Model-for-Heartbeat-Classification
The source code for the paper: A pyramid-like model for heartbeat classification from ECG recordings.


Please notice that the uploaded python notebooks has maintained all the step-by-step results. For a quick result inspection and validation, just take a look at those results. If you want to reproduce the results, please follow the instruction below.


In order to reproduce the results in the paper, a few things you need to know. 
a. You need to download the raw data from the physiobank. 

b. You need to included all the python packages used in the python notebooks.

c. Once the raw data are ready, run the python notebooks in the 'Data preparation' folder to produce the cleaned data. 
When running the notebooks for data preparation, please notice that
  1. The raw data folder(s) should be placed at the same category with the pyNotebook.
  2. Reset the parameter of the ‘dataSetLoc’
  3. Specify a output location for the cleaned data. 
  4. The incart dataset could be too large for whole-loading. It is suggested that preparing the incart dataset gradually. 
  
d. Once the cleaned data are rady, run the 'Feature Extraction.ipynb' to extract features from the cleaned data and store the features as csv files. Please make sure that the data loading and saving location in the python notebook is identical with where you actually put the data. 

e. Run the 'Pyramid-like Model 2.0 - Submitted Version. ipynb' to reproduce the experient result. 

