# Ex04 Places Around Me
## Date: 23-04-2025
# Name: Gowtham N
# Reg No:212222220013

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Neyveli</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Gowtham N (212222220013)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="_self" alt="home" title="home" href="open link.html" coords="908,410,972,448" shape="rect">
    <area target="_self" alt="vadakumelur" title="vadakumelur" href="vadamelur.html" coords="450,202,68" shape="circle">
    <area target="_self" alt="Durai Amman Temple" title="Durai Amman Temple" href="temple.html" coords="391,602,23" shape="circle">
    <area target="_self" alt="Ayyanar lake" title="Ayyanar lake" href="lake.html" coords="1002,82,1035,68,1037,102,1071,80,1120,69,1147,99,1148,173,1029,190,990,156,999,116" shape="poly">
</map>
        </center>
    </body>
</html>
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Neyveli</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Gowtham N (212222220013)</b></font>
        </h3>
        <center>
            <img src="lake.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="" title="" href="" coords="" shape="rect">
</map>
        </center>
    </body>
</html>

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Neyveli</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Gowtham N (212222220013)</b></font>
        </h3>
        <center>
<img src="temple.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="" title="" href="" coords="" shape="rect">
</map>
        </center>
    </body>
</html>

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Neyveli</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Gowtham N (212222220013)</b></font>
        </h3>
        <center>
            <img src="vadamelur.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="" title="" href="" coords="" shape="rect">
            </map>
        </center>
    </body>
</html>



```

## OUTPUT
![image](https://github.com/user-attachments/assets/4a15da16-2d86-46d9-8cdd-5ffcb0be3483)

![image](https://github.com/user-attachments/assets/97f919f0-7d8e-4e2e-a7a2-d7a9b75ff31c)


![image](https://github.com/user-attachments/assets/18825124-4e79-42ee-8dcc-72fa3892b68d)


![image](https://github.com/user-attachments/assets/e01cfb99-fa3b-431d-a827-e571caac9269)


## RESULT
The program for implementing image maps using HTML is executed successfully.
