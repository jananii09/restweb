# Ex.07 Restaurant Website
## Date:19/12/2024

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
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Little Lemon Restaurant</title>
    <meta name="description" content="A Brief Description">
    <meta name="author" content="Luxury Jewellery">

    <!-- Load static files -->
    {% load static %}

    <link rel="stylesheet" href="{% static 'styles.css' %}">
</head>
<body>

    <!-- Header section -->
    <header>
        <div class="logo">
            <img src="{% static 'images/logo.png' %}" alt="Client Logo">
        </div>
        <nav>
            <ul class="nav-menu">
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main content section -->
    <main>
        <!-- Promotional Banner -->
        <section class="promo">
            <h1>Welcome to Little Lemon</h1>
            <p>Have your Favourite taste...</p>
            <img src="{% static 'images/img1.png' %}" alt="banner">
            <p>Savor the best of both worlds with our delicious veg and non-veg dishes, crafted to perfection. From mouthwatering starters to irresistible snacks, every bite is a burst of flavor. Join us for a dining experience that satisfies every craving!</p>
        </section>

        <!-- Three columns section -->
        <section class="three-columns">
            <article class="column">
                <h2>Starters and Snacks</h2>
                <img src="{% static 'images/img2.png' %}" alt="Starters&Snacks">
                <p>*  Kickstart your cravings with our irresistible starters and snacks, bursting with flavor in every bite.</p>
                <p>*  Perfectly crafted to tease your taste buds, our delicious selection is the ultimate treat for any occasion.</p> 
                <p>*  Indulge in the perfect bite-sized delights!</p>
            </article>
            <article class="column">
                <h2>Vegetarian</h2>
                <img src="{% static 'images/img3.png' %}" alt="Veg">
                <p>*  Delight in our fresh, flavorful vegetarian dishes that celebrate nature's finest ingredients.</p>
                <p>*  Each meal is crafted to nourish your body and satisfy your taste buds.</p>
                <p>*  Experience the vibrant taste of wholesome, plant-based goodness!</p>
            </article>
            <article class="column">
                <h2>Non-Vegetarian</h2>
                <img src="{% static 'images/img4.png' %}" alt="NonVeg">
                <p>*  Indulge in the rich, savory flavors of our premium non-veg dishes, expertly crafted for true food lovers.</p>
                <p>*  From tender meats to bold spices, every bite promises a taste of perfection.</p>
                <p>*  Satisfy your cravings with our irresistible non-veg delights!</p>
            </article>
        </section>
    </main>

    <!-- Footer section -->
    <footer>
        <div class="footer-left">
            <img src="{% static 'images/logo_footer.png' %}" alt="Client Logo">
        </div>
        <div class="footer-right">
            <p>&copy; 2024 Little Lemon. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
```

## OUTPUT:
![Screenshot 2024-12-19 132851](https://github.com/user-attachments/assets/387b2797-f408-477f-a328-d307c7b621f9)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
