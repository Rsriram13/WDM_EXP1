### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 07/08/2025
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
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
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
### EMPLOYEE TABLE: 
<img width="1913" height="1077" alt="Screenshot 2025-08-07 161808" src="https://github.com/user-attachments/assets/76c23712-2bb4-4dde-a77b-b967e126fde1" />
<img width="1230" height="731" alt="Screenshot 2025-08-07 161826" src="https://github.com/user-attachments/assets/24abcda4-c0be-4546-bc11-5cda63c2b2c3" />

###  WEATHER:

<img width="1919" height="1070" alt="Screenshot 2025-08-07 170315" src="https://github.com/user-attachments/assets/6bd5ca17-ef16-4757-85e2-03742de0f12e" />
<img width="1228" height="735" alt="Screenshot 2025-08-07 170329" src="https://github.com/user-attachments/assets/b8a5595a-c30a-48f6-9fdc-dbfe14dedd1f" />
 
### PREPROCESSING:

### Procedure:

#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

### EMPLOYEE TABLE: 

<img width="1255" height="943" alt="Screenshot 2025-08-07 154514" src="https://github.com/user-attachments/assets/c7f013a2-a882-4da9-bf5a-87f455aa14a0" />
<img width="1223" height="727" alt="Screenshot 2025-08-07 154533" src="https://github.com/user-attachments/assets/3e4708cd-08c1-4522-9c6a-3857d76c432d" />

### WEATHER: 

<img width="1919" height="1079" alt="Screenshot 2025-08-07 160615" src="https://github.com/user-attachments/assets/8756bc9b-ee9e-49f2-9656-059e1f06242e" />
<img width="1224" height="731" alt="Screenshot 2025-08-07 160358" src="https://github.com/user-attachments/assets/e198eaf1-5d82-4e6b-a5da-ef8ea2bcbcd7" />

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

### EMPLOYE TABLE:

<img width="1916" height="1079" alt="Screenshot 2025-08-07 154814" src="https://github.com/user-attachments/assets/24360c87-0f0d-41d7-b95e-4dae1db2a556" />
<img width="1228" height="729" alt="Screenshot 2025-08-07 154845" src="https://github.com/user-attachments/assets/8db45380-2f77-4e02-bcb5-db927d4e83c5" />

### WEATHER:

<img width="1919" height="1079" alt="Screenshot 2025-08-07 160723" src="https://github.com/user-attachments/assets/99c1cbdb-ce14-437f-880f-857f69b77a89" />

<img width="1226" height="735" alt="Screenshot 2025-08-07 160735" src="https://github.com/user-attachments/assets/e5d9abe7-dcb5-40c0-a850-d331a1c5b3e1" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

### EMPLOYEE TABLE:
<img width="1878" height="1079" alt="Screenshot 2025-08-07 161057" src="https://github.com/user-attachments/assets/12b3f95e-c1ae-483c-a453-7b2efc3393cb" />
<img width="1221" height="733" alt="Screenshot 2025-08-07 161109" src="https://github.com/user-attachments/assets/7551f64b-b9b7-4f43-92ca-bc8c9046e054" />

### WEATHER:

<img width="1919" height="1079" alt="Screenshot 2025-08-07 161008" src="https://github.com/user-attachments/assets/9155dc73-9006-429a-8d3e-b9c1e60d5974" />
<img width="1225" height="735" alt="Screenshot 2025-08-07 161027" src="https://github.com/user-attachments/assets/2c152a9b-b551-40bf-a8f6-4450e015ef23" />

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
