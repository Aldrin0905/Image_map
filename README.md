# Ex04 Places Around Me
# Date:
# Reg no: 212223240005
# Name:S.Aldrin
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
    <html>
    <head>
      <title>My City</title>
    </head>
    <body>
      <h1 align="center">
        <font color="red"><b>Tambaram</b></font>
      </h1>

      <h3 align="center">
        <font color="blue"><b>Harshat</b></font>
      </h3>
    <center>
        <img src="map.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
          <area shape="rect" coords="700,250,850,400" href="home.html" title="Home">
          <area shape="circle" coords="570,230,45" href="road.html" title="Muduchur road">
          <area shape="circle" coords="640,200,30" href="lake.html" title="Tambaram Lake">
          <area shape="circle" coords="1120,360,25" href="garden.html" title="GG Garden">
          <area shape="rect" coords="950,120,1100,140" href="stop.html" title="Pallikarani">
        </map>
      </center>
    </body>
    </html>

stop.html


    <html>
    <head>
      <title>Pallikarani</title>
    </head>
    <body bgcolor="blue">
      <h1 align="center">
        <font color="cyan"><b>Tambaram</b></font>
      </h1>
    <h3 align="center">
    <font color="lime"><b>Pallikarani</b></font>
  </h3>

  <hr size="3" color="cyan">

  <p align="justify">
        <font face="Georgia" size="5" color="white">
            Pallikaranai is a rapidly developing residential locality in South Chennai,
            offering excellent connectivity to OMR, ECR, and GST Road. It is renowned 
            for the Pallikaranai Marsh, one of Chennai's last remaining natural wetlands, 
            which supports over 600 species of flora and fauna, including 176 bird species .​
          </p>
        </body
        </html>


garden.html


    <html>
    <head>
      <title>Garden</title>
    </head>
    <body bgcolor="blue">
      <h1 align="center">
        <font color="cyan"><b>Tambaram</b></font>
      </h1>
      <h3 align="center">
        <font color="lime"><b>GG Garden</b></font>
      </h3>
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5" color="white">
            GG Garden in Tambaram is a peaceful residential area known for its calm surroundings.
            It offers easy access to schools, shops, and transport facilities, making life convenient.
            The neighborhood features clean streets, friendly communities, and a green environment.
            Ideal for families, GG Garden combines suburban charm with city connectivity. 
      </p>
    </body>
    </html>

lake.html


    <html>
    <head>
      <title>Lake</title>
    </head>
    <body bgcolor="blue">
      <h1 align="center">
        <font color="cyan"><b>Tambaram</b></font>
      </h1>
      <h3 align="center">
        <font color="lime"><b>Tambaram lake</b></font>
      </h3>

      <hr size="3" color="red">

      <p align="justify">
        <font face="Georgia" size="5" color="white">
          Lakes are generally formed as a consequence of the tectonic or glacial activity. 
          Lakes are also formed due to the meandering river or even by human activity. 
          For civilization, there are abundant reasons to point them out, this owes to the 
          resource of water, and water is a definite source to continue life on this planet. 
          This lake is also facing numerous problems such as pollution, siltation, and 
          climate change. 
      </p>
    </body>
    </html>


road.html


    <html>
    <head>
      <title>My Home Town</title>
    </head>
    <body bgcolor="green">
      <h1 align="center">
        <font color="gray"><b>Tambaram</b></font>
      </h1>
      <h3 align="center">
        <font color="blue"><b>MUDUCHUR ROAD </b></font>
      </h3>
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5">
          These Roads construction started at 2017 and successfully ended on 2023.
          These Roads are constructed by L&T . These Roads are know for it's pot holes and 
          number of accidents occuring.
        </font>
      </p>
    </body>
    </html>
```

# OUTPUT

![435693955-3fe7d17d-e34e-41f7-a3bd-14a090179e70](https://github.com/user-attachments/assets/3ca5dc45-aff7-4063-aa58-2d8dc18d48c3)

![435694229-4a081640-d2f6-4661-a539-8a9ab2a18a3e](https://github.com/user-attachments/assets/16134c23-dcd7-469f-864b-c9ff3f2cd4b1)

![435694502-50a881ae-9220-4917-a3ae-5fafaafb1334](https://github.com/user-attachments/assets/b7979329-4299-4489-b525-229230ed06d5)

![435694603-3825f722-7177-40fc-a016-eb71df60fdfe](https://github.com/user-attachments/assets/fdfd094d-4226-4b1a-bcd2-1cbfff9a149c)

![435694774-ecf0c2b5-22ab-4390-8a50-78d3c6f4a0ba](https://github.com/user-attachments/assets/2429008b-8825-41c7-962f-3b9de0b24198)



# RESULT
The program for implementing image maps using HTML is executed successfully.
