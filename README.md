# Ex.07 Restaurant Website
# Date:05/12/24
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

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurants Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff5733;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
        }
        .restaurant {
            margin-bottom: 20px;
            border: 1px solid #ccc;
            padding: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Popular Restaurants</h1>
</header>

<nav>
    <a href="#italian">Italian</a>
    <a href="#chinese">Chinese</a>
    <a href="#mexican">Mexican</a>
</nav>

<div class="content">
    <section id="italian">
       <center><h2>Italian Restaurants</h2>
        <div class="restaurant">
            <img src="olive garden.jpg" alt="image olive garden">
            <h3>Olive Garden</h3>
            <p>Enjoy authentic Italian dishes and a cozy atmosphere.</p>
            <h3 >Famous Food</h3>
            <P style=>Chicken Alfredo.<br> 
                Chicken and Shrimp Carbonara.  <br>
                Chicken Parmigiana.  <br>
                Chicken Tortelloni Alfredo.<br>  
                Eggplant Parmigiana. <br>
                Five Cheese Ziti al Forno. </P>
        </div>
        <div class="restaurant">
            <img src="carbone.jpg" alt="carbone image">
            <h3>Carbone</h3>
            <p>Experience classic Italian dining in a vibrant setting.</p>
        </div>
    </section></center>

    <center><section id="chinese">
        <h2>Chinese Restaurants</h2>
        <div class="restaurant">
            <img src="panda express.jpg" alt="panda express">
            <h3>Panda Express</h3>
            <p>Fast-casual dining featuring Chinese-American cuisine.</p>
        </div>
        <div class="restaurant">
            <img src="hakkasan.jpg" alt="hakkasan image">
            <h3>Hakkasan</h3>
            <p>Elegant dining with a modern twist on traditional Chinese dishes.</p>
        </div>
    </section></center>

    <center><section id="mexican">
        <h2>Mexican Restaurants</h2>
        <div class="restaurant">
            <img src="chipotle.jpg" alt="chipotle">
            <h3>Chipotle</h3>
            <p>Build your own burritos, bowls, and tacos with fresh ingredients.</p>
        </div>
        <div class="restaurant">
            <img src="el torito.jpg" alt="el torito image">
            <h3>El Torito</h3>
            <p>Enjoy a variety of traditional Mexican dishes in a festive atmosphere.</p>
        </div>
    </section></center>
</div>
<footer>
    <p>&copy; 2024 Restaurants Guide. All rights reserved.</p>
</footer>

</body>
</html>

```
# OUTPUT:
![Screenshot 2024-12-25 144856](https://github.com/user-attachments/assets/bd88e861-cf7a-45b1-9f56-88b08935878d)
![Screenshot 2024-12-25 144919](https://github.com/user-attachments/assets/83d15179-9e2b-4744-bdd6-08d80d7c2e89)
![Screenshot 2024-12-25 145105](https://github.com/user-attachments/assets/975b76f1-9db2-4b8a-bba4-174336b92ae5)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
