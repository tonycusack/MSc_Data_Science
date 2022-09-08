# MSc_Data_Science
 All the code required by the researcher in order to duplicate findings. 

# 1. Collecting data.
As outlined in the appendices, first download CyKit, the Emotiv app, OpenVibe designer and OpenVibe acquisition server. When you are ready, instructions to pass to the command prompt, on Windows, are shown in the instructions.txt file. 

# 2. Pre processing
All filtering and Independent Component Analysis (ICA) of the data is performed through the MATLAB tool, EEGLAB. After completing steps shown in the dissertation, the data can be exported as a csv. 

# 3. Analysis
Following the 'master_notebook' in the experiments folder should allow the user to follow through the code. This includes importing data, separating data, and testing models. The 'knn' notebook allows analysis of distance metrics utilised by the kNN. 
