# GEOG370

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projections</title>
</head>
<body>
    <h1>In this project I learned how to display images in different projections</h1>
    
    <h2 style="color:rgb(216, 125, 158)">Describe in your own words how you displayed the map in different projections using QGIS</h2>
    <p>IN QGIS, I went down to the information bar on the bottom and I clicked the second most far right option to pull up the CRS window. Then in the search bar, I typed in the projection number I was looking for and clicked it and then it was applied to my map. </p>
    
    <h2>WGS84 Projection: EPSG:4326</h2>
    <h3>On this map the indicator cirlces become more distorted towards the poles and slighly distorted towards the edges of the map. The indicator circles suggest that shape and area are disorted in this projection. </h3>
    <a href=".//maps/4326.png">
    <img src=".//maps/4326.png" alt="WGS84" width='500px'>
    </a>
    <h2>Aitoff Projection: ESRI:54043 </h2>
    <h3>This projection displays the world in a more spherical way. The indicator circles shape remain mostly intact, but do become more distorted towards the poles and egges of the map. Area of the circles seems to increase towards these regions as well.  </h3>
    <a href=".//maps/54043.png">
    <img src=".//maps/54043.png" alt="Aitoff" width='500px'>
    </a>
    <h2>WGS84/Pseudo-Mercator Projection: ESPG:3857 Projection</h2>
    <h3>The indicator circles in this projection tell us that shape has been preserved since none of the circles have a distorted shape. However the indicator circles also tell us that this projection distorts area to make things seem larger towards the poles as seen with Greenland and Antarctica</h3>
    <a href=".//maps/3857.png">
    <img src=".//maps/3857.png" alt="WGS84" width='500px'>
    </a>
    <h2>Sphere_Winkel_I Projection: ESRI:53018</h2>
    <h3>Similar to the Aitoff projection, this projection displays the world in a more spherical way. Indicator circles maintain the shape relatively well, being more distorted near the poles and egdes of the map, with area also being distorted in these regions.</h3>
    <a href=".//maps/53018.png">
    <img src=".//maps/53018.png" alt="WGS84" width='500px'>
    </a>
    <h2>World_Cylindrical_Equal_Area Projection: ESRI:54034</h2>
    <h3>This projection's indicator circles are distorted in shape towards the poles, but the area seems to remain constant for each circle even when shape distorts. </h3>
    <a href=".//maps/54034.png">
    <img src=".//maps/54034.png" alt="WGS84" width='500px'>
    </a>
    <h2>World_Equidistant_Conic Projection: ESRI:54027</h2>
    <h3>In this projection, indicator circles are normal around the North Pole but as you travel out to the south pole we see distortion in the shape and area of these circles. Distance seems to be preserved in this map. </h3>
    <a href=".//maps/54027.png">
    <img src=".//maps/54027.png" alt="WGS84" width='500px'>
    </a>
    <h2>North_Pole_Azimuthal_Equidistant Projection: ESRI:102016</h2>
    <h3>In this projection, indicator circles are normal around the North Pole but as you travel out to the south pole we see distortion in the shape and area of these circles. Different from the previous map though, the projection shows a full circle with Antarctica connecting rather than having a gap at the top of the map. </h3>
    <a href=".//maps/102016.png">
    <img src=".//maps/102016.png" alt="WGS84" width='500px'>
    </a>
    <h2>Hartebeesthoek94 / ZAF BSU Albers 25E Projection: ESPG:9221</h2>
    <h3>This projection is interesting because it displays a sort of half globe view from the south pole. I think this projection said it was for South Africa and the indicator circles show that this is a good projection for the country as they are least distorted there. </h3>
    <a href=".//maps/9221.png">
    <img src=".//maps/9221.png" alt="WGS84" width='500px'>
    </a>
    <h2>Sphere_Craster_Parabolic Projection: ESRI: 53046</h2>
    <h3>This is another interesting projection because it shows the world in a sort of spherical view, but the poles are pointed. Shape and area of indicator circles seem to be distorted.  </h3>
    <a href=".//maps/53046.png">
    <img src=".//maps/53046.png" alt="WGS84" width='500px'>
    </a>
    <h2>Data used for this project</h2>
    <a href="https://www.naturalearthdata.com/http//www.naturalearthdata.com/download/10m/cultural/ne_10m_admin_0_countries.zip"> Download Natrual Earth 1:10m Cultural Vector </a>
</body>
</html>

<h2 style="color:rgb(0, 187, 255)">Walking Path from Morrison Residence Hall to the Student Entrance at the Dean Dome</p>

<h2>My Map</h2>
<h3></h3>
<a href=".//maps/Homework 2.png">
<img src=".//maps/Homework 2.png" alt="WGS84" width='500px'>
</a>
<h2>Links to Vectors</h2>
<a href="https://github.com/carojean923/GEOG370/tree/main/vectors"> vectors in geojson format </a>
<h2>Online Vector used for this project</h2>
<a href="https://opendata-townofchapelhill.hub.arcgis.com/datasets/townofchapelhill::chapel-hill-transit-bus-stops/explore"> chapel-hill-transit-bus-stops </a>
