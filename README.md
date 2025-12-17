# Ex.06 Restaurant Website
## Date:17/12/2025

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
rest.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style1.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="restname">
        <h1><b>BELLA CUCINA</b></h1>
      </div>
      <div class="line">The taste of Italy!</div>
      <div class="lines">
        <i>"Where every bite feels like home in Italy."</i>
        <p>
          A cozy Italian bistro that brings authentic pasta, wood-fired pizzas,
          and rich sauces straight from traditional Italian recipes.
        </p>
      </div>
      <div class="image1">
        <img src="image1.jpg " width="600" height="300" />
      </div>
      <div class="image2">
        <img src="image2.jpg" width="600" height="300" />
      </div>
      <footer class="copyrights">&copy;Mahalakshmi S(25018377)</footer>
    </div>
  </body>
</html>

style1.css

.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background.jpg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.restname {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.line {
    color: beige;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 250%;
    top: -120px;
    left: 10px;
}

.lines {
    color: white;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 130%;
    top: -100px;
}

.image1 {
    position: relative;
    top: -90px;
    left: 100px;
    background-size:contain;
}

.image2 {
    position: relative;
    top: -390px;
    left: 800px;
    background-size:contain;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: -330px;
    left: -20px;
    position: relative;
}

menu.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style2.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="menu">
        <h1><b>MENU</b></h1>
      </div>
      <div class="menugrid">
        <div class="menuitem">
          <img src="pizza.jpg" width="300" height="150" />
          <h1>Pizza</h1>
          <p>Rs. 190</p>
        </div>
        <div class="menuitem">
          <img src="pasta.jpg " width="300" height="150" />
          <h1>Pasta</h1>
          <p>Rs. 180</p>
        </div>
        <div class="menuitem">
          <img src="risotto.jpg " width="300" height="150" />
          <h1>Risotto</h1>
          <p>Rs. 200</p>
        </div>
        <div class="menuitem">
          <img src="lasagna.jpg " width="300" height="150" />
          <h1>Lasagna</h1>
          <p>Rs. 220</p>
        </div>
        <div class="menuitem">
          <img src="focaccia.jpg " width="300" height="150" />
          <h1>Focaccia</h1>
          <p>Rs. 170</p>
        </div>
        <div class="menuitem">
          <img src="arrosticini.jpg" width="300" height="150" />
          <h1>Arrosticini</h1>
          <p>Rs. 210</p>
        </div>
        <div class="menuitem">
          <img src="gelato.jpg" width="300" height="150" />
          <h1>Gelato</h1>
          <p>Rs. 150</p>
        </div>
        <div class="menuitem">
          <img src="tiramisu.jpg " width="300" height="150" />
          <h1>Tiramisu</h1>
          <p>Rs. 200</p>
        </div>
      </div>
      <footer class="copyrights">&copy; Mahalakshmi S(25018377)</footer>
    </div>
  </body>
</html>

style2.css
.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(Background.jpg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.menu {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
    border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 100px;
    left: -20px;
    position: relative;
}

admin.html
<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style3.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="admin">
        <h1><b>ADMINISTRATION TEAM</b></h1>
      </div>
      <div class="admingrid">
        <div class="adminlist">
          <img src="maha.jpg " width="130" height="250" />
          <h1>Mahalakshmi S</h1>
          <p class="post">CEO</p>
        </div>
        <div class="adminlist">
          <img src="vijay.jpg" width="130" height="250" />
          <h1>Vijay</h1>
          <p class="post">Marketing Manager</p>
        </div>
        <div class="adminlist">
          <img src="vijay deverakonda.jpg" width="130" height="250" />
          <h1>Vijay Deverakonda</h1>
          <p class="post">Operations Manager</p>
        </div>
        <div class="adminlist">
          <img src="dulquer salmaan.jpg " width="130" height="250" />
          <h1>Dulquer Salmaan</h1>
          <p class="post">HR Manager</p>
        </div>
        <div class="adminlist">
          <img src="AK.jpg " width="130" height="250" />
          <h1>Ajith Kumar</h1>
          <p class="post">Executive Chef</p>
        </div>
        <div class="adminlist">
          <img src="SK.jpg" width="130" height="250" />
          <h1>Siva Karthikeyan</h1>
          <p class="post">Customer Service Manager</p>
        </div>
      </div>
      <footer class="copyrights">&copy; Mahalaskhmi S(25018377)</footer>
    </div>
  </body>
</html>

style3.css

.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(Background.jpg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: aliceblue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.admin {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminlist{
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminlist img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminlist h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.adminlist p {
    color: black;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 30px;
    left: -20px;
    position: relative;
}

contact.html

<html>
  <head>
    <title>Home</title>
    <link rel="stylesheet" href="style4.css" />
  </head>
  <body>
    <div class="background">
      <div class="contents">
        <a href="rest.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
      </div>
      <div class="contact">
        <h1><b>CONTACT</b></h1>
      </div>
      <div class="info">
        <h1>Visit us at:</h1>
        <p>
          Bella Cucina<br />123, Maple Street,<br />Riverside Street, CA
          173081<br />India
        </p>
        <br />
        <h1>Phone:</h1>
        <p>+91 98765 43210</p>
        <br />
        <h1>Email ID:</h1>
        <p>bellacucina123@gmail.com</p>
      </div>
      <footer class="copyrights">&copy; Mahalakshmi S(25018377)</footer>
    </div>
  </body>
</html>

style4.css

.background {
    width: 1470px;
    height: 680px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(Background.jpg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid white;
    padding: 10px;
    background-color: white;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.contact {
    color: paleturquoise;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.info {
    color: white;
    font-family: Times New Roman;
    position: relative;
    top: -70px;
    left: 50;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: -20px;
    left: -20px;
    position: relative;
}

```



## OUTPUT:
![alt text](<Screenshot (81).png>)
![alt text](<Screenshot (82).png>)
![alt text](<Screenshot (83).png>)
![alt text](<Screenshot (84).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
