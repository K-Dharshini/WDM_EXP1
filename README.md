### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing

### DATE:

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

# Training Data Set employee Table

![image](https://github.com/user-attachments/assets/d199d507-01aa-485c-93e2-310d4ff95019)

# Training Data Set Weather Table

![image](https://github.com/user-attachments/assets/cdbcc6a1-acb5-427a-9b0b-78432131bfdd)

### PREPROCESSING

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

# Weather Table after adding new attribute CLIMATE:

![image](https://github.com/user-attachments/assets/e2121b10-61a6-42ba-8cf9-f67d08e635b2)

# Employee Table after adding new attribute ADDRESS:

![image](https://github.com/user-attachments/assets/58064f3d-a9d7-4640-97c8-151f42bd5ed0)

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

# Weather Table after removing attributes WINDY, PLAY: 

![image](https://github.com/user-attachments/assets/8a1da718-bf51-4cd9-a3fe-d33f681253bd)

# Employee Table after removing attributes SALARY, GENDER:

![image](https://github.com/user-attachments/assets/d4b813bf-0188-4d4a-a6c4-42d6b0afab68)

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

# Weather Table after Normalizing TEMPARATURE, HUMIDITY:

![image](https://github.com/user-attachments/assets/d62b6818-d333-433f-9b81-b1b98ac9f4b4)

# Employee Table after Normalizing ID, EXP, PHONE:

![image](https://github.com/user-attachments/assets/b2574be7-6fb9-47b4-8d83-980942e8f7ec)

### RESULT: 
Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
