# BodyDimensions
Code for manuscript on feral cat body dimensions in Tasmania.
This README.txt file was generated on 20241202 by Alexandra Paton

-------------------
GENERAL INFORMATION
-------------------
Title of Dataset: A non-invasive approach to measuring body dimensions of wildlife with camera-traps: a felid field trial.

Principal Investigator: Alexandra Paton, University of Tasmania, alexandra.paton@utas.edu.au

Date of data collection: 2019, 2020, 2021.

Geographic location of data collection: Picton region, Tasmania, Australia. 


These data contain information for estimating the size of feral cats (Felis catus) using the camera-trap Cuddeback X-Change Colour Model 1279. 

--------------------
DATA & FILE OVERVIEW
-------------------- 

FocalLengthConfig.excel

The excel file 'FocalLengthConfig' contains measurements from photos of a 25cm by 25cm square at varying distances taken with the Cuddeback X-Change Colour Model 1279. The column 'Measurement' describes whether the length or height of the square was measured; 'cm' is the size of the square in metres; 'pixels' is the measurement of the square in pixels, obtained using the ruler tool in photoshop/gimp/another image editing software; 'Distance' is the distance of the square to the camera-trap in meters; 'Focal length' is the calculated focal length ((pixels x Distance)/cm). The average focal length, standard errors, and confidence intervals are calculated within this document. 

--------------------------

KnownSizeAndDistanceExperiement.csv

The csv file 'KnownSizeAndDistanceExperiement' contains the following columns: 'Name' which describes the cat silhouette measured; 'DTO' which is the measured distance of the silhouette to the camera-trap; 'OHP' is the object height in pixels; 'OLP' which is the object length in pixels; 'OHM' is the real object height in centimetres; 'OLM' is the real object length in centimetres. These data are used to validate the accuracy of our methodology. 

--------------------------

PictonCatSizeMeasurements.csv 

The csv file 'PictonCatSizeMeasurements' contains the following columns: 'Name' which describes the cat measured; 'Camera' is the camera-trap from which the image is taken; 'DTO' which is the measured distance of the cat to the camera-trap; 'OHP' is the object height in pixels; 'OLP' which is the object length in pixels; 'PhotoID' is the file name of the photograph from which the measrements are taken. These data are used to estimate feral cat dimensions in Picton, Tasmania. 

--------------------------

ControlTrialAccuracyResults.csv

The csv file 'ControlTrialAccuracyResults' contains the output of the control trial used to create the supplementary table.

--------------------------

SizeCalculations12.02.2024.r

The R file 'SizeCalculations12.02.2024' contains the calculations for feral cat size. It requires the KnownSizeAndDistanceExperiement.csv and PictonCatSizeMeasurements.csv files. 


