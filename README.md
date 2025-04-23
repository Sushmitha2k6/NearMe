# Ex04 Places Around Me
## Date: 23.04.2025

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
map.html
<html>
<head>
    <title>My City</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>CUDDALORE</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>SUSHMITHA S (212224230282)</b></font>
    </h3>
    <center>
        <img src="map1.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">

<map name="image-map">
    <area target="" alt="SILVER BEACH" title="SILVER BEACH" href="beach.html" coords="NaN" shape="circle">
    <area target="" alt="CUDDALORE PORT" title="CUDDALORE PORT" href="port.html" coords="NaN" shape="circle">
    <area target="" alt="VILLANGAPATTU SHRI MURUGAN TEMPLE" title="VILLANGAPATTU SHRI MURUGAN TEMPLE" href="temple.html" coords="465,431,NaN" shape="circle">
    <area target="" alt="THIRUVANTHIPURAM TEMPLE" title="THIRUVANTHIPURAM TEMPLE" href="thiruvanthipuramtemple.html" coords="NaN" shape="circle">
    <area target="" alt="SOTHIKUPPAM BEACH" title="SOTHIKUPPAM BEACH" href="beach2.html" coords="NaN" shape="circle">

</map>
</center>
</body>
</html>
 beach.html

 <html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>CUDDALORE</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>SILVER BEACH<sub>2</sub> Way</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Silver Beach, located approximately 2 kilometers from downtown Cuddalore in Tamil Nadu, India, is a serene coastal destination along the Coromandel Coast of the Bay of Bengal. Spanning an impressive 57 kilometers, it stands as one of the longest beaches in Asia and the second-longest on the Coromandel Coast
        </font>
    </p>
</body>
</html>

beach2.html

<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>CUDDALORE</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b><sub>SOTHIKUPPAM BEACH</sub> Way</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Sothikuppam Beach is a serene coastal destination located in the Sangolikuppam area of Cuddalore district, Tamil Nadu. Situated near the historic town of Cuddalore and the scenic Silver Beach, Sothikuppam Beach offers a tranquil environment ideal for relaxation and leisure activities. 
        </font>
    </p>
</body>
</html>

port.html

<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>CUDDALORE</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>CUDDALORE PORT<sub>2</sub> Way</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            Cuddalore Port, located in the Cuddalore district of Tamil Nadu, India, is a historically significant maritime facility situated at the confluence of the Gedilam and Paravanar rivers, opening into the Bay of Bengal. Once a bustling hub during the British colonial era, the port has experienced periods of dormancy but is currently undergoing revitalization efforts to enhance its role in regional trade and industry.​

Historical Significance
During the British colonial period, Cuddalore Port served as a vital point for maritime trade and military operations. The British established Fort St. David in 1653 near the port, which became a strategic military base. Over time, the port's prominence declined, and it transitioned to primarily supporting fishing activities.​

Current Infrastructure and Operations
Cuddalore Port is classified as a minor port and functions as an open roadstead anchorage. Vessels anchor offshore, and cargo is transferred using lighters and steel barges. The port handles a variety of cargo, including chemicals, fertilizers, agricultural produce, and other bulk commodities. Its strategic location near industrial areas and connectivity to Tamil Nadu's hinterlands support the state's economic activities.​
        </font>
    </p>
</body>
</html>

temple.html

<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>CUDDALORE</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b><sub>VILLANGAPATTU SHRI MURUGAN TEMPLE</sub> Way</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            The Villangapattu Shri Murugan Temple, also known as the Velludaiyanpattu Murugan Temple, is a revered Hindu shrine located in the village of Vilangalpattu, near Vanamadevi, in the Cuddalore district of Tamil Nadu, India. Situated along the Naduveerapattu-Vilangalpattu-Vanamadevi-Cuddalore Road, the temple is approximately 13 to 15 kilometers from Panruti and is perched atop a small hill, offering a serene and spiritual ambiance. 
        </font>
    </p>
</body>
</html>

thiruvanthipuramtemple.html

<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center">
        <font color="red"><b>CUDDALORE</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>THIRUVANTHIPURAM TEMPLE<sub>2</sub> Way</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            The Devanathaswamy Temple, also known as the Thiruvanthipuram Temple, is a revered Hindu shrine located in Thiruvahindrapuram, near Cuddalore in Tamil Nadu, India. Dedicated to Lord Vishnu, worshipped here as Devanatha Perumal, and his consort Hemabhujavalli Thayar (a form of Lakshmi), this temple is esteemed as one of the 108 Divya Desams—sacred abodes of Vishnu celebrated in the Tamil Vaishnavite canon, the Nalayira Divya Prabandham 
        </font>
    </p>
</body>
</html>

```
## OUTPUT


![alt text](<Screenshot 2025-04-23 193555.png>)
![alt text](<Screenshot 2025-04-23 193616.png>)
![alt text](<Screenshot 2025-04-23 193641.png>)
![alt text](<Screenshot 2025-04-23 193701.png>)
![alt text](<Screenshot 2025-04-23 193724.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
