# Ex.06 Restaurant Website
## Date:23/12/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
```
##restaurant.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Restaurant Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color:beige;
            color:black;
        }

        header {
            color:black;
            padding: 1rem 0;
            text-align: center;
            background-color:lightyellow;
        }
        nav {
            text-align: center;
            padding: 0.5rem 0;
            background-color:lightslategray;
        }
        nav a {
            color:black;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1rem;
        }
        nav a:hover {
            text-decoration: underline; 
        }
        footer {
            color:black;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
            font-size: xx-large;
        }
        .item2{
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>B.tech foddie</h1>
        <p>Where every meal is a delight!</p>
    </header>
    <nav>
        <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="About.html">About</a>
        <a href="Contact.html">Contact</a>
    </nav>  
    <div class="container">
        <div CLASS="item1">
           <center><img src="restaurent.png" width="900" height="500"></center>
        </div>

        <div CLASS="item2">
            <h1>AFTERNOON</h1>
                <h2>Food menus are tailored appropriately to season and availbity. Changing daily, we use the highest quality of produce, cooked with care.<br>
                
                Our wine list has a focus on European producers alongside a smattering from the new world. We work with wine makers who produce high quality wine with minimal intervention - ranging from classics to the unusual.<br>
                
                The beer list is dominated by British breweries, particularly those from the thriving London scene. We work closely with Five Points Brewery who produce our house pale ale 'So Solid Brew'<br>
                
                For group bookings of 7+ please see our set menu below. This changes seasonally and showcases the best of our a la carte offering.</h2>
        </div>
    <footer>
        <p>-----------------------------------------------------------------------------------------</p>
        <p>&copy; 2024 Delicious Bites. All rights reserved.</p>
    </footer>
</body>
</html>

##menu.html

<style>
    body {
        font-family: Arial, sans-serif;
        background-color:beige;
        color:black;
    }

    header {
        background-color:lightyellow;
        color:black;
        padding: 1rem 0;
        text-align: center;
    }
    nav {
        background-color:lightslategray;
        text-align: center;
        padding: 0.5rem 0;
    }

    nav a {
        color:black;
        text-decoration: none;
        margin: 0 15px;
        font-size: 1.1rem;
    }

    nav a:hover {
        text-decoration: underline;
    }

    .container {
        padding: 20px;
        max-width: 1200px;
        margin: auto;
        background: #fff;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .section {
        margin: 20px 0;
    }

    .section h2 {
        color: #444;
        margin-bottom: 10px;
    }
    footer {
        color:black;
        text-align: center;
        padding: 10px 0;
        margin-top: 20px;
    }
    footer p {
            margin: 0;
        }
            .container {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            width: 90%;
            background-color:beige;
            }

           .item {
            text-align: center;
            }
           .item img {
            width: 150;
            height: 150;
            margin: 30PX;
            }
</style>
<body>
    <header>
        <h1>B.tech foddie</h1>
        <p>Where every meal is a delight!</p>
    </header>

    <nav>
        <a href="Restaurant.html">Home</a>
        <a href="Menu.html">Menu</a>
        <a href="About.html">About</a>
        <a href="Contact.html">Contact</a>
    </nav>
    <div class="container">
        <div CLASS="item">
            <img src="burger.png" >
            <H3>Burger<br>RS:200</H3>
        </div>

        <div CLASS="item">
            <img src="biriyani.png" >
            <H3>Chicken Biryani<br>RS:300</H3>
        </div>
        
        <div CLASS="item">
            <img src="fishfry.png" >
            <H3>Fish Fry<br>RS:250</H3>
        </div>

        <div CLASS="item">
            <img src="friedchicken.png" >
            <H3>Fried Chicken<br>RS:300</H3>
        </div>

        <div CLASS="item">
            <img src="kebeb.png" >
            <H3>Kebab<br>RS:400</H3>
        </div>

        <div CLASS="item">
            <img src="mushroomsoup.png" >
            <H3>Mushroom Soup<br>RS:200</H3>
        </div>

        <div CLASS="item">
            <img src="pasta.png" >
            <H3>Pasata<br>RS:200</H3>
        </div>

        <div CLASS="item">
            <img src="pizza.png" >
            <H3>Pizza<br>RS:250</H3>
        </div>

        <div CLASS="item">
            <img src="salad.png" >
            <H3>Salad<br>RS:150</H3>
        </div>

        <div CLASS="item">
            <img src="steak.png" >
            <H3>Steak<br>RS:350</H3>
        </div>

        <div CLASS="item">
            <img src="sushi.png" >
            <H3>Sushi<br>RS:500</H3>
        </div>

        <div CLASS="item">
            <img src="tomatosoup.png" >
            <H3>Tomato Soup<br>RS:150</H3>
        </div>
        
    </div>
    <footer>
        <p>&copy; 2024 Delicious Bites. All rights reserved.</p>
    </footer>
</body>
</html>

##about.html

<style>
  body {
      font-family: Arial, sans-serif;
      background-color:beige;
      color:black;
  }

  header {
      background-color:lightyellow;
      color:black;
      padding: 1rem 0;
      text-align: center;
  }
  nav {
      background-color:lightslategray;
      text-align: center;
      padding: 0.5rem 0;
  }

  nav a {
      color:black;
      text-decoration: none;
      margin: 0 15px;
      font-size: 1.1rem;
  }

  nav a:hover {
      text-decoration: underline;
  }

  .container {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
      background: #fff;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }

  .section {
      margin: 20px 0;
  }

  .section h2 {
      color: #444;
      margin-bottom: 10px;
  }
  footer {
      color:black;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
  }
  footer p {
            margin: 0;
        }
            .container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            width: 90%;
            background-color: beige;
            }

           .item {
            text-align: center;            
            }
           .item img {
            width: 300;
            height: 250;
            margin: 30PX;
            }
</style>
<body>
  <header>
      <h1>B.tech foddie</h1>
      <p>Where every meal is a delight!</p>
  </header>

  <nav>
      <a href="Restaurant.html">Home</a>
      <a href="Menu.html">Menu</a>
      <a href="About.html">About</a>
      <a href="Contact.html">Contact</a>
  </nav>
  <div class="container">
    <DIV CLASS="item">
        <img src="chef-Gordon-Ramsay.png" >
        <H3>Gordon-Ramsay</H3>
    </DIV>

    <DIV CLASS="item">
        <img src="chef-Sanjeev-Kapoor.png" >
        <H3>Sanjeev-Kapoor</H3>
    </DIV>
    
    <DIV CLASS="item">
        <img src="chef-atul.png" >
        <H3>Atul</H3>
    </DIV>

    <DIV CLASS="item">
        <img src="chef-paul-bocuse.png" >
        <H3>Paul Bocuse</H3>
    </DIV>

    <DIV CLASS="item">
        <img src="Chef-Sandeep-Pande.png" >
        <H3>Sandeep Pande</H3>
    </DIV>

    <DIV CLASS="item">
        <img src="Chef-Vineet-Bhatia.png" >
        <H3>Vineet Bhatia</H3>
    </DIV>
</div>
  <footer>
      <p>&copy; 2024 B.tech foddie. All rights reserved.</p>
  </footer>
</body>

##contact.html

<style>
  body {
      font-family: Arial, sans-serif;
      background-color:beige;
      color:black;
  }

  header {
      background-color:lightyellow;
      color:black;
      padding: 1rem 0;
      text-align: center;
  }
  nav {
      background-color:lightslategray;
      text-align: center;
      padding: 0.5rem 0;
  }

  nav a {
      color:black;
      text-decoration: none;
      margin: 0 15px;
      font-size: 1.1rem;
  }

  nav a:hover {
      text-decoration: underline;
  }

  .container {
      padding: 20px;
      max-width: 1200px; 
      margin: auto;
      background: #fff;
  }

  .section {
      margin: 20px 0;
  }

  .section h2 {
      color: #444;
      margin-bottom: 10px;
  }
  footer {
      color:black;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
  }
  footer p {
            margin: 0;
        }
        .contact-section{
          text-align: center;
          font-size: x-large;
        }
        .contact-info{
          text-align: center;
        }
</style>
<body>
  <header>
    <h1>B.tech foddie</h1>
    <p>Where every meal is a delight!</p>
</header>
<nav>
    <a href="Restaurant.html">Home</a>
    <a href="Menu.html">Menu</a>
    <a href="About.html">About</a>
    <a href="Contact.html">Contact</a>
</nav>
  <section class="contact-section">
     <u><h1>Contact Us</h1></u>
   <p class="text">We'd love to hear from you! <br>
  Please reach out using the contact form below or through the contact details provided.</p>
    <div class="contact-info">
        <u><h2>Contact Information</h2></u>
        <ul>
            <strong>Email:</strong> <a href="mailto:">support@DeliciousBites.com</a><br>
            <strong>Phone:</strong> +91 9669477400<br>
            <strong>Address:</strong> 1/115 Saveetha Street,Saveetha Nagar,chennai<br>
        </ul>
    </div>
</section>
  <footer><p> &copy 2024 KING OF FOODS | All rights reserved</p></footer>
</body>
```

## OUTPUT:
![alt text](<Screenshot 2025-12-23 102301.png>)
![alt text](<Screenshot 2025-12-23 102318.png>)
![alt text](<Screenshot 2025-12-23 102333.png>)
![alt text](<Screenshot 2025-12-23 102347.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
