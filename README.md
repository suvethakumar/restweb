# Ex.07 Restaurant Website
## Date:3/10/25

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
rest.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SUVETHA RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color:rgb(128, 128, 128);
            color: red;
        }
        header {
            background-color:purple;
            color: yellow;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color: sky blue;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
        nav a {
            color: white;
 text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: pink;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
 background-color:green;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: indigo;
        }
        .menu-item p {
            font-size: 1em;
            color:rgb(192, 192, 192);
        }
        footer {
            background-color:purple;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>SUVETHA RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
 </nav>
</header>
 <section id="About" class="About">
        <h1>Welcome to SUVETHA Restaurant</h1>
        <p>our staffs</p>
        </section>
 
 <img src="vijay.jpg.jpg"height="200",width="200"style="display:;">
 <img src="nayanthara.jpg"height="200",width="200"style="display:">
 <img src="surya.jpg "height="200",width="200"style="display:">
 <img src="samantha.jpg"height="200",width="200"style="display:">
 <img src="rashmika.jpg"height="200",width="200"style="display:">






 <footer>

  <p>© 2025 Designed By Suvetha(25014616)</p>
</footer>
</body>
</html>

home.html

home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SUVETHA RESTAURANT - Home</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #fff8f0;
      color: #291515;
    }
    header {
      background-color: #8d5f5f;
      color: white;
      padding: 20px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }
    nav {
      background-color: #625b40;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
 font-size: 1.1em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      background-color: #f5e8d6;
    }
    .hero h2 {
      font-size: 2.5em;
      color: #83624c;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2em;
      color: #5a2e00;
    }
    .dishes {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .dishes h2 {
      text-align: center;
      color: #83624c;
      margin-bottom: 30px;
      font-size: 2em;
    }
    .dish-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
 }
    .dish-item {
      background-color: #81664c;
      padding: 20px;
      border-radius: 8px;
      width: 200px;
      text-align: center;
      color: #fff;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .dish-item h3 {
      margin-bottom: 10px;
    }
    footer {
      background-color: #7dede9;
      color: rgb(1, 15, 2);
      text-align: center;
      padding: 18px 10px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    SUVETHA RESTAURANT
    <nav>
      <a href="home.html">Home</a>
      <a href="about.html">About</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
<a href="booking.html">Book Table</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to SUVETHA Restaurant</h2>
    <p>Delicious food made with love,afection,care and with delitedness. Enjoy the special dishes prepared by our talented chefs and enjoy with your family which makes you unforgetable!</p>
  </section>

  <section class="dishes">
    <h2>Our Popular Dishes</h2>
    <div class="dish-list">
      <div class="dish-item"><h3>Burger</h3></div>
      <div class="dish-item"><h3>Ice-Cream</h3></div>
      <div class="dish-item"><h3>Mutton Biriyani</h3></div>
      <div class="dish-item"><h3>Idly</h3></div>
      <div class="dish-item"><h3>Chicken Biryani</h3></div>
      <div class="dish-item"><h3>Dosa</h3></div>
      <div class="dish-item"><h3>Butter Chicken</h3></div>
      <div class="dish-item"><h3>Chicken Wings</h3></div>
    </div>
  </section>

  <footer>
    <p>© 2025 Designed By SUVETHA(25014616)</p>
  </footer>
</body>
</html>

menu.html


menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SUVETHA RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color:pink;
            color:blue;
        }
        header {
            background-color: #16e54d;
            color: rgb(110, 18, 185);
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color: yellow;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
 nav a {
            color: brown;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: pink;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
            background-color: purple;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: green;
        }
        .menu-item p {
            font-size: 1em;
            color: indigo;
        }
        footer {
            background-color: #8e2929;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>SUVETHA RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="Menu" class="Menu">
        <h1>Welcome to SUVETHA Restaurant</h1>
        <p>Experience the best flavors of traditional and modern cuisine in a warm and welcoming atmosphere.</p>
    </section>
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\chicken wing.jpg"height="200",width="200"style="display:">
<img src="c:\Users\SUVETHA CSE\OneDrive\Documents\chicken biriyani.jpg"height="200",width="200"style="display:">
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\burger.jpg"height="200",width="200"style="display:">
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\dosa.jpg"height="200",width="200"style="display:">
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\French fries.jpg"height="200",width="200"style="display:">
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\ice creaam.jpg"height="200",width="200"style="display:;">
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\idly.jpg"height="200",width="200"style="display:">
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\mutton biriyani.jpg"height="200",width="200"style="display:">
 <img src="c:\Users\SUVETHA CSE\OneDrive\Documents\mutton.jpg"height="200",width="200"style="display:">
 
 




 <footer>

  <p>© 2025 Designed By SUVETHA(25014616)</p>
</footer>
</body>
</html>

admin.html

admin.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Admin Dashboard</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Logout</a>
  </nav>
</header>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>burger</li>
    <li>Ice-Cream</li>
    <li>Mutton Biriyani </li>
    <li>Idly</li>
    <li>Chicken Biryani</li>
    <li>dosa</li>
    <li>meals</li>
    <li>prawn</li>
    <li>French Fries</li>
    <li>chickenwing</li>
,  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>Dhashvin- Chef</li>
    <li>Sanjutha - Waitress</li>
    <li>Dhanush - Manager</li>
  </ul>
</section>

<footer>
  <p>© 2025 SUVETHA Restaurant</p>
</footer>
</body>
</html>

contact.html

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>SUVETHA Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>
  <p>📍 no.19,Selliyamman Kovil Street,Villupuram</p>
  <p>📞 ‪+91 9384456203‬</p>
  <p>📧 EMAIL : suvetha221107@gmail.com</p>
</section>

<footer>
  <p>© 2025 SUVETHA Restaurant</p>
</footer>
</body>
</html>

booking.html

book.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SUVETHA RESTAURANT - Book Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: pink;
      color: #291515;
    }
    header {
      background-color: purple;
      color: black;
      padding: 20px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }
    nav {
      background-color: skyblue;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
    }
    nav a {
      color: rgb(229, 13, 204);
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .booking-form {
      max-width: 600px;
 margin: 40px auto;
      background-color: rgb(225, 11, 104);
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .booking-form h2 {
      text-align: center;
      color: rgb(247, 1, 1);
      margin-bottom: 25px;
      font-size: 2em;
    }
    .booking-form label {
      display: block;
      margin-bottom: 8px;
      font-weight: 600;
    }
    .booking-form input, 
    .booking-form select, 
    .booking-form textarea {
      width: 100%;
      padding: 5px;
      margin-bottom: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 1em;
    }
    .booking-form button {
      background-color: rgb(46, 221, 81);
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 6px;
      font-size: 1.1em;
      cursor: pointer;
      width: 100%;
    }
    .booking-form button:hover {
 background-color: rgb(239, 10, 10);
    }
    footer {
      background-color: rgb(78, 50, 205);
      color: black;
      text-align: center;
      padding: 12px 10px;
      margin-top: 5px;
    }
  </style>
</head>
<body>
  <header>
    SUVETHA RESTAURANT
    <nav>
      <a href="home.html">Home</a>
      <a href="about.html">About</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="booking.html">Book Table</a>
    </nav>
  </header>

  <section class="booking-form">
    <h2>Book a Table</h2>
    <form action="#" method="POST">
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" placeholder="Your name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Your Email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required>

      <label for="guests">Number of Guests</label>
 <input type="number" id="guests" name="guests" min="1" placeholder="Number of Guests" required>

      <label for="date">Date</label>
      <input type="date" id="date" name="date" required>

      <label for="time">Time</label>
      <input type="time" id="time" name="time" required>

      <button type="submit">Book Now</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Designed By SUVETHA(25014616)</p>
  </footer>
</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot (55).png>)
![alt text](image.png)
![alt text](<Screenshot (53).png>)
![alt text](<Screenshot (50).png>)
![alt text](<Screenshot (47).png>)
![alt text](<Screenshot (49).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
