EX1 Creaion of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
DATE: 08.02.24
Name: sarvesh.s
Reg.No:212222230135
AIM:
To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing

PROCEDURE:
Open Start -> Programs -> Accessories -> Notepad
Type the following training data set with the help of Notepad for Employee Table.
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
After that the file is saved with .arff file format.
Minimize the arff file and then open Start -> Programs -> weka-3-4.
Click on weka-3-4, then Weka dialog box is displayed on the screen.
In that dialog box there are four modes, click on explorer.
Explorer shows many options. In that click on ‘open file’ and select the arff file
Click on edit button which shows employee table on weka.
OUTPUT:
EMPLOYEE DATA


WEATHER DATA


PREPROCESSING
Procedure:
1) Add -> Pre-Processing Technique:
Start -> Programs -> Weka-3-4 -> Weka-3-4
Click on explorer.
Click on open file.
Select Weather.arff file and click on open.
Click on Choose button and select the Filters option.
In Filters, we have Supervised and Unsupervised data.
Click on Unsupervised data.
Select the attribute Add.
A new window is opened.
In that we enter attribute index, type, data format, nominal label values for Climate.
Click on OK.
Press the Apply button, then a new attribute is added to the Weather Table.
Save the file.
Click on the Edit button, it shows a new Weather Table on Weka.
OUTPUT:
EMPLOYEE DATA


WEATHER DATA


2) Remove -> Pre-Processing Technique:
Start -> Programs -> Weka-3-4 -> Weka-3-4
Click on explorer.
Click on open file.
Select Weather.arff file and click on open.
Click on Choose button and select the Filters option.
In Filters, we have Supervised and Unsupervised data.
Click on Unsupervised data.
Select the attribute Remove.
Select the attributes windy, play to Remove.
Click Remove button and then Save.
Click on the Edit button, it shows a new Weather Table on Weka.
OUTPUT:
EMPLOYEE DATA


WEATHER DATA


Normalize -> Pre-Processing Technique:
Start -> Programs -> Weka-3-4 -> Weka-3-4
Click on explorer.
Click on open file.
Select Weather.arff file and click on open.
Click on Choose button and select the Filters option.
In Filters, we have Supervised and Unsupervised data.
Click on Unsupervised data.
Select the attribute Normalize.
Select the attributes temparature, humidity to Normalize.
Click on Apply button and then Save.
Click on the Edit button, it shows a new Weather Table with normalized values on Weka.
OUTPUT:
EMPLOYEE DATA


WEATHER DATA


RESULT:
Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
