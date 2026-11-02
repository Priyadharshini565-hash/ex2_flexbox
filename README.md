# Ex02 Commercial Website
## Date:02/11/2026

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
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ElectroHub - Electronics Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">Electro<span>Hub.</span></div>

        <div class="search">
            <input type="text" placeholder="Search electronics...">
            <button>Search</button>
        </div>

        <div class="account-link">
            <a href="#account">My Account</a>
        </div>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#categories">Categories</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#account">Account</a>
    </nav>

    <!-- Homepage / Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <p class="tagline">WELCOME TO ELECTROHUB</p>

            <h1>Upgrade Your World<br>With Latest Technology</h1>

            <p>
                Discover the latest smartphones, laptops,
                headphones and smart gadgets at amazing prices.
            </p>

            <a href="#products" class="shop-btn">Shop Now</a>
        </div>
    </section>

    <!-- Categories Section -->
    <section class="categories" id="categories">
        <h2>Shop By Categories</h2>

        <div class="category-container">

            <div class="category-card">
                <div class="category-icon">📱</div>
                <h3>Smartphones</h3>
            </div>

            <div class="category-card">
                <div class="category-icon">💻</div>
                <h3>Laptops</h3>
            </div>

            <div class="category-card">
                <div class="category-icon">🎧</div>
                <h3>Headphones</h3>
            </div>

            <div class="category-card">
                <div class="category-icon">⌚</div>
                <h3>Smart Watches</h3>
            </div>

        </div>
    </section>

    <!-- Products Section -->
    <section class="products" id="products">
        <h2>Featured Products</h2>
        <p class="section-description">
            Explore our latest electronic collections.
        </p>

        <div class="product-container">

            <div class="product-card">
                <img src="images/mobile.jpg"
                     alt="Smartphone">
                <h3>Premium Smartphone</h3>
                <p>Latest smartphone with advanced features.</p>
                <h4>₹24,999</h4>
                <button>Add to Cart</button>
            </div>

            <div class="product-card">
                <img src="images/laptop.jpg"
                     alt="Laptop">
                <h3>High Performance Laptop</h3>
                <p>Powerful laptop for work and entertainment.</p>
                <h4>₹54,999</h4>
                <button>Add to Cart</button>
            </div>

            <div class="product-card">
                <img src="images/headphones.jpg"
                     alt="Wireless Headphones">
                <h3>Wireless Headphones</h3>
                <p>Enjoy high-quality sound and comfort.</p>
                <h4>₹2,499</h4>
                <button>Add to Cart</button>
            </div>

            <div class="product-card">
                <img src="images/smartwatch.jpg"
                     alt="Smart Watch">
                <h3>Smart Watch</h3>
                <p>Track your fitness with smart features.</p>
                <h4>₹3,499</h4>
                <button>Add to Cart</button>
            </div>

        </div>
    </section>

    <!-- About Us Section -->
    <section class="about" id="about">

        <div class="about-image">
            <img src="images/about.jpg"
                 alt="Electronics shopping and technology">
        </div>

        <div class="about-content">
            <p class="tagline">ABOUT ELECTROHUB</p>

            <h2>Your Trusted Electronics Shopping Destination</h2>

            <p>
                ElectroHub is an online electronics store that offers
                the latest technology products at affordable prices.
                We provide quality products, excellent customer
                service and a convenient shopping experience.
            </p>

            <a href="#contact" class="shop-btn">Learn More</a>
        </div>

    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Us</h2>

        <div class="contact-container">
            <div class="contact-info">
                <h3>Get In Touch</h3>
                <p>Email: support@electrohub.com</p>
                <p>Phone: +91 98765 43210</p>
                <p>Location: Chennai, Tamil Nadu</p>
            </div>

            <div class="contact-form">
                <h3>Send Us a Message</h3>

                <form>
                    <input type="text"
                           placeholder="Your Name" required>

                    <input type="email"
                           placeholder="Your Email" required>

                    <textarea
                        placeholder="Your Message" required></textarea>

                    <button type="submit">Submit</button>
                </form>
            </div>
        </div>
    </section>

    <!-- User Account Section -->
    <section class="account" id="account">
        <h2>Welcome to ElectroHub</h2>
        <p>Login or create an account to explore our products.</p>

        <a href="#account" class="shop-btn">Login / Sign Up</a>
    </section>

    <!-- Footer -->
    <footer>
        <h2>ElectroHub.</h2>

        <div class="footer-links">
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </div>

        <div class="social-links">
            <a href="https://www.instagram.com/">Instagram</a>
            <a href="https://www.facebook.com/">Facebook</a>
            <a href="https://www.linkedin.com/">LinkedIn</a>
        </div>

        <p>© 2026 ElectroHub. All Rights Reserved.</p>
    </footer>

</body>
</html>
```
style.css
```

/* STEP 6: GLOBAL STYLES */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f8fafc;
    color: #1e293b;
}

/* STEP 7: HEADER */

header {
    background-color: #101828;
    color: white;
    padding: 18px 7%;

    /* STEP 8: FLEXBOX */
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 15px;
}

.logo {
    font-size: 28px;
    font-weight: bold;
}

.logo span {
    color: #f97316;
}

.search {
    display: flex;
    width: 40%;
}

.search input {
    flex: 1;
    padding: 11px;
    border: none;
    border-radius: 5px 0 0 5px;
}

.search button {
    padding: 11px 18px;
    border: none;
    background-color: #f97316;
    color: white;
    cursor: pointer;
    border-radius: 0 5px 5px 0;
}

.account-link a {
    color: white;
    text-decoration: none;
}

/* NAVIGATION */

nav {
    background-color: #1e293b;
    padding: 16px 7%;

    display: flex;
    justify-content: center;
    gap: 40px;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    font-size: 15px;
    transition: 0.3s;
}

nav a:hover {
    color: #f97316;
}

/* STEP 10: HOMEPAGE WITH BACKGROUND IMAGE */

.hero {
    min-height: 430px;
    background:
        linear-gradient(rgba(16, 24, 40, 0.75),
                        rgba(16, 24, 40, 0.85)),
        url("images/hero.jpg");

    background-size: cover;
    background-position: center;

    display: flex;
    align-items: center;
    padding: 60px 8%;
    color: white;
}

.hero-content {
    max-width: 650px;
}

.tagline {
    color: #f97316;
    font-weight: bold;
    font-size: 13px;
    margin-bottom: 15px;
}

.hero h1 {
    font-size: 42px;
    line-height: 1.3;
    margin-bottom: 18px;
}

.hero-content p {
    line-height: 1.7;
    margin-bottom: 25px;
}

.shop-btn {
    display: inline-block;
    background-color: #f97316;
    color: white;
    padding: 13px 25px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.shop-btn:hover {
    background-color: #ea580c;
    transform: translateY(-3px);
}

/* CATEGORIES SECTION */

.categories {
    padding: 50px 8%;
    text-align: center;
}

.categories h2,
.products h2,
.contact h2 {
    font-size: 30px;
    margin-bottom: 30px;
    color: #101828;
}

/* FLEXBOX CATEGORY CARDS */

.category-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 25px;
}

.category-card {
    background-color: white;
    width: 200px;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 3px 12px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.category-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 8px 18px rgba(0,0,0,0.15);
}

.category-icon {
    font-size: 45px;
    margin-bottom: 15px;
}

.category-card h3 {
    color: #1e293b;
}

/* PRODUCTS SECTION */

.products {
    padding: 50px 8%;
    background-color: #eef2f7;
    text-align: center;
}

.section-description {
    color: #64748b;
    margin-top: -15px;
    margin-bottom: 30px;
}

/* FLEXBOX PRODUCT LAYOUT */

.product-container {
    display: flex;
    justify-content: center;
    align-items: stretch;
    flex-wrap: wrap;
    gap: 25px;
}

/* PRODUCT CARDS */

.product-card {
    background-color: white;
    width: 240px;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 3px 12px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.product-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

/* PRODUCT IMAGES */

.product-card img {
    width: 100%;
    height: 170px;
    object-fit: contain;
    margin-bottom: 15px;
}

.product-card h3 {
    font-size: 17px;
    margin-bottom: 10px;
}

.product-card p {
    color: #64748b;
    font-size: 13px;
    margin-bottom: 15px;
    line-height: 1.5;
}

.product-card h4 {
    color: #f97316;
    font-size: 21px;
    margin-bottom: 15px;
}

.product-card button {
    background-color: #2563eb;
    color: white;
    padding: 11px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

.product-card button:hover {
    background-color: #101828;
}

/* ABOUT SECTION */

.about {
    padding: 65px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 45px;
}

.about-image,
.about-content {
    flex: 1;
}

.about-image img {
    width: 100%;
    max-width: 450px;
    height: 300px;
    object-fit: cover;
    border-radius: 10px;
}

.about-content h2 {
    font-size: 30px;
    margin-bottom: 20px;
    color: #101828;
}

.about-content p:not(.tagline) {
    color: #64748b;
    line-height: 1.8;
    margin-bottom: 25px;
}

/* CONTACT SECTION */

.contact {
    padding: 55px 8%;
    background-color: #eef2f7;
}

.contact h2 {
    text-align: center;
}

.contact-container {
    display: flex;
    justify-content: space-between;
    gap: 40px;
    flex-wrap: wrap;
}

.contact-info,
.contact-form {
    flex: 1 1 280px;
    background-color: white;
    padding: 25px;
    border-radius: 10px;
}

.contact-info h3,
.contact-form h3 {
    margin-bottom: 20px;
    color: #101828;
}

.contact-info p {
    margin-bottom: 15px;
    color: #64748b;
}

.contact-form form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-form input,
.contact-form textarea {
    padding: 12px;
    border: 1px solid #cbd5e1;
    border-radius: 5px;
    font-family: inherit;
}

.contact-form textarea {
    height: 100px;
    resize: vertical;
}

.contact-form button {
    background-color: #f97316;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

.contact-form button:hover {
    background-color: #101828;
}

/* USER ACCOUNT */

.account {
    background-color: #101828;
    color: white;
    padding: 50px 20px;
    text-align: center;
}

.account h2 {
    margin-bottom: 15px;
}

.account p {
    color: #cbd5e1;
    margin-bottom: 25px;
}

/* FOOTER */

footer {
    background-color: #1e293b;
    color: white;
    text-align: center;
    padding: 35px 15px;
}

footer h2 {
    color: #f97316;
}

.footer-links,
.social-links {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
    margin: 20px 0;
}

footer a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

footer a:hover {
    color: #f97316;
}

footer p {
    color: #cbd5e1;
    font-size: 13px;
    margin-top: 20px;
}

/* STEP 12 & 13: RESPONSIVE DESIGN */

@media (max-width: 768px) {

    header {
        flex-direction: column;
    }

    .search {
        width: 100%;
    }

    nav {
        gap: 20px;
    }

    .hero h1 {
        font-size: 32px;
    }

    .about {
        flex-direction: column;
    }

    .about-image img {
        max-width: 100%;
    }

    .contact-container {
        flex-direction: column;
    }
}

@media (max-width: 480px) {

    nav {
        flex-direction: column;
        align-items: center;
        gap: 15px;
    }

    .hero h1 {
        font-size: 27px;
    }

    .categories,
    .products {
        padding: 35px 15px;
    }

    .product-card {
        width: 100%;
        max-width: 300px;
    }

    .category-card {
        width: 100%;
        max-width: 300px;
    }
}
```


## OUTPUT


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
