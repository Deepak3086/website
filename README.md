# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Italian Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color :white;
            color: rgb(6, 169, 34);
        }
        header .logo {
            display: flex;
            padding-left: 40%;
            align-items: center;
        }
        header .logo img {
            height: 50px;
            margin-right: 10px;
        }
        nav a {
            margin: 0 10px;
            color: rgb(13, 213, 53);
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: url('c:/Users/admin/Downloads/lasagna background image with size 1200X400.png') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 100px 20px;
            position: relative;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .cards {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .card {
            background-color: #fdf4e3;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 30%;
            text-align: center;
            padding: 20px;
        }
        .card img {
            width: 100%;
            border-radius: 8px;
        }
        .card h2 {
            margin-top: 15px;
            font-size: 1.5rem;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="c:\Users\admin\Pictures\restaurant pictures\logo.webp" alt="Logo">
            <h1>Sapori Di Italia</h1>
        </div>
        <nav>
            <a href="C:\Users\admin\Desktop\web development\booking.html">Book now</a>
            <a href="C:\Users\admin\Desktop\web development\menu.html">Menu</a>
            <a href="C:\Users\admin\Desktop\web development\About.html">About</a>
            <a> Contact us</a>

        </nav>
    </header>

    <div class="hero">
        <h1>40% Off This Weekend</h1>
        <p>Where Taste Meets Luxury.</p>
    </div>

    <div class="cards">
        <div class="card">
            <img src="c:\Users\admin\Downloads\menu bg.webp" alt="Our New Menu">
            <h2>Our New Menu</h2>
        </div>
        <div class="card">
            <img src="c:\Users\admin\Downloads\Italian restaurant table booking background.png" alt="Book a Table">
            <h2>Book a Table</h2>
        </div>
        <div class="card">
            <img src="c:\Users\admin\Pictures\restaurant pictures\opening.png" alt="Opening Hours">
            <h2>Opening Hours</h2>
        </div>
    </div>

    <footer>
        <p>© 2024 Sapori Di Italia. All rights reserved.</p>
    </footer>
</body>
</html>
~~~
# OUTPUT:
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
