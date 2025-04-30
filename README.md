# Ex04 Places Around Me
## Date: 30.04.2025

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
        <center>
        <h1 >
        <font color="lightblue" >KOLATHUR</font>
        </h1>
        <h3 > <font color ="black" > VAISHNAVI R  NAIR        REG NO: 212224110058 </font></h3>

            <img src="map.jpg" usemap="#MyCity" height ='610' width="1450">
            <map name="MyCity">
                <area shape="rect" coords="909,562,1084,644" href="home.html" title="MY HOME">
                <area shape="rect" coords="631,51,867,122" href="market.html" title="KOLATHUR FISH MARKET">
                <area shape="rect" coords="61,61,348,139" href="hotel.html" title="HOTEL SRM GRANDS">
                <area shape="rect" coords="786,103,1073,181" href="movie.html" title="SRI GANGA CINEMAS">
                <area shape="rect" coords="223,392,456,455" href="school.html" title="DON BOSCO MATRICULATION HIGHER SECONDARY SCHOOL">       
            </map>
        </center>
    </body>
</html>

movie.html
<!DOCTYPE html>
<html>
<head>
    <title>Sri Ganga Cinemas</title>
    <style>
        body {
            background-color: green;
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>KOLATHUR</h2>
    <h2>SRI GANGA CINEMAS: ENTERTAINMENT FOR EVERYONE</h2>
    <hr>
    <p>
        Sri Ganga Cinemas, located in Kolathur, Chennai, is a popular theatre known for offering an affordable and enjoyable movie-watching experience. It features comfortable seating, digital sound systems, and a good selection of Tamil, Telugu, and Hindi films.
    </p>
    <p>
        The cinema is loved by local residents for its convenient location, reasonable ticket prices, and clean environment. With regular showtimes and online booking options, it’s a go-to spot for families and movie lovers in the neighborhood.
    </p>
    <p>
        Whether it's a weekend blockbuster or a casual weekday show, Sri Ganga Cinemas delivers a great cinematic experience close to home.
    </p>
</body>
</html>

school.html
<!DOCTYPE html>
<html>
<head>
    <title>Don Bosco Matriculation School</title>
    <style>
        body {
            background-color: green;
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>KOLATHUR</h2>
    <h2>DON BOSCO MATRICULATION SCHOOL: EDUCATION WITH VALUES</h2>
    <hr>
    <p>
        Don Bosco Matriculation School, located in Kolathur, Chennai, is a highly reputed educational institution known for its commitment to academic excellence and character building. Affiliated with the Tamil Nadu State Board, the school offers quality education from Kindergarten to Higher Secondary level.
    </p>
    <p>
        The school provides a balanced curriculum that integrates academics, sports, arts, and moral instruction. With modern classrooms, computer labs, a library, and science laboratories, Don Bosco ensures a stimulating learning environment for its students.
    </p>
    <p>
        Known for its disciplined yet friendly atmosphere, the school emphasizes values such as respect, responsibility, and integrity. The experienced faculty members strive to nurture each student's potential, helping them grow into confident and responsible citizens.
    </p>
    <p>
        Located conveniently near Perambur and Villivakkam, Don Bosco Matriculation School is easily accessible by public transport and is a preferred choice for parents seeking a well-rounded education for their children.
    </p>
</body>
</html>

hotel.html
<!DOCTYPE html>
<html>
<head>
    <title>Hotel SRM Grands</title>
    <style>
        body {
            background-color: green;
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>KOLATHUR</h2>
    <h2>HOTEL SRM GRANDS: COMFORTABLE STAY IN CHENNAI</h2>
    <hr>
    <p>
        Hotel SRM Grands, located in Kolathur, Chennai, is a well-known destination for travelers seeking comfort and convenience. With its clean and modern rooms, excellent service, and proximity to major attractions, the hotel is ideal for both business and leisure stays. It features air-conditioned rooms, free Wi-Fi, 24/7 room service, and on-site parking.
    </p>
    <p>
        The in-house multi-cuisine restaurant serves delicious South Indian, North Indian, and Chinese dishes, making dining convenient for guests. The hotel is also equipped with a banquet hall suitable for small functions, meetings, or events.
    </p>
    <p>
        Located close to Perambur and Villivakkam, Hotel SRM Grands is easily accessible via road and rail. Friendly staff, budget-friendly rates, and reliable facilities make it a popular choice among local and outstation visitors alike.
    </p>
</body>
</html>

market.html
<!DOCTYPE html>
<html>
<head>
    <title>Kolathur Fish Market</title>
    <style>
        body {
            background-color: green;
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>KOLATHUR</h2>
    <h2>KOLATHUR FISH MARKET: A HUB OF FRESH SEAFOOD</h2>
    <hr>
    <p>
        Kolathur Fish Market, located in Chennai, Tamil Nadu, is a bustling hub for fresh seafood lovers. Known for its early morning energy and a wide variety of fish, the market attracts both locals and wholesale buyers. Vendors display an impressive assortment of fresh catch including prawns, crabs, sardines, and seer fish. The market plays a vital role in the local economy and supports numerous families who rely on fishing and fish trading. The market’s vibrant atmosphere, competitive pricing, and fresh seafood make it a preferred choice for many residents in and around Kolathur.
    </p>
</body>
</html>

home.html
<!DOCTYPE html>
<html>
<head>
    <title>My Home</title>
    <style>
        body {
            background-color: green;
            color: white;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
        }
        h2 {
            margin: 10px;
        }
        hr {
            color: white;
        }
    </style>
</head>
<body>
    <h2>MY HOME</h2>
    <h2>A PLACE OF LOVE AND COMFORT</h2>
    <hr>
    <p>
        My home is located in Kolathur, Chennai – a peaceful neighborhood filled with greenery and friendly people. It is a place where I feel safe, relaxed, and happy every day.
    </p>
    <p>
        Our house has a cozy living room, a bright kitchen, two bedrooms, and a small garden where we grow flowers and vegetables. In the evenings, we often sit outside to enjoy the fresh air and talk with our neighbors.
    </p>
    <p>
        My home is close to schools, parks, and shops, which makes daily life very convenient. What makes it truly special is the love and togetherness shared by everyone in the family.
    </p>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2025-04-30 100320.png>)

![alt text](<Screenshot 2025-04-30 100304.png>) 
![alt text](<Screenshot 2025-04-30 100131.png>) 
![alt text](<Screenshot 2025-04-30 100158.png>) 
![alt text](<Screenshot 2025-04-30 100224.png>) 
![alt text](<Screenshot 2025-04-30 100244.png>)




## RESULT
The program for implementing image maps using HTML is executed successfully.
