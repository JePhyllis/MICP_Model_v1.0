# MICP_Model_v1.0
## 1. Introduction
Welcome to the simulation models for low-density microplastic settings in the open oceans.  The model is combined with several programs (.ipynb) explicitly processed on Jupyter Notebook.  Users are encouraged to perform a reproduction of the simulation in the manuscript or use their dataset for further exploration.  The simulation model can generate low-density microplastics with different characteristics, estimating their trajectories under various oceanic conditions and seasons.  Due to the extreme size of the database, the current program only provides two sets of global ocean physical and chemical data for simulation and reproduction under typical seasons (summer and winter, which can be acquired through Google Docs).  If users need inter-annual ocean physical and chemical data daily, please get in touch with us to provide more detailed datasets. 
## 2. System requirements
### 2.1. Software dependencies and operating systems
#### 2.1.1. Software dependencies
This model is programmed using Python 3.7 and runs in a Jupyter Notebook powered by Anaconda. The supporting databases include numpy, pandas, matplotlib, netCDF4, and Basemap.  Please make sure that these databases have been installed in your Jupyter Notebook.
#### 2.1.2. Operating systems
All the operating systems, including Windows, Mac OS, and Linux, which could run Anaconda normally can be used to process the present model. 
### 2.2. Versions the software has been tested on
Windows 10 Education
Anaconda 4.6.11
Python 3.7.3
numpy 1.21.6
matplotlib 3.5.0
pandas 1.3.5
netCDF4 1.5.8
Basemap 1.2.2
## 3. Installation guide
### 3.1. Instructions
1. Download the zip file
2. Extract the file and place the folder under the Jupyter Notebook working folder (Typically under the Windows user -- username folder)
3. Open Jupyter Notebook and the model folder should be seen in the Jupyter Notebook file interface.
4. Download the oceanic database from Google Docs and place it in the Data folder. (https://drive.google.com/drive/folders/1z980UNo9cgEpxFtLOrDoQg1u8lKwgySB?usp=sharing)
### 3.2. Typical install time on a "normal" desktop computer
Approximately 30 minutes.
## 4. Demo
### 4.1. Instructions to run on data
There are 9 programs (.ipynb) in the folder.  All necessary datasets for modeling are stored in the Data folder.  The outputs will be saved in the Output folder.  To run the model and generate Figure 1-6 in the manuscript, a specific order is given as follows:
1. Fig. 1: Open Fig_1.ipynb, press the run icon.
2. Fig. 2: Open Fig_2.ipynb, press the run icon.
3. Fig. 3: Open Random_LDMP_Generator.ipynb, press the run icon; 
    Open the  Monte_Carlo_LDMP_Traj_Fig_3.ipynb, press the run icon;
    Open the  Fig_3.ipynb, press the run icon.
4. Fig. 4: Open Fig_4.ipynb, press the run icon.
5. Fig. 5: Open Fig_5A.ipynb, press the run icon;
                Open Fig_5.ipynb, press the run icon;
6. Fig. 6:    Open Random_LDMP_Generator.ipynb, press the run icon; 
    Open the  Monte_Carlo_LDMP_Traj.ipynb, press the run icon;
    Open the  Fig_6.ipynb, press the run icon. 
### 4.2. Expected output
See Readme.pdf
### 4.3. Expected run time for a demo on a "normal" desktop computer
The expected run time depends on the number of simulated microplastics.  On a "normal" desktop computer, each program makes a run for several hours to several days.
## 5. Instructions for use
### 5.1. How to run the software on your data
Users are encouraged to use their own data to run the model.  They should place their own data in the Data folder using the exact format and data organization style as the original datasets.  The parameters within the model may need further modification to adapt to new scenarios. The model programs have provided enough instructions and references for these modifications.
### 5.2. Reproduction instructions
See 4.1.
 
