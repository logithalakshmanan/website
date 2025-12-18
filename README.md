# Ex.07 Restaurant Website
# Date:18.12.2025
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
index.html

<!DOCTYPE html>
<html>
<head>
    <title>Restaurant Menu - CHARCOAL</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
    <a href="index.html">Home</a>
    <a href="administration.html">Administration</a>
    <a href="booktable.html">Book Table</a>
</nav>

<div class="banner">
    <h1>Charcoal Restaurant</h1>
    <p>Fresh  Tasty  Affordable</p>
</div>

<div class="menu">
    <!-- Dish 1 -->
    <div class="card">
        <img src="pizza.jpg" alt="Pizza">
        <h3>Pizza</h3>
        <p class="price">Rs.250</p>
    </div>

    <!-- Dish 2 -->
    <div class="card">
        <img src="burger.avif" alt="Burger">
        <h3>Burger</h3>
        <p class="price">Rs.180</p>
    </div>

    <!-- Dish 3 -->
    <div class="card">
        <img src="pasta.jpg" alt="Pasta">
        <h3>Pasta</h3>
        <p class="price">Rs.220</p>
    </div>

    <!-- Dish 4 -->
    <div class="card">
        <img src="fried rice.jpg" alt="Fried Rice">
        <h3>Fried Rice</h3>
        <p class="price">Rs.200</p>
    </div>

    <!-- Dish 5 -->
    <div class="card">
        <img src="noodles.jpg" alt="Noodles">
        <h3>Noodles</h3>
        <p class="price">Rs.190</p>
    </div>

    <!-- Dish 6 -->
    <div class="card">
        <img src="sandwich.jpg" alt="Sandwich">
        <h3>Sandwich</h3>
        <p class="price">Rs.150</p>
    </div>

    <!-- Dish 7 -->
    <div class="card">
        <img src="ice cream.jpg" alt="Ice Cream">
        <h3>Ice Cream</h3>
        <p class="price">Rs.120</p>
    </div>

    <!-- Dish 8 -->
    <div class="card">
        <img src="cake.jpg" alt="Cake">
        <h3>Cake</h3>
        <p class="price">Rs.300</p>
    </div>

    <!-- Dish 9 -->
    <div class="card">
        <img src="milkshake.jpg" alt="Milkshake">
        <h3>Juice</h3>
        <p class="price">Rs.100</p>
    </div>
</div>

</body>
</html>

administration.html
<html>
<head>
    <title>Administration - NAHDI MANDI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .admin-section {
            padding: 30px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .admin-section h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .admin-team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .team-member {
            background-color: lightblue;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }
        .team-member img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .admin-login {
            margin-top: 30px;
            text-align: center;
        }
        .admin-login input {
            padding: 10px;
            margin: 10px 5px;
            border: 1px solid gray;
            border-radius: 5px;
            font-size: 14px;
        }
        .admin-login button {
            padding: 10px 20px;
            background-color: darkslateblue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .admin-login button:hover {
            background-color: slateblue;
        }
    </style>
</head>
<body>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="adminstration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>CHARCOAL Administration</h1>
</header>

<div class="admin-section">
    <h2>Meet the Team</h2>
    <div class="admin-team">
        <div class="team-member">
            <h3>John Doe</h3>
            <p>Manager</p>
        </div>
        <div class="team-member">
            <h3>Jane Smith</h3>
            <p>Assistant Manager</p>
        </div>
        <div class="team-member">
            <h3>Emily Johnson</h3>
            <p>HR Head</p>
        </div>
    </div>

    <div class="admin-login">
        <h2>Admin Login</h2>
        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</div>

</body>
</html>
    <div class="admin-login">
        <h2>Admin Login</h2>
        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</div>

</body>
</html>

booktable.html
<!DOCTYPE html>
<html>
<head>
    <title>Book a Table - NAHDI MANDI</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Navbar -->
<nav>
    <a href="index.html">Home</a>
    <a href="administration.html">Administration</a>
    <a href="booktable.html">Book Table</a>
</nav>

<!-- Banner -->
<div class="banner">
    <h1>Book a Table</h1>
    <p>Reserve your spot at CHARCOAL</p>
</div>

<!-- Booking Section -->
<div class="booking-section">
    <h2>Reserve Your Table Now</h2>
    <form class="booking-form">
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number" required>
        <select name="guests" required>
            <option value="" disabled selected>Number of Guests</option>
            <option value="1">1 Guest</option>
            <option value="2">2 Guests</option>
            <option value="3">3 Guests</option>
            <option value="4">4 Guests</option>
            <option value="5">5 Guests</option>
            <option value="6+">6+ Guests</option>
        </select>
        <input type="date" name="date" required>
        <input type="time" name="time" required>
        <button type="submit">Book Now</button>
    </form>
</div>

</body>
</html>

contact.html
<html>
<head>
    <title>Contact Us - NAHADI MANDI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: white;
            padding: 20px;
        }
        .contact-section {
            padding: 30px;
            max-width: 600px;
            margin: auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-section h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .contact-section form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .contact-section input, .contact-section textarea, .contact-section button {
            padding: 10px;
            font-size: 16px;
            border: 1px solid whitesmoke;
            border-radius: 5px;
        }
        .contact-section textarea {
            resize: none;
            height: 100px;
        }
        .contact-section button {
            background-color: #4a4a4a;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="adminstration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>Contact Us</h1>
</header>

<div class="contact-section">
    <h2>We'd Love to Hear from You!</h2>
    <form>
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
        <textarea name="message" placeholder="Your Message..." required></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>

style.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: lightgray;
}


nav {
    background-color: darkslategray;
    display: flex;
    justify-content: center;
    padding: 10px;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}
nav a:hover {
    color: lightblue;
}


.banner {
    background-color: #c0392b;
    color: white;
    text-align: center;
    padding: 25px 10px;
    margin-bottom: 30px;
}
.banner h1 {
    margin: 0;
    font-size: 36px;
}
.banner p {
    margin: 5px 0 0;
    font-size: 16px;
}


.booking-section {
    padding: 40px;
    max-width: 500px;
    margin: 40px auto;
    background-color: white;
    border-radius: 15px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    text-align: center;
}

.booking-section h2 {
    color: darkslateblue;
    margin-bottom: 30px;
}

.booking-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.booking-form input,
.booking-form select,
.booking-form button {
    padding: 12px;
    font-size: 16px;
    border: 1px solid gray;
    border-radius: 8px;
}

.booking-form button {
    background-color: darkslateblue;
    color: white;
    cursor: pointer;
    transition: background 0.3s, transform 0.3s;
}
.booking-form button:hover {
    background-color: slateblue;
    transform: translateY(-2px);
}


@media screen and (max-width: 600px) {
    .booking-section {
        width: 90%;
        padding: 30px;
    }
}
```
# OUTPUT:
![alt text](<Screenshot (164).png>)
![alt text](<Screenshot (165).png>)
![alt text](<Screenshot (166).png>)
![alt text](<Screenshot (167).png>)
![alt text](<Screenshot (168).png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
