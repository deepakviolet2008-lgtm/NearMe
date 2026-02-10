# Ex04 Places Around Me
## Date: 10.02.2026

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
Image Map.html

<html>
    <head>
        <title>Image map</title>
    </head>
    <body>
        <h1>KRISHNAGIRI</h1>
        <h3>DEEPAK B (25018314)</h3>
        <img src="Screenshot 2026-02-09 105523.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Krishnagiri" title="Krishnagiri" href="Krishnagiri.html" coords="893,470,1042,521" shape="rect">
    <area target="_blank" alt="Government boys hr sec school" title="Government boys hr sec school" href="Govt_Boys_school.html" coords="1238,679,1240,726,1482,734,1509,689,1475,668" shape="poly">
    <area target="_blank" alt="Government girls hr sec school" title="Government girls hr sec school" href="Govt_Girls_school.html" coords="" shape="rect">
    <area target="_blank" alt="Government Museum" title="Government Museum" href="Govt_museum.html" coords="1648,575,83" shape="circle">
    <area target="_blank" alt="SIDCO Industrial Estate" title="SIDCO Industrial Estate" href="SIDCO.html" coords="83,171,164,127,317,121,352,182,188,210" shape="poly">
</map>
    </body>
</html>

Govt_Boys_school.html

<html>
    <head>
        <title>KRISHNAGIRI</title>
    </head>
    <body  align="center" bgcolor="red">
        <h1>KRISHNAGIRI</h1>
        <h3>GOVT BOYS SCHOOL</h3>
        <p>The Government Boys Higher Secondary School in Krishnagiri (specifically near Courts, Newpet) is a long-standing public institution established in 1868, offering Tamil-medium education from grades 6 to 12. Managed by the Department of Education, it is located in an urban area, featuring 12 classrooms, a library with approximately 3,000 books, and a playground. </p>
    </body>
</html>

Govt_Girls_school.html

<html>
    <head>
        <title>KRISHNAGIRI</title>
    </head>
    <body  align="center" bgcolor="pink">
        <h1>KRISHNAGIRI</h1>
        <h3>GOVT GIRLS SCHOOL</h3>
        <p>The Government Girls Higher Secondary School in Krishnagiri, located near the Taluk Office (PIN: 635001), is a key educational institution dedicated to empowering young women in the district. As part of Tamil Nadu's state-run,,it focuses on delivering quality education, fostering extracurricular skills, and ensuring safe, inclusive learning environments for female students. </p>
    </body>
</html>

Govt_museum.html

<html>
    <head>
        <title>KRISHNAGIRI</title>
    </head>
    <body  align="center" bgcolor="#D1FFBD">
        <h1>KRISHNAGIRI</h1>
        <h3>GOVT MUSEUM</h3>
        <p>Established in 1993 on Gandhi Road, the Government Museum in Krishnagiri is a district-level institution focusing on the art, archaeology, and culture of the region. It showcases artifacts from the Paleolithic to modern periods, featuring significant collections of Neolithic tools, Megalithic pottery, hero stones, and local tribal artifacts, offering a glimpse into the area's rich history.  </p>
    </body>
</html>

SIDCO.html

<html>
    <head>
        <title>KRISHNAGIRI</title>
    </head>
    <body  align="center" bgcolor="#DFC5FE">
        <h1>KRISHNAGIRI</h1>
        <h3>SIDCO</h3>
        <p>SIDCO (Tamil Nadu Small Industries Development Corporation) in Krishnagiri operates multiple industrial estates (including main Krishnagiri, Polupalli, Uthangarai, and Bargur) that serve as vital hubs for MSMEs. Strategically located near NH-44, they support industries like engineering, agro-processing, textiles, and auto components, providing infrastructure, sheds, and plots.</p>
    </body>
</html>

Krishnagiri.html

<html>
    <head>
        <title>KRISHNAGIRI</title>
    </head>
    <body  align="center" bgcolor="sky blue">
        <h1>KRISHNAGIRI</h1>
        <p>Krishnagiri, known as the "Mango Capital of India" and the "Gateway of Tamil Nadu," is a historically significant district in Tamil Nadu, famed for producing over 300,000 tons of mangoes annually. Named "Black Hill" (Krishna-Giri) due to its vast black granite deposits, it is an agricultural hub with a rich, ancient past stretching back to the Paleolithic age. </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
