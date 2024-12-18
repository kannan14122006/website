# Ex.07 Restaurant Website
# Date:18/12/2024
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
web.html


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web app</title>
    <link rel="stylesheet" href="web.css">
</head>
<body>
    <div  id="template">

        <img src="back ground image 1.jpg" alt="back ground">
        <a href="Ocean_food.html" id="tag" >Kanna Restaurent</a>
        <a href="order_now.html" id="order">Order Now </a>
        <a href="contact.html" id="contact">Contact</a>
        <a href="administration.html" id="offers">Administraion</a>
        <input type="text" placeholder="search" id="search">

    </div>
</body>
</html>

ocean_food.html

html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ocean Foods</title>
    <style>
        body
        {
            background-color: pink;
        }
    </style>
</head>
<body >
   
        <h1>About Kanna restaurent</h1>
        <pre>
            Welcome to Kanna Restaurant
At Kanna Restaurant, we are passionate about delivering a dining experience that blends tradition and innovation. 
Located in the heart of [City], we specialize in [specific cuisine, e.g., "authentic Asian fusion"] dishes crafted with fresh, locally-sourced ingredients
        </pre>
        <pre>
            <h3>Our Story</h3>
Founded in [Year], Kanna Restaurant was built on a foundation of love for great food and community. 
Our journey began with the vision to bring people closer through the universal language of flavors. Whether you’re here for a casual lunch, a romantic dinner, or a celebration, we aim to make every visit special
<h2>Our Philosophy</h2>
We believe that food is more than just nourishment—it’s an experience. 
At Kanna Restaurant, we emphasize quality, creativity, and service excellence. Every dish is prepared with care and attention,
 combining traditional techniques with a modern twist to delight your palate.
<h3>
    Our Team</h3>
Behind every great meal is a team dedicated to excellence.
 From our talented chefs who craft each dish with precision to our friendly staff ensuring your comfort, we’re here to provide 
 a seamless and memorable dining experience.

<h3>Visit Us</h3>
Come and experience the charm and flavors of Kanna Restaurant. Whether you’re a first-time guest or a regular visitor, 
we look forward to welcoming you with open arms and a delicious menu.
 Reserve your table today and discover why Kanna Restaurant is more than just a place to eat—it’s a place to connect, savor, and enjoy.


        </pre>

   
</body>
</html>

order_now.html

html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ocean Foods</title>
    <style>
        body
        {
            background-color: pink;
        }
    </style>
</head>
<body >
   
        <h1>About Kanna restaurent</h1>
        <pre>
            Welcome to Kanna Restaurant
At Kanna Restaurant, we are passionate about delivering a dining experience that blends tradition and innovation. 
Located in the heart of [City], we specialize in [specific cuisine, e.g., "authentic Asian fusion"] dishes crafted with fresh, locally-sourced ingredients
        </pre>
        <pre>
            <h3>Our Story</h3>
Founded in [Year], Kanna Restaurant was built on a foundation of love for great food and community. 
Our journey began with the vision to bring people closer through the universal language of flavors. Whether you’re here for a casual lunch, a romantic dinner, or a celebration, we aim to make every visit special
<h2>Our Philosophy</h2>
We believe that food is more than just nourishment—it’s an experience. 
At Kanna Restaurant, we emphasize quality, creativity, and service excellence. Every dish is prepared with care and attention,
 combining traditional techniques with a modern twist to delight your palate.
<h3>
    Our Team</h3>
Behind every great meal is a team dedicated to excellence.
 From our talented chefs who craft each dish with precision to our friendly staff ensuring your comfort, we’re here to provide 
 a seamless and memorable dining experience.

<h3>Visit Us</h3>
Come and experience the charm and flavors of Kanna Restaurant. Whether you’re a first-time guest or a regular visitor, 
we look forward to welcoming you with open arms and a delicious menu.
 Reserve your table today and discover why Kanna Restaurant is more than just a place to eat—it’s a place to connect, savor, and enjoy.


        </pre>

   
</body>
</html>

contact.html



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">  
    <style>
      *{
        font-family: Arial, Helvetica, sans-serif;
      }
        #contact
        {
            border-radius: 30px;
            border: 50px inset black;
            display: flex;
            font-size: 30px;
            gap: 10px;
            background:	linear-gradient(to bottom, red ,yellow,red);
            border: 1px inset black;
            height: 800px;
        }
        #contact>div{
            width: 30%;
            /* border: 5px solid pink; */
            padding: 50px;
        }
        #div1
        {
            position: absolute;
            top:40px;
            right: 100px;
            border:1px inset whitesmoke;
            background-color: whitesmoke;
            border-radius: 50px;
        }
        input{
            font-size: 25px;
            margin-left: 30px;
        }
        #textarea
        {
          margin-left: 25px;
          padding: 20px;
          border: #FFFFFF;
          padding: 10px;
          border-radius: 10px;
          font-size: 20px;
        }

        #submit
        {
          background-color: #FF5200;
          border-radius: 10px;
          color: whitesmoke;
        }
        #label2
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;

        }
        #label1
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;
        }
        #info
        {
          padding: 20px;
          
        }

    </style>
    <script>
            function f1()
            {
                document.getElementById("label3").innerHTML="Informations are saved";
            }
    </script>
    
</head>
<body>
    <div id="contact">
      
           <div id="info">
              <b style="text-decoration: underline ;"> Kanna Restaurent</b>
              <br>
              <br>
              <b style="font-size: 50px;">Customer <br> Support</b>
              <br>
              <p>Email:suppor@KannaRestaurent.in</p>
              <br><br>
              <b>Find us on</b>
              <br>
               <i class="fab fa-instagram"  style="font-size: 50px; color: #E4405F ; margin-left: 20px; padding: 20px;"></i>
               <i class="fab fa-facebook-f"   style="font-size: 50px; color: #3b5998;  margin-left: 20px; padding: 20px;"></i>
               <i class="fab fa-linkedin-in"  style="font-size: 50px; color: #0077b5; margin-left: 20px; padding: 20px;"></i>
               <i class="fab fa-twitter"  style="font-size: 50px; color: #0077b5; margin-left: 20px; padding: 20px;"></i>
              
            </div>
        <div  id="div1">
            <hr style="font-style: italic;">
            <b align="center"> Get in touch </b>
            <br>
            <br>

            <label id="label2"><input type="text" id="label2" placeholder="Enter Name"></label>
            <br>
            <br>
            <label id="label1"> <input type="text" id="label1"  placeholder="Enter Number"></label>
            <br>
            <br>
            <label ><textarea  id="textarea" placeholder="Enter Message"  rows="10" cols="50"></textarea></label>
            <br>
            <br>
            <label id="label3"> <input type="submit"  id="submit" placeholder="Enter" onclick="f1()"></label>
            <hr>
        </div>

    </div>
</body>
</html>

administration.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administraion</title>
    <style>
        body
        {
            background-color: rgba(255,0,0,0.6);
        }
        #container
        {
            background-color: whitesmoke;
            display: flex;
            border: 5px solid aquamarine;
            height: 500px;
            width: auto;
            justify-content: space-evenly;
            border-radius: 100px;
        }
        #main
        {
            border: 1px solid black;
        }
        .box
        {
            position: relative;
            display: inline-block;
            top: 150px;
            height: 200px;
            width: 200px;
            border: 2px solid black;
            background-color: pink;
            border-radius: 50%;
        }
        #head
        {
            text-align: center;
            font-size: 40px;
            font-family: 'Times New Roman', Times, serif;
            font-weight: 700;
            background-size:cover ;
        }
        #name
        {
            justify-content: space-evenly;
        }
        #n1
        {
            position: absolute;
            bottom: 170px;
            left: 100px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n2
        {
            position: absolute;
            bottom: 170px;
            left: 300px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n3
        {
            position: absolute;
            bottom: 170px;
            left: 570px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n4
        {
            position: absolute;
            bottom: 170px;
            left: 800px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n5
        {
            position: absolute;
            bottom: 170px;
            left: 1050px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
    </style>
    
</head>
<body>
    <div align="center" id="head">Chef of my company</div>
    <div id="container">

            <div ><img src="WhatsApp Image 2024-12-18 at 21.11.03_c1ba5d5d.jpg" alt="" class="box"></div>
            <div ><img src="WhatsApp Image 2024-12-18 at 21.11.39_ddd72167.jpg" alt="" class="box"></div>
            <div ><img src="WhatsApp Image 2024-12-18 at 21.11.40_6162148e.jpg" alt="" class="box"></div>
            <div ><img src="WhatsApp Image 2024-12-18 at 21.40.58_81804a84.jpg" alt="" class="box"></div>
            <div ><img src="WhatsApp Image 2024-12-18 at 21.16.15_4cc6a3a8.jpg" alt="" class="box"></div>

    </div>
    <p id="n1">K.Pavan Kumar </p> 
        <p id="n2">M.R. Mani Kandan</p>
         <p id="n3">K. Savish</p>
        <p id="n4">A. Raja Dharunesh</p>  
        <p id="n5">k. Harish</p>
</body>
</html>

```
# OUTPUT:
![text](<Screenshot (7).png>) 
![text](<Screenshot (8).png>) 
![text](<Screenshot (9).png>) 
![text](<Screenshot (10).png>) 
![text](<Screenshot (11).png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
