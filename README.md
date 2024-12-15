
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Digital Freelance Academy - Empowering the next generation of digital freelancers.">
    <meta name="keywords" content="freelance, academy, digital skills, Ethiopia, freelancing jobs, courses">
    <title>Digital Freelance Academy (DFA)</title>
    <!-- Include CSS for styling -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <div class="logo">
                <a href="#">DFA</a> <!-- Logo of your academy -->
            </div>
            <ul class="navigation">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#courses">Our Courses</a></li>
                <li><a href="#community">Community</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="hero">
        <h1>Welcome to Digital Freelance Academy (DFA)</h1>
        <p>Empowering Ethiopian youth with digital skills for global freelancing success.</p>
        <button onclick="window.location.href='#courses'">Explore Our Courses</button>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about-us">
        <h2>About Us</h2>
        <p>At DFA, we provide affordable, flexible, and impactful digital freelancing training to empower Ethiopian youth. Our mission is to prepare students for the global freelance marketplace by offering comprehensive digital skills training.</p>
    </section>

    <!-- Courses Section -->
    <section id="courses" class="courses">
        <h2>Our Courses</h2>
        <div class="course-list">
            <div class="course-item">
                <h3>Web Development</h3>
                <p>Learn HTML, CSS, JavaScript, and backend development to start your career as a web developer.</p>
            </div>
            <div class="course-item">
                <h3>Graphic Design</h3>
                <p>Master graphic design using tools like Photoshop and Illustrator to become a freelance designer.</p>
            </div>
            <div class="course-item">
                <h3>Digital Marketing</h3>
                <p>Learn SEO, social media marketing, and content creation to succeed in the digital marketing industry.</p>
            </div>
        </div>
    </section>

    <!-- Community Section -->
    <section id="community" class="community">
        <h2>Join Our Community</h2>
        <p>Get support from our growing freelance community and start building your network today.</p>
        <button onclick="window.location.href='#contact'">Join Now</button>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Have questions? Get in touch with us for more information on our courses or services.</p>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Digital Freelance Academy. All rights reserved.</p>
        <ul class="footer-links">
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Terms & Conditions</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </footer>

    <!-- Include JavaScript for interactivity -->
    <script src="script.js"></script>
</body>
</html>

