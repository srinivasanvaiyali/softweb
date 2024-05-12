# Ex.07 Software Product Company Website
## Date: 12.05.24
## name: Srinivasan V
## Reg no: 212222043008

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
## home
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>BATMAN</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'playfair display';                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center; 
                background-color:rgb(134, 228, 134);
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(0, 0, 0);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
                padding-left: 10px;
            }
            span {
                color: rgb(0, 0, 0);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgba(255, 0, 174, 0.823);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgba(250, 215, 18, 0.49);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: yellow;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
	    .text h3 {
                color: white;
                font-weight: 800;
                font-size: 22px;
                letter-spacing: 3px;
            }
	
            .text p {
                color: white;
                text-transform: capitalize;
                font-size: 17px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
	
            }
                footer {
                    color: aliceblue;
                background-color: rgb(0, 0, 0);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>BATMAN SOFTWARE SOLUTIONS</span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="products.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2><span> SOFTWARE DEVELOPMENT </span></h2>
                <br>
		<h3></h3>
		<br>
                <p>We blend innovation with expertise to craft bespoke software that drives your success. From streamlined workflows to immersive user experiences, trust us to elevate your digital presence. Let's transform your ideas into reality. Elevate your software, elevate your business with us.</p>
                <br>
                
            </div>
        </div>  
    </div>
    <footer>
        <center> Copyright@2024 Developed By Srinivasan V (212222043008) </center>
    </footer>
</body>
</html>
```

## Products
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>BATMAN</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'playfair display';
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
                background-color:rgb(228, 167, 134);
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(200, 29, 149);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(0, 0, 0);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(0, 0, 0, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:rgb(255, 255, 255);
                border-radius: 10px;
                background:rgba(255, 0, 174, 0.823);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgb(160, 124, 127);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 10px;
                background: transparent;
                border: 1px solid white;
                padding: 10px 5px;
            }
            .container .box-container .box img {
                height: 50px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color: rgb(0, 0, 0);
                font-size: larger;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: larger;
                line-height: 1.5;
            }
            footer {
                color: aliceblue;
                background-color: rgb(41, 37, 20);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>BATMAN SOFTWARE SOLUTIONS</span></h1>
            <ul>
                <li><a href="Home.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="pics\Circle Illustrations Photos and Premium High Res Pictures.jpeg" alt="">
                    <h3>Framework</h3>
                    <p>A software framework provides a foundation for developing applications. Examples include AngularJS for web development, TensorFlow for machine learning, and Django for web applications.</p>
                </div>

                <div class="box">
                    <img src="pics\download (14).jpeg" alt="">
                    <h3>Compiler</h3>
                    <p> A compiler translates code written in one programming language into another language, typically machine code or bytecode. Examples include GCC for C/C++ and Java compilers for Java programming language. </p>
                </div>

                <div class="box">
                    <img src="pics\Cloud computing black vector concept.jpeg"alt="">
                    <h3>Cloud Computing Service</h3>
                    <p>Offerings such as Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS) for scalable and flexible cloud hosting solutions.</p>
                </div>
               
                <div class="box">
                    <img src="pics\Data Analytics Clipart Transparent PNG Hd, Data Analytic Static Vector Icon, Data Icons, Analytics, Icon PNG Image For Free Download.jpeg" alt="">
                    <h3>Data Analytics Platform</h3>
                    <p>A comprehensive tool for businesses to collect, analyze, and visualize their data, enabling informed decision-making.</p>
                </div>
                <div class="box">
                    <img src="pics\Automatically machine icon.jpeg" alt="">
                    <h3>Workflow Automation Software</h3>
                    <p> Products to automate repetitive tasks and streamline business processes, improving efficiency and productivity.</p>
                </div>
 
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed By Srinivasan V (212222043008) </center>
    </footer>
</body>
</html>
```
## PERSON 
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>BATMAN</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'playfair display';                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(228, 200, 134);
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:gold;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(221, 27, 182);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:rgb(222, 22, 172);
                border-radius: 10px;
                background:rgb(255, 0, 170);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: white;
                position: relative;
                left: 200px;
            }
            .image table img {
                height: 250px;
                width: 250px;
                border: 2px solid yellow;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: yellow;
            }
            footer {
                color: aliceblue;
                background-color: rgb(0, 0, 0);
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>BATMAN SOFTWARE SOLUTIONS</h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div> 
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="pics\SRINI.jpeg"> </td>
                    <td> <img src="pics\rubesh.jpeg"> </td>
                    <td> <img src="pics\KAVI.jpeg"> </td>
                    <td> <img src="pics/INDHU.jpeg"> </td>
                    
                </tr>
                <tr align="center">
                    <th>SRINIVASAN</th>
                    <th>RUBESH</th>
                    <th>KAVISREE</th>
                    <th>INDRAJA</th>
                   
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> Co-Founder </td>
                    <td> CTO </td>
                    <td> Director </td>
                    
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed By Srinivasan V (212222043008) </center>
    </footer>
</body>
</html>
```
## contact
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>BATMAN</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'playfair display';                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: 100%;
                background-size: cover;
                background-color:rgb(134, 220, 228);

            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(0, 0, 0);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
                font-family: copperplate 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            }
            span {
                color: rgb(0, 0, 0);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: fixed;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(0, 0, 0);
            } 
            ::placeholder {
                color: rgb(0, 0, 0);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgba(255, 0, 174, 0.823);
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgba(255, 217, 0, 0.523);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 500px;
                border: 3px solid rgb(255, 255, 255);
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: rgb(255, 255, 255);
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid rgb(255, 255, 255);
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: rgb(255, 241, 241);
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: rgb(255, 255, 255);
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 15px;
                border: 1px solid rgb(255, 255, 255);
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: rgb(255, 255, 255);
                border-radius: 30px;
                background: rgb(0, 0, 0);
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: rgb(0, 0, 0);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: rgb(255, 255, 255);
                position: relative;
                top: 50px;
                
                padding: 10px 80px;
            }
            .box-2 span {
                color: rgb(255, 255, 255);
                font-size: 30px;
            }
            footer {
                color: aliceblue;
                background-color: rgb(0, 0, 0);
                margin-top: auto;
            }
        </style>
    </head>
<body></body>
    <div class="banner">
     
        <br>
        <div class="navbar">
            <h1 class="logo"><span>BATMAN SOFTWARE SOLUTIONS</span></h1>
            <ul>
                <li><a href="Home.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> <span>Contact Us </span></h1>
                        <input type="text"  placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="30" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information</h2>
                <p><span> Address</span>: <br> NO 99,POND AREA, 9TH CROSS STREET, KILAMBAKKAM, CHENNAI TN IN 600034. </p>
                <p> <span>Email</span> :<br> batmansoftwaresolutions@gmail.com
                <p> <span>Phone</span>:<br> 9686764656</p>
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed By Srinivasan V (212222043008) </center>
    </footer>
</body>
</html>
```

## OUTPUT:
![home 7](https://github.com/srinivasanvaiyali/softweb/assets/145117665/dc20bef8-aaf8-453c-918b-a1d39da83376)
![products 7](https://github.com/srinivasanvaiyali/softweb/assets/145117665/4a954ccd-3132-4827-978b-dd63d5d50cab)
![person 7](https://github.com/srinivasanvaiyali/softweb/assets/145117665/bad97dfd-27a9-4e74-9f50-9c9305c7622a)
![CONTACT 7](https://github.com/srinivasanvaiyali/softweb/assets/145117665/7e6fd1b4-64f3-4b3d-9682-cf224b275301)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
