SageMath
========

GravesLab tools in the Sage Computer Algebra System

Worksheets:
Dataset Fitting - example that demonstrates fitting a model to data with adjustable parameters
Manipulating Data - example that demonstrates importing data from a text file
Data Preprocessing - first attempt at the functions that do all of the work

----------
start up Sage
(pass: p45)

https://github.com/GravesLab/SageMath

/media/brandon/Data/Repos/SageMath

navigate into each datafolder, run Sagemath/batch files/batch-rename
remove any extraneous garbage files
----------
reset()
root = '/mnt/data/Repos/SageMath/'
fxn_lib = root + 'libraries/spectral_analysis.sage'
attach fxn_lib

myDataFolder = root + 'datasets/ftir_01/'
myFitSpecies = ['N2O']

plotTimeSeries(myDataFolder,myFitSpecies)



	

