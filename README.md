<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Geoflex Tech World Consultancy - Your trusted partner for innovative technology and business solutions.">
    <title>Geoflex Tech World Consultancy</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        /* Header */
        header {
            background: #1a3c6d;
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        nav .logo {
            font-size: 1.8rem;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1rem;
        }

        nav ul li a:hover {
            color: #f4a261;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: url('https://images.unsplash.com/photo-1516321310762-479e93c67c2e') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            margin-top: 80px;
        }

        .hero-content {
            background: rgba(0, 0, 0, 0.5);
            padding: 2rem;
            border-radius: 10px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }

        .btn {
            background: #f4a261;
            color: white;
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .btn:hover {
            background: #e76f51;
        }

        /* About Section */
        .about, .services, .contact {
            max-width: 1200px;
            margin: 4rem auto;
            padding: 0 20px;
        }

        .about h2, .services h2, .contact h2 {
            font-size: 2.5rem;
            margin-bottom: 1.5rem;
            text-align: center;
            color: #1a3c6d;
        }

        .about p {
            font-size: 1.1rem;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }

        /* Services Section */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            background: #f9f9f9;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #1a3c6d;
        }

        /* Contact Section */
        .contact form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }

        .contact input, .contact textarea {
            padding: 0.8rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }

        .contact textarea {
            resize: vertical;
            min-height: 150px;
        }

        .contact button {
            background: #f4a261;
            color: white;
            border: none;
            padding: 1rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }

        .contact button:hover {
            background: #e76f51;
        }

        /* Footer */
        footer {
            background: #1a3c6d;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }

        footer p {
            margin-bottom: 0.5rem;
        }

        footer a {
            color: #f4a261;
            text-decoration: none;
        }

        footer a:hover {
            color: #e76f51;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 10px;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <div class="logo">Geoflex Tech World</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to Geoflex Tech World Consultancy</h1>
            <p>Your trusted partner for innovative technology and business solutions.</p>
            <a href="#contact" class="btn">Get in Touch</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Geoflex Tech World Consultancy is dedicated to empowering businesses with cutting-edge technology solutions. Our team of experts provides tailored strategies in IT consulting, software development, and digital transformation to help you achieve your goals.</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>IT Consulting</h3>
                <p>Strategic IT solutions to optimize your business processes and infrastructure.</p>
            </div>
            <div class="service-card">
                <h3>Software Development</h3>
                <p>Custom software tailored to meet your unique business needs.</p>
            </div>
            <div class="service-card">
                <h3>Digital Transformation</h3>
                <p>Transform your business with modern technologies and data-driven insights.</p>
            </div>
            <div class="service-card">
                <h3>Cloud Solutions</h3>
                <p>Secure and scalable cloud services to enhance efficiency and flexibility.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Geoflex Tech World Consultancy. All rights reserved.</p>
        <p><a href="mailto:info@ezekielgeoffreyizam@gmail.com">info@geoflextech.com</a> | <a href="tel:+1234567890">+ (234) 9084-8401-09 </a></p>
    </footer>

    <script>
        // Basic form submission handling
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! We will get back to you soon.');
            this.reset();
        });
    </script>
</body>
</html>
