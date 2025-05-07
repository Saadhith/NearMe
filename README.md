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
```
map.html


<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body bgcolor="#fdfaf6" text="#2c2c2c">

    <h1 align="center">
        <font color="#4B0082" size="10" face="Georgia">CHENNAI</font>
    </h1>

    <h3 align="center">
        <font color="#800000" size="6" face="Trebuchet MS">Aadhith S (212224220002)</font>
    </h3>

    <center>
        <img src="c:\Users\admin\Desktop\ca\1.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
            <area target="" alt="Saravana store" title="Saravana store" href="saravana.html" coords="542,86,669,164" shape="rect">
            <area target="" alt="Vettri theater" title="Vettri theater" href="vettri.html" coords="648,285,771,351" shape="rect">
            <area target="" alt="Vettri theater" title="Rela hospital" href="rela.html" coords="1085,215,1297,291" shape="rect">
            <area target="" alt="PVR" title="PVR" href="pvr.html" coords="476,345,643,407" shape="rect">
            <area target="" alt="AGS" title="AGS" href="ags.html" coords="306,530,490,556" shape="rect">
        </map>
    </center>

</body>
</html>




<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">Saravana Stores</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            Saravana Stores, founded in 1969, is a chain of retail stores in India. 
            It is the largest family owned business retail chain in India.[3][4] 
            It is the first store to introduce Aadi Thallupadi sale concept.

            Saravana Stores operates seven stores in Chennai, at T. Nagar, Purasawalkam, Porur, Padi, Sholinganallur, Pallavaram and 
            Usman Road.The company has mega stores in Madurai, Tirunelveli and Coimbatore. The company is growing rapidly and has 
            plans to open stores in Mumbai, New Delhi, and Bengaluru. 
            The company also operates the Saravana Selvarathinam Stores in Tirunelveli and Madurai.
        </font>
        <img src="c:\Users\admin\Desktop\18_big.jpg" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>






<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">Vettri Theatres</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            CHENNAI, India – Christie®, a leader in creating and delivering the world’s best visual and audio experiences, 
            is proud to announce that Vettri Theatres has become the first cinema in India to be equipped with Christie’s next-generation CP4325-RGB 
            RealLaser™ cinema projector.​Located in Chennai, Vettri Theatres is the most prominent cinema in the city’s Chrompet district 
            with a single-screen auditorium featuring ergonomic cushion seats, three-way stage speakers and eye-catching interiors. 
            The massive auditorium has a capacity of 776 seats and is highly popular among students, working professionals and residents in and around Chrompet district.
        </font>
        <img src="c:\Users\admin\Desktop\vettri.jpg" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>





<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7"> Rela hospital </font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            Dr. Rela Institute & Medical Centre, an international medical facility, is a quaternary care hospital. 
            We have access to cutting-edge technology and experienced, caring medical professionals. We are dedicated to fostering 
            and responding to the needs of our patients along with compassion and care. Our hospital has a facility of over 450 beds 
            inclusive of 130 critical care beds, 14 operating rooms, contemporary reference laboratories and radiology services. 
            Rela hospital is in a sprawling area of 36 acres of land located in Chromepet, Chennai, India.
        </font>
        <img src="c:\Users\admin\Desktop\rela.jpg" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>



<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">PVR</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            PVR is a popular multiplex located in Pallavaram, Chennai.
            It was originally known as  before being acquired by PVR in 2018.
            The theatre is known for its comfortable seating and high-quality sound system.
            It offers a great movie experience along with popular snacks like popcorn and cold coffee.
            Movie tickets and showtimes are available on platforms like BookMyShow.
        </font>
        <img src="c:\Users\admin\Desktop\sddefault.jpg" usemap="#MyCity" height="610" width="1450">
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>
```

## OUTPUT
![map1](https://github.com/user-attachments/assets/b6b6968b-1c56-4cce-a8b5-ce1088847998)

![map2](https://github.com/user-attachments/assets/850bf561-9a7f-4bb1-8325-131e5527c99e)

![map3](https://github.com/user-attachments/assets/a1473124-b228-4b2b-8830-d644694efd13)

![map5](https://github.com/user-attachments/assets/4f94a3ad-53da-4407-8a99-3046d5faae24)

![map6](https://github.com/user-attachments/assets/59f23c5a-5cc0-4009-a5c3-457a2633e253)


## RESULT
The program for implementing image maps using HTML is executed successfully.
