<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real Estate Resolutions</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <h1>Real Estate Resolutions</h1>
            <p>Turning Properties into Dreams</p>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Professional Real Estate Photography</h2>
            <button onclick="location.href='#contact'">Book Now</button>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio">
        <h2>Our Work</h2>
        <div class="portfolio-gallery">
            <img src="path-to-image1.jpg" alt="Property Image 1">
            <img src="path-to-image2.jpg" alt="Property Image 2">
            <img src="path-to-image3.jpg" alt="Property Image 3">
            <!-- Add more images as needed -->
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <ul>
            <li>Real Estate Photography</li>
            <li>Drone Photography</li>
            <li>Video Walkthroughs</li>
        </ul>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>With years of experience capturing stunning visuals, we understand what sells properties...</p>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="testimonials">
        <h2>What Our Clients Say</h2>
        <blockquote>
            <p>"Real Estate Resolutions elevated our listings to a whole new level!"</p>
            <cite>- Satisfied Client</cite>
        </blockquote>
        <!-- Add more testimonials as needed -->
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Ready to book? Reach out below!</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Real Estate Resolutions. All Rights Reserved.</p>
    </footer>
</body>
</html>
