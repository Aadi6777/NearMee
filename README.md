# Ex04 Places Around Me
## Date: 

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
home.html
```
<html>
    <head>
        <title>My Home Town</title>
        </head>
        <body bgcolor="lightgreen">
        <h1 align="center">
        <font color="maroon"><b>Erode</b></font>
        </h1>
        <h3 align="center">
        <font color="red"><b>My Home Town</b></font>
        </h3>
        <hr size="3" color="purple">
        <p align="justify">
        <font face="Georgia" size="5">
           Erode is a city in the Indian state of Tamil Nadu. It is located on the banks of the Kaveri river and is 
           surrounded by the Western Ghats. Erode is the seventh largest urban agglomeration in Tamil Nadu.
           It is the administrative capital of Erode district and is administered by the Erode Municipal Corporation which was established in 2008.
        </font>
        </p>
    </body>
</html>

```
lake.html
```
<html>
    <head>
        <title>Erode</title>
        </head>
        <body bgcolor="pink">
        <h1 align="center">
        <font color="blue"><b>Erode</b></font>
        </h1>
        <h3 align="center">
        <font><b>Kolampalayam</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Kollampalayam is a locality situated near Erode, in the state of Tamil Nadu, India. 
            Erode itself is an important city known for its textile industry, and Kollampalayam is one of the smaller towns or areas in the vicinity, typically known for its rural and semi-urban characteristics.
            Kollampalayam benefits from its proximity to Erode, which is a major transportation hub. 
            Erode is well connected by road, rail, and air to other parts of Tamil Nadu and beyond.

        </font>
        </p>
    </body>
</html>


```
rodf.html
```
<html>
    <head>
        <title>KODAIKANAL</title>
        </head>
        <body bgcolor="beige">
        <h1 align="center">
        <font color=""><b>Erode</b></font>
        </h1>
        <h3 align="center">
        <font color="lime"><b>Veerapanchathiram</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Veerappanchatram is a neighbourhood locality in the city of Erode. Until 2010, it was an independent municipal administrative body after which it was officially integrated with Erode Municipal Corporation. 
            It is one of the four zones of Erode Municipal Corporation, combining 15 Wards. As of 2011, the town had a population of 84,453.
        </font>
        </p>
    </body>
</html>


```
temple.html
```
<html>
    <head>
        <title>Erode</title>
        </head>
        <body bgcolor="grey">
        <h1 align="center">
        <font color="brown"><b>Suriyampalayam</b></font>
        </h1>
        <h3 align="center">
        <font><b>My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Karatupalayam is a panchayat town in the city of Erode in the Indian state of Tamil Nadu.
            It is the Headquarters for one of the four zones of Erode Municipal Corporation. 
            In 2011, Karatupalayam was an independent panchayat town, but has since been merged with Erode during the Corporation expansion that happened in 2011. 
            The office of Karatupalayam Zone-I and city bank, Bank of Baroda,[2] is located at Javuli Nagar along the Bhavani Road, although there are other local banks in the area.
        </font>
        </p>
    </body>

```
broad.html
```
<html>
    <head>
        <title>Erode</title>
        </head>
        <body bgcolor="violet">
        <h1 align="center">
        <font color="OLIVE"><b>Karungalpalayam</b></font>
        </h1>
        <h3 align="center">
        <font color="GREEN"><b>My Home Town</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Karungalpalayam (Tamil: கருங்கல்பாளையம்) also known as (K.G. Palayam) is a commercial suburb in the city of Erode. It is located on the banks of Cauvery River, 3 kilometres (1.9 mi) to the north-east of Erode Central Bus Terminus and 1 kilometre (0.62 mi) west of Pallipalayam.
            Kalingarayan Canal runs through Karungalpalayam.The area is a mix of commercial and residential buildings.
            The economy of this urban area is primarily textile production using power looms.
        </font>
        </p>
    </body>
</html>

```
map.html
```
<html>
   <head>
    <title>My city</title>
   </head>
   <body>
    <h1 align="center">
        <font color="Orange"><b>Erode</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Aadipranav (24007963)</b></font>
    </h3>
    <center>
    <img src="mapps.png" usemap="#MyCity" height="700" width="1200">
    <map name="MyCity">
        <area shape="circle" coords="520,160,70," href="home.html" title="My home">
        <area shape="circle" coords="600,320,15" href="temple.html" title="Karatupalayam">
        <area shape="circle" coords="740,240,80,5" href="broad.html" title="Karungalpalayam">
        <area shape="circle" coords="700,200,90" href="observatory.html" title="Observatory of astronomical research">
        <area shape="circle" coords= href="lake.html" title="Man made Lake">
    </map>
</center>
   </body>
</html>

```



## OUTPUT

![alt text](<Screenshot (16).png>)

![alt text](<Screenshot (17).png>)

![alt text](<Screenshot (18).png>)

![alt text](<Screenshot (19).png>)

![alt text](<Screenshot (20).png>)

![alt text](<Screenshot (21).png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
