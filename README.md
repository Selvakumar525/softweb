# Ex.07 Software Product Company Website
## Date:

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
# home.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
        <div class="content">
            <h1>A Software Agency shaping <br><span>ideas into</span> <br>Products</h1>
            <p class="par"><b>"People who are really serious about software <br>should make their own hardware" - Alan Kay. 
                </b></p>

                <button class="cn"><a href="#">JOIN US</a></button>

                <div class="form">
                    <h2>Login Here</h2>
                    <input type="email" name="email" placeholder="Username or Email">
                    <input type="password" name="" placeholder="Password">
                    <button class="btnn"><a href="#">Login</a></button>

                    <p class="link">Don't have an account<br>
                    <a href="#">Sign up </a> here</a></p>
                    <p class="liw">Log in with</p>

                    <div class="icons">
                        <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-google"></ion-icon></a>
        
                    </div>

                </div>
                    </div>
                </div>
        </div>
    </div>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
</body>
</html>
~~~
# style.css
~~~
*{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background: linear-gradient(to top, rgba(124, 70, 115, 0.5)50%,rgba(207, 21, 21, 0.5)50%), url(1.jpg);
    background-position: center;
    background-size: cover;
    height: 100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color: #5500dd;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
    margin-top: 5px
}

.menu{
    width: 400px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover{
    color: #ff7200;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}

.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}

.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
    transition: 0.2s ease;
    cursor: pointer;
}
.btn:hover{
    color: #000;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.content{
    width: 1200px;
    height: auto;
    margin: auto;
    color: #fff;
    position: relative;
}

.content .par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}

.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;
}

.content .cn{
    width: 160px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;
    
}

.content .cn a{
    text-decoration: none;
    color: #000;
    transition: .3s ease;
}

.cn:hover{
    background-color: #fff;
}

.content span{
    color: #ff7200;
    font-size: 65px
}

.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position: absolute;
    top: -20px;
    left: 870px;
    transform: translate(0%,-5%);
    border-radius: 10px;
    padding: 25px;
}

.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color: #ff7200;
    font-size: 22px;
    background-color: #fff;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}

.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #ff7200;
    border-top: none;
    border-right: none;
    border-left: none;
    color: #fff;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}

.form input:focus{
    outline: none;
}

::placeholder{
    color: #fff;
    font-family: Arial;
}

.btnn{
    width: 240px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: #fff;
    transition: 0.4s ease;
}
.btnn:hover{
    background: #fff;
    color: #ff7200;
}
.btnn a{
    text-decoration: none;
    color: #000;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color: #ff7200;
}
.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}
.icons a{
    text-decoration: none;
    color: #fff;
}
.icons ion-icon{
    color: #fff;
    font-size: 30px;
    padding-left: 14px;
    padding-top: 5px;
    transition: 0.3s ease;
}
.icons ion-icon:hover{
    color: #ff7200;
}
~~~
# people.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="peo.css">
    <title>People</title>
</head>
<body>

    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
    <div class="centered-content">
        <div class="people-grid">
            <div class="person">
                <div class="circle-box">
                    <img src="person1.png" alt="Person 1">
                </div>
                <h3>Sundar Pichai</h3>
                <p>CEO</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person2.png" alt="Person 2">
                </div>
                <h3>Eleanor Bolton</h3>
                <p>CEO,Co-Founder</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person3.png" alt="Person 3">
                </div>
                <h3>Caspian Shields</h3>
                <p>CTO,Co-Founder</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person4.png" alt="Person 4">
                </div>
                <h3>Marek Goodman</h3>
                <p>CFO</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person5.png" alt="Person 5">
                </div>
                <h3>Lisa WhiteHouse</h3>
                <p>CMO</p>
            </div>
            <div class="person">
                <div class="circle-box">
                    <img src="person6.png" alt="Person 6">
                </div>
                <h3>Buster Mckenize</h3>
                <p>COO</p>
            </div>
        </div>
    </div>
</body>
</html>
~~~
# peo.css
~~~
peo.css

*{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background: linear-gradient(to top, rgba(124, 70, 115, 0.5)50%,rgba(207, 21, 21, 0.5)50%), url(1.jpg);
    background-position: center;
    background-size: cover;
    height: 100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color: #5500dd;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
    margin-top: 5px
}

.menu{
    width: 400px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover{
    color: #ff7200;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}

.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
    transition: 0.2s ease;
    cursor: pointer;
}
.btn:hover{
    color: #000;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

/* Center the content on the page */
.centered-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* Style the people grid */
.people-grid {
    display: flex; /* Use flexbox to arrange people horizontally */
    justify-content: space-between; /* Distribute space between people */
    gap: 20px; /* Gap between people */
    padding: 20px;
}

/* Style individual people */
.person {
    text-align: center;
}

/* Style the circular image container */
.circle-box {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    overflow: hidden;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);
}

.circle-box img {
    max-width: 100%;
    height: auto;
    border: 1px solid #ddd;
}

.person h3 {
    margin: 10px 0;
    font-size: 18px;
}

.person p {
    font-size: 16px;
}
~~~
# product.html
~~~
product.html

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Webpage Design</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .product-image {
            text-align: center;
        }

        .product-image img {
            max-width: 100%;
            max-height: 100%;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"><button class="btn">Search</button></a>
            </div>
        </div> 

        <div class="product-image">
            <img src="image.jpeg" alt="Product Name" width="800" height="600">
        </div>
    </div>
</body>
</html>
~~~

# contact.html
~~~
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="cont.css">
    <title>Contact Us</title>
</head>
<body>
 <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">VirtuTech Solutions</h2>
            </div>

            <div class="menu">
                <ul>
                    <li><a href="home.html">HOME</a></li>
                    <li><a href="people.html">PEOPLES</a></li>
                    <li><a href="product.html">PRODUCTS</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="search" name="" placeholder="Enter To Search">
                <a href="#"> <button class="btn">Search</button></a>
            </div>

        </div> 
    <div class="container">
        <div class="contact-form">
            <h1>Contact Us</h1>
            <form action="submit_form.php" method="POST">
                <div class="form-group">
                    <input type="text" id="name" name="name" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <input type="email" id="email" name="email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                </div>
                <button type="submit">Submit</button>
            </form>
        </div>
        <div class="contact-info">
            <h2>Contact Information</h2>
            <p><strong>Address:</strong> 123 Main Street,Tiruvallur,Chennai</p>
            <p><strong>Email:</strong> virtutech@gmail.com</p>
            <p><strong>Phone:</strong>044-0804</p>
        </div>
    </div>
</body>
</html>
~~~
# contt.css
~~~
cont.css
*{
    margin: 0;
    padding: 0;
}

.main{
    width: 100%;
    background: linear-gradient(to top, rgba(124, 70, 115, 0.5)50%,rgba(207, 21, 21, 0.5)50%), url(1.jpg);
    background-position: center;
    background-size: cover;
    height: 100vh;
}

.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}

.logo{
    color: #5500dd;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float: left;
    padding-top: 10px;
    margin-top: 5px
}

.menu{
    width: 400px;
    float: left;
    height: 70px;
}

ul{
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
}

ul li{
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;
}

ul li a:hover{
    color: #ff7200;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}

.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
    transition: 0.2s ease;
    cursor: pointer;
}
.btn:hover{
    color: #000;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background-color: #fff;
    display: flex;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    text-align: center;
}

.contact-form, .contact-info {
    padding: 20px;
    flex: 1;
}

.contact-form {
    text-align: left;
}

h1 {
    color: #333;
}

h2 {
    color: #333;
}

.form-group {
    margin: 10px 0;
}

input[type="text"],
input[type="email"],
textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    background-color: #007BFF;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}
~~~
## OUTPUT:
# home.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/e5989efe-13d5-44c7-a39b-df6525ec0340)

# people.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/ffebfa81-80be-4856-acc9-8847bf9cf265)

# product.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/40ed9f57-60bd-4b3f-ad8e-aa1406d65b35)

# contact.html:
![image](https://github.com/Selvakumar525/softweb/assets/120643262/db76663e-197b-441a-98ae-7923bc826638)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
