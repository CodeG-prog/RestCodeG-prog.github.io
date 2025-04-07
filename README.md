<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nairobi Food Joints - Online Food Marketplace</title>
    <link rel="stylesheet" href="ourstyles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Header/Navigation -->
    <header class="header">
        <div class="container">
            <div class="logo">
                <i class="fas fa-utensils"></i>
                <h1>Nairobi Food Joints</h1>
            </div>
            <nav class="navbar">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#restaurants">Restaurants</a></li>
                    <li><a href="#foods">Foods</a></li>
                    <li><a href="#how-it-works">How It Works</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="auth-buttons">
                <a href="#" class="btn btn-login">Login</a>
                <a href="#" class="btn btn-signup">Sign Up</a>
            </div>
            <div class="mobile-menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h2>Order from your favorite foods from Nairobi food joints</h2>
                <p>Discover and order from hundreds of restaurants and food vendors across Nairobi City</p>
                <div class="search-bar">
                    <input type="text" placeholder="Search for restaurants or food...">
                    <button class="btn btn-search">
                        <i class="fas fa-search"></i> Search
                    </button>
                </div>
            </div>
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Nairobi street food">
            </div>
        </div>
    </section>

    <!-- Featured Restaurants -->
    <section class="featured-restaurants" id="restaurants">
        <div class="container">
            <h2 class="section-title">Featured Restaurants</h2>
            <div class="restaurants-grid">
                <!-- Restaurant Card 1 -->
                <div class="restaurant-card">
                    <div class="restaurant-image">
                        <img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="K'osewe Ranalo Foods">
                    </div>
                    <div class="restaurant-info">
                        <h3>K'osewe Ranalo Foods</h3>
                        <div class="rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                            <span>4.5 (120)</span>
                        </div>
                        <div class="delivery-info">
                            <span><i class="fas fa-motorcycle"></i> Free delivery</span>
                            <span><i class="fas fa-clock"></i> 30-45 min</span>
                        </div>
                        <a href="#" class="btn btn-view">View Menu</a>
                    </div>
                </div>

                <!-- Restaurant Card 2 -->
                <div class="restaurant-card">
                    <div class="restaurant-image">
                        <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Mama Oliech">
                    </div>
                    <div class="restaurant-info">
                        <h3>Mama Oliech</h3>
                        <div class="rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                            <span>4.0 (95)</span>
                        </div>
                        <div class="delivery-info">
                            <span><i class="fas fa-motorcycle"></i> Ksh 100 delivery</span>
                            <span><i class="fas fa-clock"></i> 20-35 min</span>
                        </div>
                        <a href="#" class="btn btn-view">View Menu</a>
                    </div>
                </div>

                <!-- Restaurant Card 3 -->
                <div class="restaurant-card">
                    <div class="restaurant-image">
                        <img src="https://images.unsplash.com/photo-1559847844-5315695dadae?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Nyama Mama">
                    </div>
                    <div class="restaurant-info">
                        <h3>Nyama Mama</h3>
                        <div class="rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span>5.0 (210)</span>
                        </div>
                        <div class="delivery-info">
                            <span><i class="fas fa-motorcycle"></i> Free delivery</span>
                            <span><i class="fas fa-clock"></i> 40-55 min</span>
                        </div>
                        <a href="#" class="btn btn-view">View Menu</a>
                    </div>
                </div>
            </div>
            <div class="view-all">
                <a href="#" class="btn btn-view-all">View All Restaurants</a>
            </div>
        </div>
    </section>

    <!-- Popular Foods Section -->
    <section class="popular-foods" id="foods">
        <div class="container">
            <h2 class="section-title">Popular Foods in Nairobi</h2>
            <div class="food-categories">
                <button class="category-btn active">All</button>
                <button class="category-btn">Nyama Choma</button>
                <button class="category-btn">Ugali & Fish</button>
                <button class="category-btn">Pilau</button>
                <button class="category-btn">Chapati & Beans</button>
                <button class="category-btn">Drinks</button>
            </div>
            <div class="foods-grid">
                <!-- Food Item 1 -->
                <div class="food-card">
                    <div class="food-image">
                        <img src="https://images.unsplash.com/photo-1559847844-5315695dadae?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Nyama Choma">
                        <span class="price">Ksh 850</span>
                    </div>
                    <div class="food-info">
                        <h3>Nyama Choma</h3>
                        <p>Tender roasted meat served with kachumbari</p>
                        <div class="restaurant-name">K'osewe Ranalo Foods</div>
                        <button class="btn btn-add-to-cart">Add to Cart</button>
                    </div>
                </div>

                <!-- Food Item 2 -->
                <div class="food-card">
                    <div class="food-image">
                        <img src="https://images.unsplash.com/photo-1559847844-5315695dadae?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Ugali & Fish">
                        <span class="price">Ksh 650</span>
                    </div>
                    <div class="food-info">
                        <h3>Ugali & Fish</h3>
                        <p>Fresh tilapia with ugali and sukuma wiki</p>
                        <div class="restaurant-name">Mama Oliech</div>
                        <button class="btn btn-add-to-cart">Add to Cart</button>
                    </div>
                </div>

                <!-- Food Item 3 -->
                <div class="food-card">
                    <div class="food-image">
                        <img src="https://images.unsplash.com/photo-1559847844-5315695dadae?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Pilau">
                        <span class="price">Ksh 450</span>
                    </div>
                    <div class="food-info">
                        <h3>Pilau</h3>
                        <p>Flavorful rice dish with tender meat</p>
                        <div class="restaurant-name">Nyama Mama</div>
                        <button class="btn btn-add-to-cart">Add to Cart</button>
                    </div>
                </div>

                <!-- Food Item 4 -->
                <div class="food-card">
                    <div class="food-image">
                        <img src="https://images.unsplash.com/photo-1559847844-5315695dadae?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80" alt="Chapati & Beans">
                        <span class="price">Ksh 250</span>
                    </div>
                    <div class="food-info">
                        <h3>Chapati & Beans</h3>
                        <p>Soft chapatis with stewed beans</p>
                        <div class="restaurant-name">K'osewe Ranalo Foods</div>
                        <button class="btn btn-add-to-cart">Add to Cart</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="how-it-works" id="how-it-works">
        <div class="container">
            <h2 class="section-title">How It Works</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-icon">
                        <i class="fas fa-search-location"></i>
                    </div>
                    <h3>1. Find a Restaurant</h3>
                    <p>Browse through hundreds of restaurants and food joints in Nairobi</p>
                </div>
                <div class="step">
                    <div class="step-icon">
                        <i class="fas fa-utensils"></i>
                    </div>
                    <h3>2. Choose Your Food</h3>
                    <p>Select your favorite dishes from the menu</p>
                </div>
                <div class="step">
                    <div class="step-icon">
                        <i class="fas fa-motorcycle"></i>
                    </div>
                    <h3>3. Delivery or Pickup</h3>
                    <p>Get your food delivered or pick it up yourself</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Seller Registration CTA -->
    <section class="seller-cta">
        <div class="container">
            <div class="cta-content">
                <h2>Are you a food seller in Nairobi?</h2>
                <p>Join our platform and reach thousands of hungry customers</p>
                <a href="#" class="btn btn-register">Register Your Business</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer" id="contact">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-about">
                    <div class="logo">
                        <i class="fas fa-utensils"></i>
                        <h3>Nairobi Food Joints</h3>
                    </div>
                    <p>Connecting food lovers with the best food joints in Nairobi</p>
                    <div class="social-links">
                        <a href="https://x.com/sir_wake"><i class="fab fa-Twitter"></i></a>
                        <a href="https://web.facebook.com/wekesa.masibo"><i class="fab fa-Facebook"></i></a>
                        <a href="https://www.instagram.com/aug_augustine/"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="footer-links">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#restaurants">Restaurants</a></li>
                        <li><a href="#foods">Foods</a></li>
                        <li><a href="#how-it-works">How It Works</a></li>
                    </ul>
                </div>
                <div class="footer-contact">
                    <h4>Contact Us</h4>
                    <ul>
                        <li><i class="fas fa-phone"></i> +254 715641169</li>
                        <li><i class="fas fa-envelope"></i> info@nairobifoodjoints.com</li>
                        <li><i class="fas fa-map-marker-alt"></i> Nairobi, Kenya</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Nairobi Food Joints. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
