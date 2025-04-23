# Ex04 Places Around Me
## Date: 23.04.2025
## Name: Marimuthu Mathavan
## Reg No: 212224230153

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>MY CITY</title>
</head>
<body bgcolor="beige">
  <h1 align="center"><b>NELLORE</b></h1>
  <h3 align="center"><b>MARIMUTHU MATHAVAN (212224230153)</b></h3>
  <center>
  <img src="Map.png" alt="Map of my Area" usemap="#mymap" width="1450" height="610">
</center>
  <map name="mymap">
    <area shape="rect" coords="1725,213,1750,262" href="beach.html" alt="MYPADU BEACH">
    <area shape="rect" coords="581,390,596,519" href="temple.html" alt="RANGANATHA SWAMY TEMPLE">
    <area shape="rect" coords="118,144,970,154" href="hotel.html" alt="MINERVA GRAND">
    <area shape="rect" coords="1452,888,1542,869" href="school.html" alt="NARAYANA SCHOOL">
    <area shape="rect" coords="1363,750,1558,813" href="hill.html" alt="NARASIMHA KONDA ">
  </map>
</body>~
</html>

beach.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="dark green">
    <h1 align="center">
      <font color="beige"><b><u>NELLORE</u></b></font>
    </h1>

    <h3 align="center">
      <font color="black"><b>MYPADU BEACH</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="black" face="Georgia" size="5">
        ​Mypadu Beach, located approximately 25 kilometers from Nellore in Andhra Pradesh, is a serene coastal destination along the Bay of Bengal. Known for its golden sands, gentle waves, and tranquil atmosphere, the beach offers a peaceful retreat away from bustling city life. Managed by the Andhra Pradesh Tourism Development Corporation (APTDC), Mypadu Beach has seen developments like water sports, including jet skiing, and the establishment of resorts to enhance tourist experiences . The beach is also a hub for local fishermen, providing visitors with a glimpse into the coastal lifestyle. With its clean shoreline and scenic beauty, Mypadu Beach is ideal for leisurely walks, photography, and enjoying fresh seafood from nearby stalls. Its accessibility and natural charm make it a favored spot for both relaxation and adventure.
      </font>
    </p>
  </body>
</html>

school.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>NELLORE</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>NARAYANA SCHOOL</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        ​Narayana Schools are part of the Narayana Group of Educational Institutions, one of Asia's largest and most respected educational conglomerates. Established in 1979 by Dr. P. Narayana with just seven students, the group has expanded to over 800 schools, colleges, coaching centers, and professional institutions across 23 Indian states, serving more than 600,000 students annually . Narayana Schools are renowned for their integrated curriculum that combines CBSE and state board syllabi with focused preparation for competitive exams like JEE, NEET, and UPSC . The institution offers age-appropriate programs such as e-Kidz, e-Champs, and e-Techno, emphasizing holistic development, including mental wellness support through its DISHA program . With a commitment to academic excellence and overall student growth, Narayana Schools aim to nurture future leaders equipped with knowledge, skills, and resilience.
      </font>
    </p>
  </body>
</html>

temple.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>NELLORE</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>RANGANATHA SWAMY TEMPLE</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        The Sri Talpagiri Ranganatha Swamy Temple in Nellore, Andhra Pradesh, is a historic and revered shrine dedicated to Lord Ranganatha, a reclining form of Lord Vishnu. Located on the banks of the Penna River, the temple dates back to the Pallava period and saw significant contributions from the Chola and Pandya dynasties. It is known for its magnificent seven-tiered Raja Gopuram, built in 1849, and its unique west-facing sanctum, which houses a 10-foot-long idol of Lord Ranganatha reclining on Adisesha. The temple also features shrines for Goddess Ranganayaki, Andal, and the Alwars, along with a beautiful mirror hall known as Addala Mandapam. Celebrated for its grand Brahmotsavam festival held annually in March or April, the temple is both a spiritual and architectural landmark, believed to rest on Adisesha who transformed into a hill to serve as the divine couch for Lord Vishnu.
      </font>
    </p>
  </body>
</html>

hotel.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>NELLORE</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>MINERVA GRAND HOTEL</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        ​Minerva Grand Hotel in Nellore, Andhra Pradesh, is a prominent 3-star establishment situated on Grand Trunk Road in the Dargamitta area, offering convenient access to the city's commercial and entertainment hubs. The hotel features 106 well-appointed rooms and suites, including Standard Single, Premium, Imperial, and Family Grand Suites, each equipped with modern amenities such as complimentary Wi-Fi, LCD televisions, tea/coffee makers, and in-room refrigerators. Guests can enjoy dining at the in-house Blue Fox restaurant, unwind at the On The Rocks bar, and utilize facilities like a fitness center and spacious banquet halls for events and conferences. With its blend of comfort, strategic location, and comprehensive services, Minerva Grand Nellore caters to both business and leisure travelers seeking a quality stay in the city.
      </font>
    </p>
  </body>
</html>

hill.html
<html>
  <head>
    <title>My Home Town</title>
  </head>
  <body bgcolor="DARK GREEN">
    <h1 align="center">
      <font color="beige"><b><u>NELLORE</u></b></font>
    </h1>

    <h3 align="center">
      <font color="BLACK"><b>NARASIMHA KONDA HILL</b></font>
    </h3>

    <hr size="3" color="gold">

    <p align="justify">
      <font color="bLACK" face="Georgia" size="5">
        Narasimha Konda, located approximately 15 kilometers from Nellore in Andhra Pradesh, is a revered hill shrine dedicated to Lord Narasimha, the fourth avatar of Lord Vishnu. Perched on the banks of the Penna River, the Sri Vedagiri Lakshmi Narasimha Swamy Temple atop the hill is believed to have been established by Sage Kashyapa and later constructed by the Pallava king Narasimhavarman I in the 9th century. The temple holds significant mythological importance, with legends stating that the Saptarishis performed yagnas here, and references to the site are found in both the Ramayana and Mahabharata. The hill, rising to about 350 feet, offers panoramic views and is considered a sacred pilgrimage destination. Annual festivals like Brahmotsavam and Krishna Janmashtami are celebrated with great fervor, attracting devotees from various regions. Narasimha Konda stands as a testament to the region's rich spiritual heritage and architectural grandeur.
      </font>
    </p>
  </body>
</html>


```


## OUTPUT
![alt text](<mathavan/Screenshot (54).png>)
![alt text](<mathavan/Screenshot (55).png>)
![alt text](<mathavan/Screenshot (56).png>)
![alt text](<mathavan/Screenshot (57).png>)
![alt text](<mathavan/Screenshot (58).png>)
![alt text](<mathavan/Screenshot (59).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
