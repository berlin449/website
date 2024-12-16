# Ex.07 Restaurant Website
# Date:5.12.2024
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

home page:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hotel tabemono.com </title>
    <link rel="icon" href="hotel logo 1.webp">
    <style>
        .head{
            display: inline;

        } 
         
         body{
            background-color: rgb(192, 251, 251);
         }  
    </style>

</head>
<body>
    <div class="head" style="background-color: blanchedalmond;">
        <hr><hr>
    <img src="hotel logo 1.webp" width="100px" style="float:left;">
    <ul style="float: right;">
        <li><a href="restaurant.html">HOME</a></li>
        <li><a href="menu.html">MENU...</a></li>
        <li><a href="order page.html">ORDER!!!</li>
        <li><a href="about us.html">ABOUT US</a></li>
    </ul>
    <h3 style="text-align: right;">opening time:3.00pm - 01.00am</h3>
    <h1 style="text-align: center;"> JANPANESE TABEMONO</h1>
    <h4 style="text-align: center;">enjoy eating japanese food.....</h4>
   
    <hr><hr>
</div>
<center>
    <div class="serchbar">
      <input placeholder="Search"> 
   </div></center>

    <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt delectus qui obcaecati, ipsum perspiciatis tenetur asperiores totam in labore, porro explicabo? Molestiae nihil expedita beatae dolorum optio sapiente obcaecati ipsa exercitationem soluta distinctio, culpa aspernatur adipisci laborum fugit eligendi delectus voluptates. Accusamus eligendi, accusantium nesciunt commodi saepe sapiente debitis consequatur architecto incidunt totam a doloribus, nihil esse tempora veritatis tenetur provident maxime inventore mollitia voluptatibus repellendus officia? Consequuntur itaque explicabo ut, aut ullam laboriosam voluptatum.</h3>
   <center>
        <img src="rest image.jpg" width="1000px"
        <img src="main sample.webp" width="600px" ></center>
        <h4>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci est repellendus temporibus, reiciendis perspiciatis officiis reprehenderit deleniti amet, recusandae ad officia molestias at esse quaerat et inventore illum voluptatum magni. At ipsa voluptate culpa suscipit libero quam vitae autem quidem.</h4>
       <center><hr><hr> <img src="sample 1.jpg" width="400px">
        <img src="sample 3.jpg" width="300px">
        <img src="sample 2.avif" width="300px">

        <hr><hr>
        <a href="menu.html">*****MENU*****</a><br>
        <a href="order page.html">!!!!!!ORDER NOW!!!!!!!</a><br>
        <a href="about us.html">.....ABOUT US....</a></center>
    <hr><hr>

</body>
</html>


menu page:
<html>
<head>
    <style>
        body{background-color: rgb(192, 251, 251);}
    table,th,td{
        border: 1px solid black;
        border-collapse: collapse;
        width: 50%;
        max-width:1000px;
        margin: 0;
        text-align: center
     }
    </style>
</head>
<body>
    <center><h1>
<table><tr>
            <th>Item Name</th>
            <th>Cost</th>
            <th>Item Code</th>
             <th>order page</th></tr>
            <tr>
                <td>sushi</td>
                <td>99₹</td>
                <td>001</td>
                <td><a href="order page.html">ORDER</a></td>
            </tr><tr>
                <td>ramen</td>
                <td>150₹</td>
                <td>002</td>
                <td><a href="order page.html">ORDER</a></td>
            </tr><tr>
                <td>tofu</td>
                <td>60₹</td>
                <td>003</td>
                <td><a href="order page.html">ORDER</a></td>
            </tr><tr>
                <td>yakitori</td>
                <td>50₹</td>
                <td>004</td>
                <td><a href="order page.html">ORDER</a></td>
            </tr><tr>
                <td>tonkatsu</td>
                <td>120₹</td>
                <td>005</td>
                <td><a href="order page.html">ORDER</a></td>
            </tr><tr>
                <td>miso soap</td>
                <td>60₹</td>
                <td>007</td>
                <td><a href="order page.html">ORDER</a></td>
            </tr><tr>
                <td>sukiyaki</td>
                <td>180₹</td>
                <td>008</td>
                <td><a href="order page.html">ORDER</a></td>
            </tr>
        </table><br><br></h1>
    </center>
    <hr><hr>
    
    <center><a href="restaurant.html">||Back||</a></center>
</body>
</html>

order page:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hotel tabemono.com </title>
    <link rel="icon" href="hotel logo 1.webp">
    <style>
        body{
            background-color: paleturquoise;
        }
    </style>
</head>
<body>
    <center>
    <h1 style="background-color: aqua;">ORDER PAGE!!!</h1>
    <form >
        <table>
            <tr>
                <td>Name</td><td><input type="text"></td>
            </tr>
            <tr>
                <td>address</td><td><input type="text"></td>
            </tr>
            <tr>
                <td>item code</td><td><input type="number"></td>
            </tr>
            <tr>
                <td>payment way</td>
                <td>
                    <select>
                        <option>Gpay</option>
                        <option>Phone pay</option>
                        <option>PayTM</option>
                        <option>amazon pay</option>
                        <option>others</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td></td><td>,<input type="submit"></td>
            </tr>
        </table>
    </form>
    <br><br>
        <a href="restaurant.html">||BACK||</a>
</center>
    
</body>
</html>

about us page:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hotel tabemono.com </title>
    <link rel="icon" href="hotel logo 1.webp">
    <style>
        body{
            background-color: paleturquoise;
        }
    </style>
</head>
<body>
    <h1 style="background-color: burlywood;">ABOUT US...</h1>
    <h2>
        contact as:958966231 (or) 9875493299<br>
        email address: hoteltabemono@gmail.com<br>
        address:39,besan nagar,chennai-600598,tamilnadu.<br>
    </h2>
    <br><br>
    <center>
    <a href="restaurant.html">||back||</a>
</center>
    
</body>
</html>


```


# OUTPUT:
![Screenshot 2024-12-16 140023](https://github.com/user-attachments/assets/6329dd11-0a10-46d4-9926-4fe5a9711484)


![Screenshot 2024-12-16 140107](https://github.com/user-attachments/assets/13cc4de8-73dc-4412-b1f0-971fc44a8fab)

![Screenshot 2024-12-16 140131](https://github.com/user-attachments/assets/56688d93-5e4b-4041-a99a-5a92b3ec3ba9)

![Screenshot 2024-12-16 140203](https://github.com/user-attachments/assets/4259964c-4620-4564-9c4e-dab3b1880ac1)

![Screenshot 2024-12-16 140219](https://github.com/user-attachments/assets/b16ab73a-f41a-4333-b26a-1d37ab4277ff)

![Screenshot 2024-12-16 140557](https://github.com/user-attachments/assets/5d7984cd-f5df-4a83-a12d-88e8bb102d90)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
