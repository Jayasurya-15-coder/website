# Ex.07 Restaurant Website
# Date:25-04-2025
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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hot Stream</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #000;
      color: #eee;
    }
    header {
      background-color:rgb(20, 14, 41);
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #333;
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 10px 0;
    }
    nav a {
      color: yellow;
      text-decoration: none;
      font-weight: bold;
    }
    .banner {
      background: url('/mnt/data/1f161b39-e971-4894-a0a7-236b1cb36920.png') center/cover no-repeat;
      color: yellow;
      padding: 60px 20px;
      text-align: center;
      font-size: 2rem;
      border-radius: 10px;
      margin: 20px;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin: 20px;
    }
    .card {
      background-color:rgb(18, 16, 36);
      padding: 15px;
      border-radius: 10px;
      width: 300px;
      color: #eee;
    }
    .card img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.8rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1> Hot Stream </h1>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#admin">Administration</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <section id="home">
    <div class="banner">40% Off This Weekend – Come Taste the Zest!</div>
    <div class="container">
      <div class="card">
        <h2>Our New Menu</h2>
        <img src="C:\Users\admin\Downloads\grill.jpeg" alt="Grill">
        <p>Discover sizzling new dishes and mouth-watering delights fresh off the grill.</p>
      </div>
      <div class="card">
        <h2>Book a Table</h2>
        <img src="C:\Users\admin\Downloads\san.jpeg" alt="Salad">
        <p>Reserve your spot now and enjoy a Mediterranean feast like no other.</p>
      </div>
      <div class="card">
        <h2>Opening Hours</h2>
        <p>Mon-Fri: 2pm-10pm<br>Sat: 2pm-11pm<br>Sun: 2pm-9pm</p>
      </div>
    </div>
  </section>

  <section id="menu">
    <h2 style="text-align:center">Our Menu</h2>
    <div class="container">
      <div class="card"><h3>Margherita Pizza</h3><img src="C:\Users\admin\Downloads\pizza.jpg" alt="Pizza" /><p>Classic Neapolitan pizza with fresh basil, mozzarella, and tomato sauce.</p></div>
      <div class="card"><h3>Spaghetti Carbonara</h3><img src="C:\Users\admin\Downloads\pasta.jpeg" alt="Pasta" /><p>Rich and creamy spaghetti tossed with pancetta and a parmesan-egg sauce.</p></div>
      <div class="card"><h3>Grilled Chicken</h3><img src="C:\Users\admin\Downloads\grills.jpeg" /><p>Juicy grilled chicken served with herbs and a side of lemon butter sauce.</p></div>
      <div class="card"><h3>Caesar Salad</h3><img src="C:\Users\admin\Downloads\sa.jpeg" alt="Salad" /><p>Romaine lettuce, parmesan, croutons, and Caesar dressing.</p></div>
      <div class="card"><h3>Fish Tacos</h3><img src="C:\Users\admin\Downloads\fish.jpeg" alt="Tacos" /><p>Grilled fish in soft tortillas with tangy slaw and chipotle sauce.</p></div>
      <div class="card"><h3>Veggie Wrap</h3><img src="C:\Users\admin\Downloads\veg.jpeg" alt="Wrap" /><p>Fresh veggies wrapped in a soft tortilla with hummus spread.</p></div>
      <div class="card"><h3>Lamb Chops</h3><img src="C:\Users\admin\Downloads\lamb.jpeg" alt="Lamb" /><p>Char-grilled lamb chops seasoned with garlic and rosemary.</p></div>
      <div class="card"><h3>Mango Smoothie</h3><img src="C:\Users\admin\Downloads\mango.jpeg" alt="Smoothie" /><p>Refreshing blend of ripe mangoes and Greek yogurt.</p></div>
      <div class="card"><h3>Chocolate Cake</h3><img src="C:\Users\admin\Downloads\choco.jpeg" alt="Cake" /><p>Moist chocolate cake topped with rich ganache.</p></div>
      <div class="card"><h3>Ice Cream Sundae</h3><img src="C:\Users\admin\Downloads\ice.jpeg" alt="Ice Cream" /><p>Classic sundae with vanilla ice cream, hot fudge, and nuts.</p></div>
    </div>
  </section>

  <section id="admin">
    <h2 style="text-align:center">Our Team</h2>
    <div class="container">
      <div class="card"><h3>Chef DiCaprio</h3><p>Master of Italian cuisine and the creative force behind our seasonal dishes.</p></div>
      <div class="card"><h3>Manager Johnny Depp</h3><p>Ensures smooth operations and customer satisfaction with a smile.</p></div>
      <div class="card"><h3>Head Waiter Dong Lee</h3><p>Leads the service team with professionalism and attention to detail.</p></div>
      <div class="card"><h3>Barista Leo Das</h3><p>Coffee connoisseur serving espresso perfection in every cup.</p></div>
      <div class="card"><h3>Pastry Chef AlPacino</h3><p>Bakes delightful pastries and desserts that melt in your mouth.</p></div>
      <div class="card"><h3>Hostess Elizabeth Grant</h3><p>Warmly welcomes every guest and makes them feel right at home.</p></div>
    </div>
  </section>

  <section id="contact">
    <h2 style="text-align:center">Contact Us</h2>
    <div class="container">
      <div class="card">
        <h3>📍 Address</h3>
        <p>123, Nelson Street<br>wool City</p>
        <h3>📞 Phone</h3>
        <p>+1 (555) 123-4567</p>
        <h3>📧 Email</h3>
        <p>contact@hot_stream.com</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 Hot Stream | Designed and Developed by <span style="color:red">JAYASURYA B</span>
  </footer>
```
# OUTPUT:

![Screenshot 2025-04-25 135443](https://github.com/user-attachments/assets/4d65a734-5fd5-4024-bc6a-8ae3e92e146c)

![Screenshot 2025-04-25 135509](https://github.com/user-attachments/assets/047c90e4-b4ea-4742-ad51-f6367b0d144b)

![Screenshot 2025-04-25 135836](https://github.com/user-attachments/assets/ecae554e-11cd-4434-9d20-f8b071f89643)

![Screenshot 2025-04-25 135902](https://github.com/user-attachments/assets/76ff4dd2-dbe9-4e6f-9572-f79f977e2394)

![Screenshot 2025-04-25 135920](https://github.com/user-attachments/assets/447cfa20-2bcf-4ff8-811e-98870e725454)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
