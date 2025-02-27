# NAME : NAVEEN KUMAR T
# REG NO : 212223220067
# EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
## DATE: 15:02:2024
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```--------------
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

Training Data Set -> Employee Table:
![305007794-638fc39b-613b-44b4-85b3-0207efb1af96](https://github.com/user-attachments/assets/540af336-4c41-427f-aaa0-56a6afc59b20)

![305007826-b0ad7eeb-28c8-45c3-8de9-3597b1833d7f](https://github.com/user-attachments/assets/2bdab0f7-7f8d-4f05-a97b-64550faa8a48)



<img width="180" alt="304777690-ea53e36a-6fd5-49ca-9421-bafdb8b7c1b6" src="https://github.com/820NaveenKumar208/WDM_EXP1/assets/154746066/88ee6250-47b0-430d-8935-164de4a5f3f3">

Training Data Set-> Weather Table
<img width="169" alt="304777823-d06c775d-e8c3-4883-8afd-a2b681b6f022" src="https://github.com/820NaveenKumar208/WDM_EXP1/assets/154746066/f90ccd8d-6459-40e7-b0a1-ee8f1d9887a3">



## PREPROCESSING
## Procedure:
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
Employee Table after adding new attribute ADDRESS:

![356813968-b79667d3-71ad-4fd7-b7d0-4a54bd93e28e](https://github.com/user-attachments/assets/66eea1d0-d566-4586-b69e-97d9b17e2e5c)


Weather Table after adding new attribute CLIMATE:
![356813973-303919fd-10a4-4c56-98b9-112aedd7511f](https://github.com/user-attachments/assets/331686d2-8600-4e1b-881b-c16a8f2c72d0)




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
Employee Table after removing attributes SALARY, GENDER:
![356814117-db6977ba-ab09-4ac2-9ed9-bd6ca295aee4](https://github.com/user-attachments/assets/a5ee9fc0-e3d1-490a-9656-5702ae99ddb7)


Weather Table after removing attributes WINDY, PLAY:
![305008264-f7a9fe7d-f55a-49f5-89af-9deebd840e67](https://github.com/user-attachments/assets/e568086a-9397-499d-8186-7474309a346b)


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
Employee Table after Normalizing ID, EXP, PHONE:

![303835822-0838cfcb-ccd5-490b-81a2-e647e9dd6feb](https://github.com/user-attachments/assets/903ca2c2-b8f2-4ea2-a7e7-308098d9b195)


Weather Table after Normalizing TEMPARATURE, HUMIDITY:
![303836066-0f55c327-2f2f-44d0-87b8-5a7c57b7f2bd](https://github.com/user-attachments/assets/2b884928-154b-4bc7-a874-7e8707488fd4)



 

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
