# Ex.07 Restaurant Website
# Date:8/12/24
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
## index.hml
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAVEETHA UNAVAGAM</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Labrada:ital,wght@0,100..900;1,100..900&family=Lobster&family=Paytone+One&family=Spicy+Rice&display=swap" rel="stylesheet">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>
    <DIv>
        <div class="banner">
            <img class="fil" src="Landing Page.png" alt="">
            <div>
                <h1 class="te1">WELCOME TO SAVEETHA UNAVAGAM</h1>
                <p class="te2">Menus can vary from simple to elaborate, with options ranging from à la carte (ordering individual items) to prix fixe (set menus at a fixed price).
                   Dining experiences often vary by restaurant style, with casual settings offering quick, informal service, while fine dining places offer a slower-paced, more formal experience.
                   Chefs: Responsible for preparing the food. In fine dining, there may be multiple chefs specializing in different areas (e.g., pastry chefs, sous chefs).
                   
                  
                </p>
            </div>
        </div>
    </DIv>
    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>

```
## menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Food Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="style2.css">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>
    <div class="menu-section">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="download.jpg" alt="ICE CREAMS">
                <h3>ICE CREAMS</h3>
                <p><strong>140</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.kannammacooks.com/wp-content/uploads/street-style-chicken-rice-recipe-1-3.jpg" alt="CHICKEN RICE">
                <h3>CHICKEN RICE</h3>
                <p><strong>990</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://pipingpotcurry.com/wp-content/uploads/2024/04/Chicken-Biryani-Piping-Pot-Curry.jpg" alt="BIRIYANI">
                <h3>BIRIYANI</h3>
                <p><strong>1100</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://thefriendlyepicurean.com/wp-content/uploads/2020/06/img_5490.jpg" alt="CHAPATI">
                <h3>CHAPATI</h3>
                <p><strong>200</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2022/03/chicken-65-restaurant-style-500x375.jpg" alt="CHICKEN LOLLIPOP">
                <h3>CHICKEN 65</h3>
                <p><strong>800</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSP-kCOFzi3mmfoN0Gx-Z34Z4iJmurmg02YWw&s" alt="MAGGI">
                <h3>MIO AMORE</h3>
                <p><strong>400</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://butfirstchai.com/wp-content/uploads/2023/03/yemeni-chicken-mandi-recipe.jpg" alt="MANDHI RICE">
                <h3>MANDHI RICE</h3>
                <p><strong>2500</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://thewhiskaddict.com/wp-content/uploads/2024/01/IMG_9911-scaled.jpg" alt="PAROTTA">
                <h3>PAROTTA</h3>
                <p><strong>250</Strong></p>
                    </DIV>
            <div class="menu-item">
                <img src="https://www.ohmyveg.co.uk/wp-content/uploads/2023/07/Idli-1-scaled-e1722868852202-720x720.jpg" alt="IDLY">
                <h3>IDLY</h3>
                <p><strong>500</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.cookwithmanali.com/wp-content/uploads/2020/05/Masala-Dosa.jpg" alt="DOSAI">
                <h3>DOSAI</h3>
                <p><strong>120</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2020/12/poori-puri-recipe.jpg" alt="PURI">
                <h3>PURI</h3>
                <p><strong>150</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://d2jx2rerrg6sh3.cloudfront.net/image-handler/picture/2018/4/shutterstock_1By_stockcreations.jpg" alt="JUICE">
                <h3>JUICE</h3>
                <p><strong>70</Strong></p>
                </diV>
            
</body>
</html>

```
## administaration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Food Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h2>Meet Our Team</h2>
        <div class="team-member">
            <img src="https://images.squarespace-cdn.com/content/v1/57a6a44d2994ca6cbb9460b6/0326d596-2813-4e05-b225-1221a845e2b8/IMG_2256.jpeg" alt="Person 1">
            <h3>Dr. N.M. Veeraiyan - founder</h3>
        </div>
        <div class="team-member">
            <img src="https://pbs.twimg.com/profile_images/1835616750349750272/rMh3Kno__400x400.jpg" alt="Person 2">
            <h3>Madhampatty Rangaraj - Manager</h3>
        </div>
        <div class="team-member">
            <img src="https://kgo.googleusercontent.com/profile_vrt_raw_bytes_1587515369_10614.jpg" alt="Person 3">
            <h3>Sanjeev Kapoor  - Chef</h3>
        </div>
        <div class="team-member">
            <img src="https://yt3.googleusercontent.com/4G1SgaqEl81izq095JJwYmOawkBLEnMVBUP81Pef8uGTq80zn25FI2fzz2uwLRm7E0wN2QKj=s900-c-k-c0x00ffffff-no-rj" alt="Person 4">
            <h3>Venkatesh Bhat - Sous Chef</h3>
        </div>
        <div class="team-member">
            <img src="https://www.shutterstock.com/image-photo/young-african-waitress-wearing-apron-260nw-1059547040.jpg" alt="Person 5">
            <h3>Sarah Williams - Waitstaff</h3>
        </div>
        <div class="team-member">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsC-lw3T2Fzg9GxJ15q3UbCOixaWI17Z4fEw&s" alt="Person 6">
            <h3>David Lee - Waitstaff</h3>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>

```
## contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - My Food Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h2>Contact Us</h2>
        <p>Address: 123 Food Street, Food City, FC 12345</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: info@foodwebsite.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>

```
## register.html
```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <form action="/action_page.php">
    <h2>Register Form</h2>
    <div class="input-container">
      <i class="fa fa-user icon"></i>
      <input class="input-field" type="text" placeholder="Username" name="usrnm">
    </div>
  
    <div class="input-container">
      <i class="fa fa-envelope icon"></i>
      <input class="input-field" type="text" placeholder="Email" name="email">
    </div>
  
    <div class="input-container">
      <i class="fa fa-key icon"></i>
      <input class="input-field" type="password" placeholder="Password" name="psw">
    </div>
  
    <button type="submit" class="btn">Register</button>
</form>
</body>
</html>
```
## style.css
```

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}
.title{
    font-family: Arial, Helvetica, sans-serif;
    font-size: xx-large;
    font-weight: bolder;
    text-align: center;
    background-color:#e8ce0b;
    margin: auto;
    padding: 1%;
    display: block;

}
header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}
.img1{
    image-resolution: 100%;
    i
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

.banner {
    background-size: auto;
    color: rgb(238, 8, 8); 
    text-align: center;
    padding: 80px 0;
    background-color:#e8ce0b;
.fil{
  -webkit-filter: blur(5px); 
  filter: blur(3px);
  border-radius: 50px;
}    
    
}
.te1{
    font-family: "Labrada", serif;
    color:antiquewhite;
    position: absolute;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-shadow: #333;
    font-size: 60px;
    
} 
.te2{
    position: absolute;
    top: 80%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: "Labrada", serif;
    color:antiquewhite;
    font-size: 30px;
}


.menu {
    padding: 20px;
    background-color: #fff;
    text-align: center;
}

.menu h2 {
    font-size: 2em;
    color: #333;
}

.menu ul {
    list-style-type: none;
    padding: 0;
}

.menu ul li {
    font-size: 1.2em;
    margin: 10px 0;
}

.administration {
    padding: 20px;
    background-color: #fff;
    text-align: center;
}

.team-member {
    display: inline-block;
    width: 300px;
    margin: 100px;
    text-align: center;
}

.team-member img {
    width: 100%;
    border-radius: 40%;
}

.team-member h3 {
    font-size: 1.1em;
    color: #333;
}
.contact {
    padding: 20px;
    background-color: #fff;
    text-align: center;
}

.contact p {
    font-size: 1.2em;
    color: #333;
}
.lobster-regular {
    font-family: "Lobster", sans-serif;
    font-weight: 400;
    font-style: normal;
  }
  
* {box-sizing: border-box;}
 .input-container {
    display: flex;
    width: 100%;
    margin-bottom: 15px;
  }
  
.icon {
    padding: 10px;
    background: dodgerblue;
    color: white;
    min-width: 50px;
    text-align: center;
  }
.input-field {
    width: 100%;
    padding: 10px;
    outline: none;
  }
  
.input-field:focus {
    border: 2px solid dodgerblue;
  }
.btn {
    background-color: dodgerblue;
    color: white;
    padding: 15px 20px;
    border: none;
    cursor: pointer;
    width: 100%;
    opacity: 0.9;
  }
  
.btn:hover {
    opacity: 1;
  }
  
```
## style2.css
```
body{
    background-color:#e8ce0b;
    
}
.menu-items {
    display: flex;
    justify-content: center;
    gap: 50px;
    flex-wrap: wrap;
    margin-bottom: 10px;
}
.menu-item {
    background-color: #e6e5d8;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 250px;
    text-align: center;
}
.menu-item img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 5px;
}
.menu-item h3 {
    color: #2c3e50;
}
.menu-section {
    text-align: center;
    margin-top: 30px;
    background-color: #e8ce0b;
}![Screenshot 2024-12-08 193531](https://github.com/user-attachments/assets/61459c98-ba80-4a4a-953d-7c43e8cfc9d1)
![Screenshot 2024-12-08 193519](https://github.com/user-attachments/assets/28a3f698-9b7d-4d77-8d76-237c0dd3ebae)
![Screenshot 2024-12-08 193505](https://github.com/user-attachments/assets/dbb44f07-ea4f-49a1-a3c6-47004e2e530f)
![Screenshot 2024-12-08 193459](https://github.com/user-attachments/assets/66581ecc-8ff6-49dc-a7d9-77dd48666b8e)

.menu-section h2 {
    color: #2c3e50;
}


```

# OUTPUT:
![Screenshot 2024-12-08 193415](https://github.com/user-attachments/assets/c8e124df-830d-4f2e-a1f5-5c1943f2a584)
![Screenshot 2024-12-08 193408](https://github.com/user-attachments/assets/55057a22-370d-4d82-ba78-7f1fab1b9868)
![Screenshot 2024-12-08 193552](https://github.com/user-attachments/assets/55afb023-1aa0-4582-b9b1-a0ad53c83562)
![Screenshot 2024-12-08 193549](https://github.com/user-attachments/assets/23e7dfab-7b4b-414d-9522-5d58a0f5bcda)
![Screenshot 2024-12-08 193539](https://github.com/user-attachments/assets/e1ee954d-e555-4613-9b77-40012d8d9d95)
![Screenshot 2024-12-08 193505](https://github.com/user-attachments/assets/c9a7a0fb-0da2-460c-8217-62d4eef80817)
![Screenshot 2024-12-08 193539](https://github.com/user-attachments/assets/52146a63-f484-4a26-b073-e38d5bbcc5b2)
![Screenshot 2024-12-08 193531](https://github.com/user-attachments/assets/db3e4844-ef7c-4493-937a-91b6676b607b)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
