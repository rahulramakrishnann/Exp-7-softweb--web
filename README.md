# Ex.07 Software Product Company Website

## Date: 31/11/2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
## index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iDIGITAL</title>
    <style>
        *{
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #080b3f;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: rgb(163, 133, 133);
        color: rgb(194, 171, 171);
        }

        header a.active {
        background-color: rgb(25, 52, 141);
        color: rgb(219, 199, 199);
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color:rgba(39, 58, 110, 0.959);
            height: 500px;        
            overflow: hidden;
            line-height: 30px;
        }

        h1,h2{
            text-align: center;
        }

        .image1 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
        }

        .image3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .image2  img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        footer{
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman',times new roman, times new roman;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <div class="logo">
            <a><img src="logo.jpg" alt="logo" border="1"></a>
        </div>
        <a class ="cname"><h1>iDIGITAL</h1></a>
        <div class="header-right">
            <a class="active" href="index.html">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <h1>Welcome to iDigital, where innovation is our language and software development is our expertise. We craft solutions that redefine the digital landscape, ensuring your technology evolves with excellence.</h1>
        
        <h2>
            "iDigital: Pioneering Tomorrow's Tech, Today!"
        </h2>
        <div class="image1">
            <img src="soft1.jpg" alt="image1">
        </div>
        <div class="image2">
            <img src="soft2.jpg" alt="image2">
        </div>
        <div class="image3">
            <img src="soft3.jpg" alt="image3">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 iDIGITAL.All rights reserved!.</p>
    </footer>
</body>
</html>
```
## product.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iDIGITAL</title>
    <style>
        *{
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #080b3f;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: white;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        .cname{
            padding-top: 12px;
            font-family: 'times new roman', 'times new roman', 'times new roman', 'times new roman', times new roman, times new roman;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color:rgb(25, 52, 141);
            height: 1500px;        
            overflow: hidden;
            line-height: 30px;
        }
        
        .prod1 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 280px;
        }

        .prod2 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        .prod3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .prod4 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
        }

        .prod5 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
            left: 650px;
        }

        .prod6 img{
            padding: 50px;
            height: 300px;
            width: 500px;
            position:absolute;
            top: 740px;
            left: 1100px;
        }

        .quote{
            text-align: center;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 40px;
            color: #8a8aa0  ;
        }

        footer{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>iDIGITAL</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a class="active" href="product.html">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="quote">
            <h3>iDIGITAL avalailability over developing Softwares </h3>
        </div>
        <div class="prod1">
            <img src="devops1.jpeg" alt="prod3">
        </div>
        <div class="prod2">
            <img src="mads.jpg" alt="prod2">
        </div>
        <div class="prod3">
            <img src="uxi.jpg" alt="prod1">
        </div>
        <div class="prod4">
            <img src="New Product Development.svg" alt="prod4">
        </div>
        <div class="prod5">
            <img src="fulllogo.jpg" alt="prod5">
        </div>
        <div class="prod6">
            <img src="webdev.jpg" alt="prod6">
        </div>
    </section>
    <footer>
        <p>&copy; 2023 iDIGITAL. All rights reserved!.</p>
    </footer>
</body>
</html>

```
## people.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iDIGITAL</title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: #080b3f;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color:white;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: rgba(25, 52, 141, 0.815);
            overflow: hidden;
            line-height:normal;
        }
        .person {
            text-align: center;
        }

        p{
            font-size: 20px;
        }
        .person img {
            display:grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            margin: 0 auto;
            height: 340px;
            padding-top: 40px;
        }

        .person p.name {
            font-weight: bold;
            margin-top: 10px;
            color:rgb(89, 180, 3);
        }

        .person p.desig {
            font-weight: bold;
            margin-top: 10px;
            color:rgb(184, 172, 172);
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:rgb(167, 190, 201)  ;
        }
        
        footer{
            font-size: 40px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>iDIGITAL</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a class="active" href="people.html">People</a>
            <a href="contact.html" target="_blank">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>GEMS OF iDIGITAL</h3>
        </div>
        <div class="image">
            <div class="person">
                <img src="person1.jpg" alt="Mugilan">
                <p class="name">Emma Johnson</p>
                <p class="desig">CEO</p>
            </div>
            <div class="person">
                <img src="person2.jpg" alt="Pinto ponnachan">
                <p class="name">Liam Brown</p>
                <p class="desig">GENERAL MANAGER</p>
            </div>
            <div class="person">
                <img src="person3.jpg" alt="Prakash">
                <p class="name">Lucas Clark</p>
                <p class="desig">HR MANAGER</p>
            </div>
            <div class="person">
                <img src="person4.jpg" alt="Ritik samuel">
                <p class="name">Olivia Smith</p>
                <p class="desig">MARKETING HEAD</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 iDIGITAL. All rights reserved.!</p>
    </footer>
</body>
</html>

```
## contact.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iDIGITAL</title>
    <style>
        *{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color:#080b3f;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: white;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: rgb(231, 216, 216);
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .cname{
            padding-top: 12px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: rgb(25, 52, 141);
            overflow: hidden;
            line-height:normal;
        }
        
        .contact-container {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 50px;
        }

        .contact-image {
            flex: 1;
            text-align: center;
        }

        .contact-image img {
            max-width: 100%;
            height: auto;
        }

        .contact-details {
            flex: 1;
            padding: 50px;
            font-size: 25px;
            color:rgb(181, 189, 174);
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:rgb(94, 163, 38);
        }

        footer{
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="logo.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>iDIGITAL</h1></a>
        <div class="header-right">
            <a href="index.html" target="_blank">Home</a>
            <a href="product.html" target="_blank">Product</a>
            <a href="people.html" target="_blank">People</a>
            <a class="active" href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>Contact Link Through </h3>
        </div>
        <div class="contact-container">
            <div class="contact-image">
                <img src="contact-us.jpg " >
            </div>
            <div class="contact-details">
                <p><strong>Email:</strong> info@idigital.com</p>
                <p><strong>Phone:</strong> +1 (444) 784501256</p>
                <p><strong>Address:</strong> 145588 Marina Hill road,Block AG, Texas city, Texas 6012</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 iDIGITAL. All rights reserved!.</p>
        </footer>
</body>
</html>

```

## OUTPUT:

![image](https://github.com/rahulramakrishnann/Exp-7-softweb--web/assets/143045415/5067e566-1ed9-433d-85fb-3897dfd3fc24)
![image](https://github.com/rahulramakrishnann/Exp-7-softweb--web/assets/143045415/f8216f03-497a-45fc-89a9-6513c71841e6)
![image](https://github.com/rahulramakrishnann/Exp-7-softweb--web/assets/143045415/3adf19de-5ec1-40de-bf42-920bfe49ab92)
![image](https://github.com/rahulramakrishnann/Exp-7-softweb--web/assets/143045415/56c29478-33bd-4f27-b58c-649494c32ff0)
![image](https://github.com/rahulramakrishnann/Exp-7-softweb--web/assets/143045415/a9f65067-375a-48a2-93cb-2c9175cbcf43)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
