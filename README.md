<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akshat - Premium Incense Products from Himachal Pradesh</title>
    <meta name="description" content="Discover Akshat, a spiritual and nature-inspired brand offering pure agarbatti, dhoop, and jauyat from Himachal Pradesh, India. Experience premium incense for puja and rituals.">
    <meta name="keywords" content="Akshat, incense, agarbatti, dhoop, jauyat, hawan samagri, Himachal Pradesh, spiritual products, natural incense">
    <meta name="author" content="Akshit Kumar">
    <link rel="canonical" href="https://www.akshatincense.com/">
    <!-- Favicon placeholder -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🌿</text></svg>">
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            color: #000;
            background: linear-gradient(135deg, #fff 0%, #f5f5f5 100%);
            overflow-x: hidden;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        /* Color Palette */
        .primary { color: #DAA520; } /* Honey Yellow */
        .secondary { color: #DC143C; } /* Ruby Red */
        .neutral { color: #000; }
        .bg-primary { background: linear-gradient(135deg, #DAA520, #FFD700); }
        .bg-secondary { background: linear-gradient(135deg, #DC143C, #FF6347); }
        .shadow { box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255,255,255,0.9);
            backdrop-filter: blur(10px);
            z-index: 1000;
            padding: 10px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav .logo {
            font-size: 24px;
            font-weight: bold;
            color: #DAA520;
        }
        nav ul {
            list-style: none;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #000;
            font-weight: 500;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #DC143C;
        }
        /* Sections */
        section {
            display: none;
            min-height: 100vh;
            padding: 80px 0 40px;
        }
        section.active {
            display: block;
        }
        /* Animations */
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.05);
        }
        /* Buttons */
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: linear-gradient(135deg, #DAA520, #FFD700);
            color: #000;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .btn:hover {
            background: linear-gradient(135deg, #DC143C, #FF6347);
            color: #fff;
        }
        /* Responsive */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                position: absolute;
                top: 100%;
                left: 0;
                width: 100%;
                background: #fff;
                display: none;
            }
            nav ul.active {
                display: flex;
            }
            nav .menu-toggle {
                display: block;
                cursor: pointer;
            }
        }
        /* Specific Styles */
        .hero {
            background: url('https://source.unsplash.com/featured/?himalayas') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0,0,0,0.5);
        }
        .hero-content {
            position: relative;
            z-index: 1;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 18px;
            margin-bottom: 20px;
        }
        .trust-points {
            display: flex;
            justify-content: space-around;
            margin: 40px 0;
        }
        .trust-points div {
            text-align: center;
        }
        .product-cards {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .product-card {
            width: 30%;
            background: #fff;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
        .why-choose {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .why-choose div {
            text-align: center;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            width: 100%;
            padding: 10px;
            background: linear-gradient(135deg, #DAA520, #FFD700);
            border: none;
            border-radius: 5px;
            color: #000;
            cursor: pointer;
        }
        .map {
            height: 400px;
            width: 100%;
        }
    </style>
</head>
<body>
    <nav>
        <div class="container">
            <div class="logo">Akshat</div>
            <div class="menu-toggle" onclick="toggleMenu()">☰</div>
            <ul id="nav-menu">
                <li><a href="#" onclick="showPage('home')">Home</a></li>
                <li><a href="#" onclick="showPage('about')">About Us</a></li>
                <li><a href="#" onclick="showPage('products')">Products</a></li>
                <li><a href="#" onclick="showPage('why-choose')">Why Choose Us</a></li>
                <li><a href="#" onclick="showPage('services')">Services</a></li>
                <li><a href="#" onclick="showPage('contact')">Contact Us</a></li>
            </ul>
        </div>
    </nav>

    <!-- Homepage -->
    <section id="home" class="active">
        <div class="hero">
            <div class="hero-content fade-in">
                <h1 class="primary">Akshat</h1>
                <p class="secondary">Pure, Spiritual, Nature-Inspired Incense from Himachal Pradesh</p>
                <p>Akshat is a home-grown Indian brand dedicated to creating pure, authentic, and spiritually uplifting puja products. Rooted in traditional Indian values and inspired by the serenity of nature, our agarbatti, dhoop, and jauyat are carefully crafted to bring peace, positivity, and devotion into everyday worship.</p>
                <div class="product-categories">
                    <h3>Our Products</h3>
                    <ul>
                        <li>Agarbatti</li>
                        <li>Dhoop</li>
                        <li>Jauyat / Hawan Samagri</li>
                    </ul>
                </div>
                <div class="trust-points">
                    <div><h4>100% Natural</h4><p>Pure ingredients</p></div>
                    <div><h4>Traditional Craft</h4><p>Age-old methods</p></div>
                    <div><h4>Hygienic</h4><p>Modern standards</p></div>
                    <div><h4>Affordable</h4><p>Honest pricing</p></div>
                </div>
                <a href="#" onclick="showPage('contact')" class="btn">Contact Us</a>
                <a href="#" onclick="showPage('contact')" class="btn">Enquiry Now</a>
            </div>
        </div>
    </section>

    <!-- About Us -->
    <section id="about">
        <div class="container">
            <h2 class="primary fade-in">About Our Brand</h2>
            <p class="fade-in">Akshat is a home-grown Indian brand dedicated to creating pure, authentic, and spiritually uplifting puja products. Rooted in traditional Indian values and inspired by the serenity of nature, our agarbatti, dhoop, and jauyat are carefully crafted to bring peace, positivity, and devotion into everyday worship.</p>
            <p class="fade-in">Founded with the vision of offering high-quality incense products made from natural ingredients, we combine age-old methods with modern hygiene and quality standards. Each product is designed to create a calming aroma that enhances meditation, prayer, and sacred rituals.</p>
            <h3 class="secondary fade-in">What We Believe In</h3>
            <ul class="fade-in">
                <li>Natural herbs, resins, and essential oils</li>
                <li>Minimal chemicals & safe ingredients</li>
                <li>Traditional formulations</li>
            </ul>
            <img src="https://source.unsplash.com/featured/?himalayas" alt="Himalayas" class="fade-in hover-scale" style="width:100%; height:300px; object-fit:cover;">
            <img src="https://source.unsplash.com/featured/?incense" alt="Incense" class="fade-in hover-scale" style="width:100%; height:300px; object-fit:cover;">
        </div>
    </section>

    <!-- Products -->
    <section id="products">
        <div class="container">
            <h2 class="primary fade-in">Our Products</h2>
            <div class="product-cards">
                <div class="product-card fade-in hover-scale">
                    <img src="https://source.unsplash.com/featured/?agarbatti" alt="Agarbatti">
                    <h3>Agarbatti</h3>
                    <p>Long-lasting fragrance, Daily puja use, Natural ingredients</p>
                    <p>Usage: For meditation and prayer.</p>
                    <p>Available: Wholesale & Retail</p>
                    <a href="#" onclick="showPage('contact')" class="btn">Enquiry</a>
                </div>
                <div class="product-card fade-in hover-scale">
                    <img src="https://source.unsplash.com/featured/?dhoop" alt="Dhoop">
                    <h3>Dhoop</h3>
                    <p>Rich & smokeless aroma, Ideal for temples & homes</p>
                    <p>Usage: For sacred rituals.</p>
                    <p>Available: Wholesale & Retail</p>
                    <a href="#" onclick="showPage('contact')" class="btn">Enquiry</a>
                </div>
                <div class="product-card fade-in hover-scale">
                    <img src="https://source.unsplash.com/featured/?havan-samagri" alt="Jauyat">
                    <h3>Jauyat / Hawan Samagri</h3>
                    <p>Pure ingredients, Sacred rituals & havan use</p>
                    <p>Usage: For hawan ceremonies.</p>
                    <p>Available: Wholesale & Retail</p>
                    <a href="#" onclick="showPage('contact')" class="btn">Enquiry</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us -->
    <section id="why-choose">
        <div class="container">
            <h2 class="primary fade-in">Why Choose Us</h2>
            <div class="why-choose">
                <div class="fade-in"><i>🌿</i><h4>Natural Ingredients</h4><p>Pure and organic</p></div>
                <div class="fade-in"><i>🕉️</i><h4>Traditional Methods</h4><p>Age-old craftsmanship</p></div>
                <div class="fade-in"><i>⏳</i><h4>Long-lasting Fragrance</h4><p>Enduring aroma</p></div>
                <div class="fade-in"><i>🧼</i><h4>Hygienic Manufacturing</h4><p>Clean and safe</p></div>
                <div class="fade-in"><i>💰</i><h4>Honest Pricing</h4><p>Affordable quality</p></div>
                <div class="fade-in"><i>🙏</i><h4>Suitable for Daily Puja</h4><p>Everyday use</p></div>
            </div>
        </div>
    </section>

    <!-- Services -->
    <section id="services">
        <div class="container">
            <h2 class="primary fade-in">Our Services</h2>
            <ul class="fade-in">
                <li>Wholesale sales of agarbatti & dhoop</li>
                <li>Retail sales</li>
                <li>Bulk orders for temples & shops</li>
                <li>Custom fragrance enquiry</li>
            </ul>
        </div>
    </section>

    <!-- Contact Us -->
    <section id="contact">
        <div class="container">
            <h2 class="primary fade-in">Contact Us</h2>
            <p class="fade-in">📞 Phone: 7876842591</p>
            <p class="fade-in">📧 Email: akshitkumar45105k@gmail.com</p>
            <p class="fade-in">📍 Address: Vill Baghni, P.O. Sidhbari, Teh. Dharamshala, Kangra – 176057, Himachal Pradesh</p>
            <p class="fade-in">GST Number: <span id="gst">Label only</span></p>
            <a href="https://wa.me/7876842591" class="btn fade-in">WhatsApp Us</a>
            <div class="map fade-in">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3424.123456789012!2d76.123456789!3d32.123456789!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMzLCsDA3JzI0LjQiTiA3NsKwMDcnMjQuMyJF!5e0!3m2!1sen!2sin!4v1234567890123!5m2!1sen!2sin" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
            <form class="contact-form fade-in" id="contactForm">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Your Phone">
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send Enquiry</button>
            </form>
        </div>
    </section>

    <script>
        // Navigation
        function showPage(pageId) {
            document.querySelectorAll('section').forEach(section => section.classList.remove('active'));
            document.getElementById(pageId).classList.add('active');
            window.scrollTo(0, 0);
        }

        function toggleMenu() {
            document.getElementById('nav-menu').classList.toggle('active');
        }

        // Animations on scroll
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        });

        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));

        // Form validation
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const formData = new FormData(this);
            // Simple validation
            if (formData.get('name') && formData.get('email') && formData.get('message')) {
                alert('En
