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
index.html:
<!DOCTYPE html>
<html>
    <head>
        <title>
            Map of my home
        </title>
    </head>
    <body>
        <img id="Image-Maps-Com-image-maps-2023-07-24-154826" src="homemukesh.jpg" border="0" width="1037" height="768" orgWidth="1037" orgHeight="768" usemap="#image-maps-2023-07-24-154826" alt="" />
        <map name="image-maps-2023-07-24-154826" id="ImageMapsCom-image-maps-2023-07-24-154826">
        <area  alt="" title="Home" href="home.html" shape="rect" coords="320,284,483,370" style="outline:none;" target="_self"     />
        <area  alt="" title="Teastall" href="teastall.html" shape="rect" coords="168,132,331,218" style="outline:none;" target="_self"     />
        <area  alt="" title="Icecream" href="icecream.html" shape="rect" coords="228,501,391,587" style="outline:none;" target="_self"     />
        <area  alt="" title="Mahal" href="mahal.html" shape="rect" coords="573,184,736,270" style="outline:none;" target="_self"     />
        <area  alt="" title="gym" href="gym.html" shape="rect" coords="853,449,1009,542" style="outline:none;" target="_self"     />
        <area shape="rect" coords="1035,766,1037,768" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
        </map>
    </body>
</html>


## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
