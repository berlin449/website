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

# PROGRAM: <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Delicious Bites | Restaurant</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f8f8f8;
        }

        /* Header */
        header {
            background-color: #b22222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #8b0000;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Sections */
        section {
            padding: 30px;
        }

        .aim {
            background-color: #fff3e0;
            border-left: 6px solid #ff9800;
        }

        .menu {
            background-color: white;
        }

        .menu-items {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .item {
            background-color: #fff;
            width: 220px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.2);
            text-align: center;
        }

        .item img {
            width: 100%;
            height: 140px;
            object-fit: cover;
            border-radius: 6px;
        }

        .services {
            background-color: #f1f1f1;
        }

        ul {
            line-height: 1.8;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>

<body>

<header>
    <h1>Delicious Bites</h1>
    <p>Fresh • Tasty • Hygienic</p>
</header>

<nav>
    <a href="#aim">Aim</a>
    <a href="#menu">Menu</a>
    <a href="#services">Services</a>
</nav>

<section id="aim" class="aim">
    <h2>Aim of the Project</h2>
    <p>
        To develop a static Restaurant website to display the food items and services provided by them.
    </p>
</section>

<section id="menu" class="menu">
    <h2>Our Menu</h2>

    <div class="menu-items">
        <div class="item">
            <img src="pizza.jpg" alt="Pizza">
            <h3>Pizza</h3>
            <p>Cheesy and delicious</p>
        </div>

        <div class="item">
            <img src="burger.jpg" alt="Burger">
            <h3>Burger</h3>
            <p>Juicy and tasty</p>
        </div>

        <div class="item">
            <img src="biryani.jpg" alt="Biryani">
            <h3>Biryani</h3>
            <p>Authentic Indian flavor</p>
        </div>

        <div class="item">
            <img src="dessert.jpg" alt="Dessert">
            <h3>Dessert</h3>
            <p>Sweet and delightful</p>
        </div>
    </div>
</section>

<section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
        <li>Dine-in Facility</li>
        <li>Online Ordering</li>
        <li>Home Delivery</li>
        <li>Party & Event Catering</li>
    </ul>
</section>

<footer>
    <p>© 2025 Delicious Bites Restaurant</p>
</footer>

</body>
</html>


# OUTPUT: <img width="1917" height="954" alt="bites" src="https://github.com/user-attachments/assets/bdd88c32-7f22-4543-a5be-8ea245e04a85" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
