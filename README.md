# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 7:

Publish the website in the given URL.

## PROGRAM :

### homepage:
#### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=fff, initial-scale=1.0">
    <title>D.Code.org</title>
    <link rel="stylesheet" href="./css/home.css">
</head>
<body style="background-color: rgb(212, 214, 214);">
    <div class="header">
        <nav>
            <h1 class="name"><</h1>
            <h1 class="name">D-C<span>ode></span></h1>
            <ul>
                <li><a href="home.html">Home |</a></li>
                <li><a href="product.html">Product |</a></li>
                <li><a href="about.html">About Us |</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>
    <div class="content">
        <h1 style="text-align: center; margin-top: 50px; font-size: 50px; font-family: Georgia, 'Times New Roman', Times, serif;">welcome to,</h1>
        <h2 style="text-align: center; padding-top: 30px; font-family: Georgia, 'Times New Roman', Times, serif;">Learn, code, and grow with d-code, the smart way to decode your knowledge</h2>
        <h2 style="text-align: center; padding-top: 15px; font-family: Georgia, 'Times New Roman', Times, serif;">Happy Coding...</h2>
    </div>
    <div class="login">
        <button>Sign In</button>
        <button>Sign Up</button>
    </div>
    <div class="footer">
       <h4>Copyright &#169; 2023 D-Code Private Limited, Developed by Sri Vignesh G</h4> 
    </div>
</body>
</html>
```
#### home.css:
```
*{
    margin: 0%;
    padding: 0%;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.header{
    background-color: rgb(80, 90, 87);
    border-bottom-left-radius: 30px;
    border-bottom-right-radius: 30px;
    height: 100px;
}
span{
    color: rgb(255, 255, 255);
}
ul,li{
    display: inline;
}
ul{
    margin-left: 43%;
}
.name{
    display: inline-block;
    margin-top: 15px;
    font-size: 65px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
a{
    font-size: 25px; 
    color: black;
}
a:hover{
    color: white;
    cursor: pointer;
}
button{
    background-color: gray;
    color: black;
    border: none;
    border-radius: 40px;
    padding: 15px;
    font-size: x-large;
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-weight: bolder;
    margin-top: 40px;
    margin-right: 20px;
    display: inline;
}
.login{
    text-align: center;
}
button:hover{
    color: white;
    background-color: black;
}
.footer{
    background-color: black;
    color: white;
    margin-top: 200px;
    padding: 5px;
    text-align: center;
}
```
### ProductPage:
#### Product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>product.d-code</title>
    <link rel="stylesheet" href="./css/product.css">
</head>
<body bgcolor="gray">
    <div class="header">
        <nav>
            <h1 class="name"><</h1>
            <h1 class="name">D-C<span>ode></span></h1>
            <ul>
                <li><a href="home.html">Home |</a></li>
                <li><a href="product.html">Product |</a></li>
                <li><a href="about.html">About Us |</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>
    <div class="title">
        <h1 class="nm">Store:</h1>
    </div>
    <div class="hold" style="margin-left: 6%;">
        <div class="box">
            <img src="./img/html.png" alt="html">
            <h5>HTML is a markup language that tells web browsers how to structure the web pages you visit.</h5>
        </div>
        <div class="box">
            <img src="./img/css.png" alt="css">
            <h5>Cascading Style Sheets (CSS) is a computer language that structures and lays out web pages.</h5>
        </div>
        <div class="box">
            <img src="./img/js.png" alt="javascript">
            <h5>JavaScript is used to make web pages interactive and to add dynamic content to web pages</h5>
        </div>
        <div class="box">
            <img src="./img/java.png" alt="html">
            <h5>Java is an object oriented language (OOP).It helps to write a code once and run it anywhere.</h5>
        </div>
        <div class="box">
            <img src="./img/php.png" alt="html">
            <h5>PHP from PHP group is a general-purpose scripting language geared towards web development.</h5>
        </div>
        <div class="box">
            <img src="./img/c.png" alt="html">
            <h5>It is powerful and general-purpose language used in programming. prefered for beginners</h5>
        </div>
    <br>
    <div class="box">
        <img src="./img/c1.png" alt="html">
        <h5> C++ is an object-oriented programming languagecan be found in today's operating systems.</h5>
    </div>
    <div class="box">
        <img src="./img/sql.png" alt="html">
        <h5>SQL is a programming language for storing and processing information in a relational database.</h5>
    </div>
    <div class="box">
        <img src="./img/ang.png" alt="html">
        <h5>Angular is written in TypeScript applies core and optional functionality that import into applications.</h5>
    </div>
    <div class="box">
        <img src="./img/node.png" alt="html">
        <h5>Node.js is an open-source javascript environment tool for almost any kind of project! </h5>
    </div>
    <div class="box">
        <img src="./img/react.png" alt="html">
        <h5>React is an open-source JavaScript library for building user interfaces. It is efficient, and flexible.</h5>
    </div>
    <div class="box">
        <img src="./img/spring.png" alt="html">
        <h5>The Spring codifies formalized design patterns as that you can integrate into your own application(s)</h5>
    </div>
    </div>
    <div class="foot">
        <h4>Copyright &#169; 2023 D-Code Private Limited, Developed by Sri Vignesh G</h4>
    </div>
</body>
</html>
```
#### Product.css
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>product.d-code</title>
    <link rel="stylesheet" href="./css/product.css">
</head>
<body bgcolor="gray">
    <div class="header">
        <nav>
            <h1 class="name"><</h1>
            <h1 class="name">D-C<span>ode></span></h1>
            <ul>
                <li><a href="home.html">Home |</a></li>
                <li><a href="product.html">Product |</a></li>
                <li><a href="about.html">About Us |</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>
    <div class="title">
        <h1 class="nm">Store:</h1>
    </div>
    <div class="hold" style="margin-left: 6%;">
        <div class="box">
            <img src="./img/html.png" alt="html">
            <h5>HTML is a markup language that tells web browsers how to structure the web pages you visit.</h5>
        </div>
        <div class="box">
            <img src="./img/css.png" alt="css">
            <h5>Cascading Style Sheets (CSS) is a computer language that structures and lays out web pages.</h5>
        </div>
        <div class="box">
            <img src="./img/js.png" alt="javascript">
            <h5>JavaScript is used to make web pages interactive and to add dynamic content to web pages</h5>
        </div>
        <div class="box">
            <img src="./img/java.png" alt="html">
            <h5>Java is an object oriented language (OOP).It helps to write a code once and run it anywhere.</h5>
        </div>
        <div class="box">
            <img src="./img/php.png" alt="html">
            <h5>PHP from PHP group is a general-purpose scripting language geared towards web development.</h5>
        </div>
        <div class="box">
            <img src="./img/c.png" alt="html">
            <h5>It is powerful and general-purpose language used in programming. prefered for beginners</h5>
        </div>
    <br>
    <div class="box">
        <img src="./img/c1.png" alt="html">
        <h5> C++ is an object-oriented programming languagecan be found in today's operating systems.</h5>
    </div>
    <div class="box">
        <img src="./img/sql.png" alt="html">
        <h5>SQL is a programming language for storing and processing information in a relational database.</h5>
    </div>
    <div class="box">
        <img src="./img/ang.png" alt="html">
        <h5>Angular is written in TypeScript applies core and optional functionality that import into applications.</h5>
    </div>
    <div class="box">
        <img src="./img/node.png" alt="html">
        <h5>Node.js is an open-source javascript environment tool for almost any kind of project! </h5>
    </div>
    <div class="box">
        <img src="./img/react.png" alt="html">
        <h5>React is an open-source JavaScript library for building user interfaces. It is efficient, and flexible.</h5>
    </div>
    <div class="box">
        <img src="./img/spring.png" alt="html">
        <h5>The Spring codifies formalized design patterns as that you can integrate into your own application(s)</h5>
    </div>
    </div>
    <div class="foot">
        <h4>Copyright &#169; 2023 D-Code Private Limited, Developed by Sri Vignesh G</h4>
    </div>
</body>
</html>
```
### AboutPage:
#### about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About.D-Code</title>
    <link rel="stylesheet" href="./css/about.css">
</head>
<body style="background-color: gray">
    <div class="header">
        <nav>
            <h1 class="name"><</h1>
            <h1 class="name">D-C<span>ode></span></h1>
            <ul>
                <li><a href="home.html">Home |</a></li>
                <li><a href="product.html">Product |</a></li>
                <li><a href="about.html">About Us |</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>
    <div class="title">
        <h1 class="abt" style="text-align: center; padding-top: 20px; font-size: 50px;">About Us</h1>
    </div>
    <div class="ctnt">
        <h5>Do you want to learn programming in a simple and fun way? Then you should visit our website and discover the amazing world of coding. Whether you are a beginner or an expert, you will find something useful and interesting on our platform. And don't worry, D-Code.team is always there to help you with any questions or problems you might have. Join us today and start your coding journey with us!
        </h5>
    </div>
    <div class="people">
        <div class="ceo">
            <img src="./img/me.jpg" alt="ceo">
            <h4>Sri Vignesh G</h4>
            <p>Founder</p>
        </div>
        <div class="ceo">
            <img src="./img/ceo.jpeg" alt="ceo">
            <h4>Jeff Bezos</h4>
            <p>CEO</p>
        </div>
        <div class="ceo">
            <img src="./img/aceo.jpeg" alt="ceo">
            <h4>mark</h4>
            <p>Asnt.CEO</p>
        </div>
        <div class="ceo">
            <img src="./img/hr.jpeg" alt="ceo">
            <h4>Nithilan</h4>
            <p>Proj manager</p>
        </div>
        <div class="ceo">
            <img src="./img/pm.jpeg" alt="ceo">
            <h4>Sanjay ashwin</h4>
            <p>HR</p>
        </div>
        <div class="ceo">
            <img src="./img/tl.jpeg" alt="ceo">
            <h4>Kavin</h4>
            <p>Team Leader</p>
        </div>
    </div>
    <div class="foter">
        <h4>Copyright &#169; 2023 D-Code Private Limited, Developed by Sri Vignesh G</h4> 
     </div>
</body>
</html>
```
#### about.css
```
*{
    margin: 0%;
    padding: 0%;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.header{
    background-color: rgb(80, 90, 87);
    border-bottom-left-radius: 30px;
    border-bottom-right-radius: 30px;
    height: 100px;
}
span{
    color: rgb(255, 255, 255);
}
ul,li{
    display: inline;
}
ul{
    margin-left: 43%;
}
.name{
    display: inline-block;
    margin-top: 15px;
    font-size: 65px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
a{
    font-size: 25px; 
    color: black;
}
a:hover{
    color: white;
    cursor: pointer;
}
.people{
    margin-left: 20%;
}
.ctnt{
    padding: 20px;
}
.ceo{
    display: inline-block;
    background-color: gray;
    height: 240px;
    width:130px;
    border-radius: 30px;
    text-align: center;
}
h4,p{
    text-align: left;
    padding: 2px;
}
.ceo:hover{
    background-color: black;
    color: white;
}
img{
    display: inline-block;
    height: 150px;
    width: 100px;
    border-radius: 60px;
    padding: 10px;
}
.foter{
    display: block;
    color: rgb(7, 7, 7);
    margin-top: 100px;
    padding: 5px;
    margin-left: 30%;
}
```
### ContactPage
#### conatct.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact.D-Code</title>
    <link rel="stylesheet" href="./css/contact.css">
</head>
<body style="background-color: gray;">
    <div class="header">
        <nav>
            <h1 class="name"><</h1>
            <h1 class="name">D-C<span>ode></span></h1>
            <ul>
                <li><a href="home.html">Home |</a></li>
                <li><a href="product.html">Product |</a></li>
                <li><a href="about.html">About Us |</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </div>
    <div class="title">
        <h1>Contact Us</h1>
    </div>
    <div class="container">
    <div class="form">
    <input type="text" class="pnm" placeholder="Enter Name">
    <input type="text" class="pnm" placeholder="Enter Mobile.No"><br>
    <input type="text" class="query" placeholder="Enter Queries"><br>
    <button>Submit</button>
    </div>
    <div class="info">
        <h2>Contact info:</h2>
        <h3>phone: +91 7548841149</h3>
        <h3>Email: D-Codequery@gmail.com</h3>
        <h3>Location</h3>
        <p>	East Asia Europe,<br>Middle East North America,<br> Oceania Southeast Asia <br>INDIA</p>
        <h3>Note:</h3>
        <p>Any queries should be resolved within 7 working days.</p>
    </div>
    </div>
    <div class="footer" style="margin-top: 30px; text-align: center;">
        <h4>Copyright &#169; 2023 D-Code Private Limited, Developed by Sri Vignesh G</h4> 
    </div>
</body>
</html>
```
#### contact.css
```
*{
    margin: 0%;
    padding: 0%;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.header{
    background-color: rgb(80, 90, 87);
    border-bottom-left-radius: 30px;
    border-bottom-right-radius: 30px;
    height: 100px;
}
span{
    color: rgb(255, 255, 255);
}
ul,li{
    display: inline;
}
ul{
    margin-left: 43%;
}
.name{
    display: inline-block;
    margin-top: 15px;
    font-size: 65px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
a{
    font-size: 25px; 
    color: black;
}
a:hover{
    color: white;
    cursor: pointer;
}
.title{
    text-align: center;
    padding: 20px;
    font-size: x-large;
}
.container{
    margin-left: 180px;
    vertical-align: top;
    display: flex;
    flex-direction: row;
}
.form{
    display: inline-block;
    height: 350px;
    width: 500px;
    background-color: rgb(151, 155, 155);
    font-size: 50px;
    font-weight: bolder;
    padding: 20px;
}
.pnm{
    width: 280px;
    height: 50px;
    display: inline;
    margin-left: 15px;
    background-color: transparent;
}
input::placeholder{
    padding: 10px;
    font-size: 30px;
    color: black;
}
.query{
    margin-top: 15px;
    font-size: 30px;
    padding-bottom: 50px;
    height: 80px;
    margin-left: 15px;
    background-color: transparent;
}
button{
    width: 100px;
    height: 50px;
    margin-left: 15px;
    background-color: rgb(70, 68, 68);
    border-radius: 40px;
    border: none;
}
button:hover{
    background-color: black;
    color: white;
}
.info{
    margin-left: 20px;
    display: inline-block;
    height: 390px;
    width: 500px;
    background-color: rgb(12, 12, 12);
    color: white;
}
h2{
    padding: 13px;
}
h3{
    padding-left: 30px;
    font-family: sans-serif;
    padding: 13px;
}
p{
    margin-left: 40px;
}
h5{
    display: inline;
    margin-left: 10px;
}
```

## OUTPUT:
![collage](https://github.com/SriVignesh-G/productcompanywebsite/assets/147576510/b34e53c6-0584-4fed-a7de-1a04a150caae)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
