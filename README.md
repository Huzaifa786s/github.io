<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telecom & BPO Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            padding: 20px;
        }
        .services, .about, .contact, .testimonials, .gallery {
            margin-bottom: 40px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            width: 100%;
            bottom: 0;
        }
        h2 {
            color: #007BFF;
        }
        .service-list, .testimonial-list {
            list-style-type: none;
            padding: 0;
        }
        .service-list li, .testimonial-list li {
            background: white;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #007BFF;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #0056b3;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .social-media {
            text-align: center;
            margin-top: 20px;
        }
        .social-media a {
            margin: 0 10px;
            text-decoration: none;
            color: #007BFF;
            font-size: 24px;
        }
        .social-media a:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Telecom & BPO Services</h1>
        <p>Your Trusted Partner in Communication and Outsourcing</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact Us</a>
        <a href="#testimonials">Testimonials</a>
    </nav>
    <div class="container">
        <!-- Home Section -->
        <section id="home">
            <h2>Welcome to Our Website</h2>
            <p>We provide top-notch telecommunication and BPO services to help your business grow.</p>
        </section>

        <!-- About Section -->
        <section id="about" class="about">
            <h2>About Us</h2>
            <p>We are a leading company in the telecommunication and BPO industry, offering reliable and efficient services to our clients worldwide.</p>
        </section>

        <!-- Services Section -->
        <section id="services" class="services">
            <h2>Our Services</h2>
            <ul class="service-list">
                <li>Telecommunication Solutions (Broadband, VoIP, Mobile Plans)</li>
                <li>Customer Support Services</li>
                <li>Technical Support</li>
                <li>Data Entry and Management</li>
                <li>IT Outsourcing</li>
            </ul>
        </section>

        <!-- Gallery Section -->
        <section id="gallery" class="gallery">
            <h2>Image Gallery</h2>
            <div>
                <img src="https://via.placeholder.com/300" alt="Placeholder Image 1">
                <img src="https://via.placeholder.com/300" alt="Placeholder Image 2">
                <img src="https://via.placeholder.com/300" alt="Placeholder Image 3">
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials" class="testimonials">
            <h2>What Our Clients Say</h2>
            <ul class="testimonial-list">
                <li>"Great service and support! Highly recommended." - Client A</li>
                <li>"Their BPO solutions helped us streamline our operations." - Client B</li>
                <li>"Reliable and efficient telecommunication services." - Client C</li>
            </ul>
        </section>

        <!-- Social Media Links -->
        <div class="social-media">
            <h2>Follow Us</h2>
            <a href="#" target="_blank">&#128247; Instagram</a>
            <a href="#" target="_blank">&#128187; Facebook</a>
            <a href="#" target="_blank">&#128241; Twitter</a>
        </div>
    </div>
    <footer>
        <p>&copy; 2023 Telecom & BPO Services. All rights reserved.</p>
    </footer>
</body>
</html>
