## Ex.06 Restaurant Website
## Date:28.12.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```

restaurant html

<html>
    <head>
        <title>HP Restaurant</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <h1>HP Restaurant</h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu item.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
        </div>
        <br>
        <br>
        <h2>"Madras on a plate Bold,Spicy,and unforgettable"</h2>
        <br>
        <br>
    <h3>"Traditional recipes,modern memories.Just like Grandma used to Make".</h3>
        <br>Every meal tells a story of Tamil Nadu.
        </h3>
    </body>
    <br><br>
    <footer>
        <p>&copy;Hariprasad A (25005271)</p>
    </footer>
</html>

styles.css

body{
    background-image: url('rest...1....jpg');
    background-repeat: no-repeat;
    background-size:cover;
    margin: auto;
}
h1{
    font-style: initial;
    text-align: center;
    color: rgb(157, 3, 3);
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: white;
    display: inline;
    font-size:larger;
    padding: 10px 10px;
}
h2{
    font-style: italic;
    font-size: 60px;
    margin-left: 10px;
}
h3{
    font-style: italic;
    font-size: 30px;
    margin-bottom: 250px;
    margin-left: 10px;
}
footer{
    text-align: center;
    color: brown;
    background-color: cyan;
}

menu item.html

<html>
    <head>
        <title>MENU</title>
        <link href="menu item.css" rel="stylesheet">
    </head>
    <body>
        <h1>MENU</h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
            <br><br><br><br>
        </div>
        <div class="menubar">
            <div class="food">
            <img src="appam.jpeg">
                <h3>APPAM</h3>
                <h4> Price=Rs-60</h4>
            </div>
            <div class="food">
                <img src="dosa.jpeg">
                <h3>DOSA</h3>
                <h4> Price=Rs-50</h4>
            </div>
            <div class="food">
                <img src="idli.webp">
                <h3>IDLI</h3>
                <h4> Price=Rs-40</h4>
            </div>
            <div class="food">
                <img src="meals.jpeg">
                <h3>MEALS</h3>
                <h4> Price=Rs-130</h4>
            </div>
            <div class="food">
                <img src="parotta.avif">
                <h3>PAROTTA</h3>
                <h4> Price=Rs-50</h4>
            </div>
            <div class="food">
                <img src="pongal.avif">
                <h3>PONGAL</h3>
                <h4> Price=Rs-60</h4>
            </div>
    </body>
    <br>
    <footer>
        <p>&copy;Hariprasad A (25006750)</p>
    </footer>
</html>

menu item.css


body{
    background-image: url('rest...2....jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
h1{
    text-align: center;
    font-style: normal;
    color: cadetblue;
    margin-top: 20px;
    font-size: 40px;
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: rgb(195, 177, 177);
    display: inline;
    font-size:larger;
    padding: 10px 10px;
    font-style: normal;
    font-size: 25px;
}
h1{
    background: none;
}
.menubar {
    display: flex;
    gap: 35px;
    width: 150%;
    margin: 100px;
}
.food {
    background-color: rgb(182, 162, 17);
    padding: 10px;
    text-align: center;
    border-radius: 8px;
    
}
.food img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}
footer{
        background-color: rgb(101, 155, 132);
    color: whitesmoke;
    text-align: center;
    padding: 10px;
    font-size: 24px;
    font-weight: 100px;

}


contact.html

<html>
    <head>
        <title>CONTACT</title>
        <link href="contact.css" rel="stylesheet">
    </head>
    <body>
        <h1>CONTACT</h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
            <br><br><br><br>
        </div>
        <h2>Location</h2>
        <p><b>HP Restaurant</b>
        <br>
        kattupakkam highway road
        <br>
        chennai-600056
        <br>
        TamilNadu
        </p>
        <h2>Email</h2>
        <p>HPrestaurant@gmail.com</p>
        <h2>Telephone No</h2>
        <p>9542706017<br>7342080178</p>
    </body>
    <footer>
        <p>&copy;Hariprasad A(25005271)</p>
    </footer>
</html>

contact.css

body{
    background-image: url('rest...3....jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
h1{
    font-style: initial;
    text-align: center;
    color: rgb(21, 152, 222);
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: rgb(26, 1, 1);
    display: inline;
    font-size:larger;
    padding: 10px 10px;
}
h2{
    text-align: center;
    font-style: inherit;
    font: size 40px;
    color: blue;
    margin-bottom: 15px;
}
p{
    text-align: center;
    font-style: italic;
    color: rgb(213, 10, 183);
}
footer{
    text-align: center;
    background-color: aquamarine;
    margin-top: 85px;
}

administration.html



<html>
    <head>
        <title>administration</title>
        <link href="administration.css" rel="stylesheet">
    </head>
    <body>
        <h1>ADMINISTRATION</h1>
        <div class="navigation">
            <a href="restaraunt.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administration.html">ADMINISTRATION</a>
            <br><br><br><br>
        </div>
        <div class="admin">
            <div class="members">
                <img src="Hariprasad.1.JPG">
                <h3>Hariprasad</h3>
                <h3>CEO</h3>
            </div>
            <div class="members">
                <img src="Dhoni.2..webp">
                <h3>MS.Dhoni</h3>
                <h3>CHAIRMAN</h3>
            </div>
            <div class="members">
                <img src="christian bale .3..jpg">
                <h3>Christian Bale</h3>
                <h3>DIGITAL MANAGER</h3>
            </div>
            <div class="members">
                <img src="brad pitt .4..jpg">
                <h3>Brad Pitt</h3>
                <h3>ASST MANAGER</h3>
            </div>
            <div class="members">
                <img src="vijay.5..jpg">
                <h3>Vijay</h3>
                <h3>SENIOR MANAGER</h3>
            </div>
        </div>
    </body>
    <footer>
        <p>&copy;Hariprasad(25005271)</p>
    </footer>
</html>

administration. css

body{
    background-image: url('rest...4....jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
h1{
    text-align: center;
    color: bisque;
    font-style:normal ;
}
.navigation{
    text-align: center;
    margin-left: 10px;
}
a{
    color: rgb(219, 6, 6);
    display: inline;
    font-size:larger;
    padding: 10px 10px;
}
.admin{
    display: flex;
    gap: 20px;
    width: 150%;
    margin: 100px;
}
.members{
    background-color:rgb(74, 110, 120);
    padding: 10px;
    text-align: center;
    border-radius: 8px;
}
.members img{
    width: 100%;
    height: 230px;
    object-fit: cover;
}
footer{
    text-align: center;
    background-color: aquamarine;
    margin-top: 85px;
}
```




## OUTPUT:
![alt text](<Screenshot 2025-12-28 152621.png>)
![alt text](<Screenshot 2025-12-28 152730.png>)
![alt text](<Screenshot 2025-12-28 152814.png>)
![alt text](<Screenshot 2025-12-28 152848.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
