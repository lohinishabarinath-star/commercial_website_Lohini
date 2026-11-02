# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
```html
<!DOCTYPE html>
<html>
<head>
    <title>Sweet Cravings | Online Bakery</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Header -->
    <header>
        <h1>🍰 SWEET CRAVINGS</h1>
        <p>Freshly Baked Happiness!</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">My Account</a>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to Sweet Cravings!</h2>
        <p>Enjoy delicious cakes, brownies, cupcakes and more.</p>
        <p>Made with love and baked with happiness! 💗</p>
    </section>

    <!-- Products Section -->
    <section id="products">
        <h2>Our Bakery Products</h2>

        <div class="product-container">

            <div class="product">
                <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?w=400" alt="Chocolate Cake">
                <h3>Chocolate Cake</h3>
                <p>₹599</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1486427944299-d1955d23e34d?w=400" alt="Vanilla Cupcakes">
                <h3>Vanilla Cupcakes</h3>
                <p>₹299</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1551024506-0bccd828d307?w=400" alt="Donuts">
                <h3>Sweet Donuts</h3>
                <p>₹199</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1569864358642-9d1684040f43?w=400" alt="Macarons">
                <h3>French Macarons</h3>
                <p>₹399</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?w=400" alt="Tres Leches Cake">
                <h3>Tres Leches Cake</h3>
                <p>₹450</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1606313564200-e75d5e30476c?w=400" alt="Chocolate Brownie">
                <h3>Chocolate Brownie</h3>
                <p>₹180</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1586788680434-30d324b2d46f?w=400" alt="Red Velvet Cake">
                <h3>Red Velvet Cake</h3>
                <p>₹650</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1533134242443-d4fd215305ad?w=400" alt="Cheesecake">
                <h3>Strawberry Cheesecake</h3>
                <p>₹499</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1602351447937-745cb720612f?w=400" alt="Chocolate Truffle">
                <h3>Chocolate Truffle</h3>
                <p>₹550</p>
                <button>Order Now</button>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1607958996333-41aef7caefaa?w=400" alt="Blueberry Muffins">
                <h3>Blueberry Muffins</h3>
                <p>₹250</p>
                <button>Order Now</button>
            </div>

        </div>
    </section>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>Sweet Cravings is an online bakery that offers fresh and delicious cakes, pastries and desserts.</p>
        <p>Our goal is to make every celebration sweeter with our freshly baked treats!</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: sweetcravings@gmail.com</p>
        <p>Phone: +91 9876543210</p>
        <p>Location: Chennai, Tamil Nadu</p>
    </section>

    <!-- User Account Section -->
    <section id="account">
        <h2>My Account</h2>

        <input type="text" placeholder="Enter Username">
        <br><br>

        <input type="password" placeholder="Enter Password">
        <br><br>

        <button>Login</button>

        <p>New User? Create an account</p>
    </section>

    <!-- Footer -->
    <footer>
        <h3>Sweet Cravings 🍰</h3>
        <p>Freshly Baked Happiness!</p>

        <p>Follow us on</p>
        <a href="https://www.instagram.com/">Instagram</a>
        <a href="https://www.facebook.com/">Facebook</a>

        <p>Developed by LOHINI S</p>
        <p>B.Tech Artificial Intelligence and Machine Learning Student</p>

        <p>© 2026 Sweet Cravings. All Rights Reserved.</p>
    </footer>

</body>
</html>
```

style.css
```


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #fff8f5;
    color: #59434b;
}


header {
    background-color: #f5c6d6;
    text-align: center;
    padding: 25px;
    color: #713f53;
}

header h1 {
    font-size: 35px;
}

header p {
    margin-top: 8px;
}


nav {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 35px;
    background-color: #d9c4e8;
    padding: 18px;
    flex-wrap: wrap;
}

nav a {
    text-decoration: none;
    color: #503d58;
    font-weight: bold;
}

nav a:hover {
    color: #ffffff;
}


.home {
    text-align: center;
    padding: 90px 20px;
    background-color: #ffe8ed;
}

.home h2 {
    font-size: 32px;
    color: #a64d79;
    margin-bottom: 15px;
}

.home p {
    margin: 10px;
}

.btn {
    display: inline-block;
    background-color: #c47b9c;
    color: white;
    padding: 12px 25px;
    margin-top: 20px;
    text-decoration: none;
    border-radius: 25px;
}

.btn:hover {
    background-color: #9e5274;
}


section {
    padding: 50px 30px;
    text-align: center;
}

section h2 {
    color: #a64d79;
    margin-bottom: 30px;
}


.product-container {
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 25px;
    flex-wrap: wrap;
}

.product {
    background-color: #ffffff;
    width: 240px;
    padding: 15px;
    border-radius: 15px;
    box-shadow: 0 3px 10px #e6cbd5;
    transition: transform 0.3s;
}

.product:hover {
    transform: translateY(-8px);
}

.product img {
    width: 100%;
    height: 170px;
    object-fit: cover;
    border-radius: 10px;
}

.product h3 {
    margin: 15px 0 8px;
    color: #9c5575;
}

.product p {
    font-size: 14px;
    margin-bottom: 10px;
}

.product h4 {
    color: #bd658b;
}


.about {
    background-color: #f8e5ed;
    line-height: 1.8;
}


.account {
    background-color: #fff0f5;
}

input {
    padding: 12px;
    margin: 8px;
    border: 1px solid #d9aabd;
    border-radius: 8px;
}

button {
    padding: 12px 25px;
    background-color: #c47b9c;
    color: white;
    border: none;
    border-radius: 8px;
    cursor: pointer;
}

button:hover {
    background-color: #9e5274;
}

/* Footer */
footer {
    background-color: #b88eaa;
    color: white;
    text-align: center;
    padding: 30px;
}

footer h3 {
    margin-bottom: 10px;
}

footer a {
    color: white;
    text-decoration: none;
    margin: 10px;
}

footer p {
    margin-top: 12px;
}

@media (max-width: 600px) {
    nav {
        gap: 15px;
    }

    .home h2 {
        font-size: 25px;
    }

    .product {
        width: 100%;
        max-width: 300px;
    }
}

```

## OUTPUT
1. Home Page and Products

2. Products, About and Contact

3. User Account and Footer



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
