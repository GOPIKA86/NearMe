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

<html>
    <body>
        <h1>THIRUVANNAMALAI</h1>
        <h3>GOPIKA A (24900767)</h3>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Arunachale
</html>swar temple" title="Arunachaleswar temple" href="temple.html" coords="552,630,772,699" shape="rect">
    <area target="" alt="Annamalai hill" title="Annamalai hill" href="hill.html" coords="1342,581,312" shape="circle">
    <area target="" alt="Arulmigu Om Vaya Lingam" title="Arulmigu Om Vaya Lingam" href=" Lingam.html" coords="240,101,96" shape="circle">
    <area target="" alt="Kubera Lingam" title="Kubera Lingam" href="Sivan Lingam.html" coords="426,173,635,107" shape="rect">
    <area target="" alt="hotel Arunachala" title="hotel Arunachala" href="hotel.html" coords="451,464,484,563,804,603" shape="poly">
</map>
</body>
hill.html
<html>
    <body bgcolor="cyan">
        <h1>THIRUVANNAMALAI</h1>
        <h3>Annamalai hill</h3>
        <p>
            A Jain site with over 2000 years of history, Tirumalai - literally, “the holy mountain” - is situated 51km from Tiruvannamalai. Dating back to at least the 9th Century, Tirumalai has been an important Jain center since ancient times.
        </p>
    </body>
</html>
hotel.html
<html>
    <body bgcolor="pink">
        <h1>THIRUVANNAMALAI</h1>
        <h3>hotel Arunachala</h3>
        <p>
            Hotel Arunachala, Thiruvanamalai, is an excellent choice to stay for pilgrims and also for tourists from all over the world. The hotel stands tall only 200 meters from the temple and is indeed a wonderful stay with six types of well-appointed rooms. Each room is classy and beautiful. They are spacious with a good decor and great furnishing. It also comes with top-notch amenities that makes your stay even more comfortable.
        </p>
    </body>
</html>
lingam.html
<html>
    <body bgcolor="blue">
        <h1>THIRUVANNAMALAI</h1>
        <h3>Arumilgu Om Vaya Lingam </h3>
        <p>
            The air is lighter at Vayu Lingam, offering mental clarity. It's like a mental fog lifts.Vayu governs air and intellect, bringing wisdom and focus. Pray for clarity and direction, especially if you're facing difficult decisions. 
        </p>
    </body>
</html>
temple.html
<html>
    <body bgcolor="yellow">
        <h1>THIRUVANNAMALAI</h1>
        <h3>Arunachaleswar Temple</h3>
        <p>
            It was constructed during the 9th century by the Chola dynasty. It has experienced a variety of expansions and renovations of the architectural changes of South India. The temple is devoted to Lord Shiva, illustrating the fire element as part of the Pancha Bhoota Sthalams.  
        </p>
        </body>
</html>
sivan lingam.html
<html>
    <body bgcolor="red">
      <h1> THIRUVANNAMALAI</h1>
      <h3>Kubera lingam</h3>
      <p>
        Positioned in the northern part of the route, the Kubera Lingam temple worships Lord Kubera, the god of wealth and prosperity. It is believed that praying at this temple can bring financial abundance and overall prosperity.
      </p>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (8).png>)
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (10).png>)
![alt text](<Screenshot (11).png>)
![alt text](<Screenshot (12).png>)
![alt text](<Screenshot (13).png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
