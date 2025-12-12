# Ex04 Places Around Me
## Date:8/12/25
### Ref:25018612

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
<font color="red"><b>Dindigul</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Jenoviya D (25014196)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Rock fort" title="Rock fort" href="Rockfort.html" coords="378,532,615,377" shape="rect">
    <area target="_blank" alt="Nagal nagar" title="Nagal nagar" href="Nagal Nagar.html" coords="1028,668,1187,750" shape="rect">
    <area target="_blank" alt="Railway colony" title="Railway colony" href="Railway.html" coords="1439,516,1574,616" shape="rect">
    <area target="_blank" alt="Theater" title="Theater" href="Theater" coords="1220,324,1461,209" shape="rect">
    <area target="_blank" alt="Ponram Briyani" title="Ponram briyani" href="P
    onram.html" coords="668,621,878,726" shape="rect">
</map>
</center>
</body>
</html>

Theater.html

<!DOCTYPE html>
<html>
<head>
    <title>Theater</title>
</head>
<body bgcolor="black">
    <h1 align="center">
        <font color="gold"><b>Theater</b></font>
    </h1>
    <h3 align="center">
        <font color="red"><b>Entertainment at its Best</b></font>
    </h3>
    <hr size="3" color="gold">
    <p align="justify">
        <font face="Georgia" size="5" color="white">
            Cineplex offers a world-class movie experience with comfortable seating, 
            high-quality sound systems, and the latest blockbusters. 
            Families and friends gather here to enjoy entertainment on the big screen. 
            With snacks, laughter, and thrilling moments, Cineplex is the perfect 
            destination for fun and relaxation.
        </font>
    </p>
</body>
</html>

Nagal Nagar.html

<!DOCTYPE html>
<html>
<head>
    <title>Nagal Nagar</title>
</head>
<body bgcolor="lightyellow">
    <h1 align="center">
        <font color="maroon"><b>Nagal Nagar</b></font>
    </h1>
    <h3 align="center">
        <font color="darkgreen"><b>A Place of Culture and Community</b></font>
    </h3>
    <hr size="3" color="brown">
    <p align="justify">
        <font face="Georgia" size="5" color="black">
            Nagal Nagar is a lively neighborhood known for its friendly community 
            and cultural diversity. It is surrounded by shops, markets, and temples 
            that reflect tradition and modern lifestyle together. 
            Festivals and gatherings bring people closer, making Nagal Nagar 
            a warm and welcoming place for everyone.
        </font>
    </p>
</body>
</html>

Ponram Biriyani.html

<!DOCTYPE html>
<html>
<head>
    <title>Ponram Biryani</title>
</head>
<body bgcolor="lightyellow">
    <h1 align="center">
        <font color="maroon"><b>Ponram Biryani</b></font>
    </h1>
    <h3 align="center">
        <font color="darkred"><b>A Feast of Flavor</b></font>
    </h3>
    <hr size="3" color="orange">
    <p align="justify">
        <font face="Georgia" size="5" color="black">
            Ponram Biryani is famous for its rich aroma and authentic taste. 
            Prepared with fragrant basmati rice, succulent pieces of meat, 
            and a perfect blend of spices, it offers a mouthwatering experience. 
            Customers from near and far come to enjoy the flavorful biryani 
            that leaves a lasting impression on the taste buds.
        </font>
    </p>
</body>
</html>

Railway Colony.html

<!DOCTYPE html>
<html>
<head>
    <title>Railway Colony</title>
</head>
<body bgcolor="lightgrey">
    <h1 align="center">
        <font color="darkblue"><b>Railway Colony</b></font>
    </h1>
    <h3 align="center">
        <font color="green"><b>A Community by the Tracks</b></font>
    </h3>
    <hr size="3" color="blue">
    <p align="justify">
        <font face="Georgia" size="5" color="black">
            Railway Colony is a peaceful neighborhood built near the railway lines, 
            providing homes to railway employees and their families. 
            The colony features well-planned streets, parks, and community spaces, 
            making it an ideal place for families to live. 
            Its close-knit community and serene environment offer comfort and convenience 
            to all its residents.
        </font>
    </p>
</body>
</html>

Rockfort.html

<!DOCTYPE html>
<html>
<head>
    <title>Rock Fort</title>
</head>
<body bgcolor="lightgoldenrodyellow">
    <h1 align="center">
        <font color="maroon"><b>Rock Fort</b></font>
    </h1>
    <h3 align="center">
        <font color="darkgreen"><b>Historic Landmark and Scenic Viewpoint</b></font>
    </h3>
    <hr size="3" color="brown">
    <p align="justify">
        <font face="Georgia" size="5" color="black">
            Dindigul Rock Fort is a majestic hilltop fort that stands as a symbol 
            of history and architectural brilliance. The fort offers panoramic views 
            of the surrounding city and hills. Visitors can explore the ancient walls, 
            temples, and pathways while enjoying the natural beauty and historic charm 
            of this remarkable landmark.
        </font>
    </p>
</body>
</html>
```

## OUTPUT
![alt text](6.png)
![alt text](1.png)
![alt text](2.png)
![alt text](3.png)
![alt text](4.png)
![alt text](5.png)
## RESULT
The program for implementing image maps using HTML is executed successfully.
