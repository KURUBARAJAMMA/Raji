<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechWave - AI Solutions for Your Business</title>
    <link rel="stylesheet" href="styles.css">
</head>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    color: #333;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}


.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
    background: #007bff;
    color: #fff;
}

.header h1 {
    font-size: 24px;
}

.nav-links {
    display: flex;
    list-style: none;
}

.nav-links li {
    margin: 0 15px;
}

.nav-links a {
    color: #fff;
    text-decoration: none;
}

.btn {
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    font-size: 16px;
}

.primary-btn {
    background: #ff5722;
    color: #fff;
}

.secondary-btn {
    background: #28a745;
    color: #fff;
}


.hero {
    text-align: center;
    padding: 100px 20px;
    background: #f4f4f4;
}

.hero h2 {
    font-size: 36px;
    margin-bottom: 10px;
}

.hero p {
    font-size: 18px;
    color: #666;
}

/* Features Section */
.features {
    padding: 60px 20px;
    background: #fff;
    text-align: center;
}

.feature-list {
    display: flex;
    justify-content: space-around;
}

.feature-item {
    width: 30%;
    padding: 20px;
    border: 1px solid #ddd;
}


.pricing {
    padding: 60px 20px;
    background: #f4f4f4;
    text-align: center;
}

.pricing-options {
    display: flex;
    justify-content: space-around;
}

.pricing-card {
    width: 30%;
    padding: 20px;
    border: 1px solid #ddd;
}

.popular {
    border-color: #ff5722;
}


.contact {
    padding: 60px 20px;
    background: #fff;
    text-align: center;
}

.contact form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

.contact input,
.contact textarea {
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
}


footer {
    text-align: center;
    padding: 20px;
    background: #007bff;
    color: #fff;
}

</style>
<body>
    
    <header class="header">
        <div class="container">
            <h1>TechWave</h1>
            <nav>
                <ul class="nav-links">
                    <li><a href="#features">Features</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
    
            </nav>
        </div>
        <div>
            <a href="#signup" class="btn primary-btn">Get Started</a>
        
        </div>
    </header>

   
    <section class="hero" id="hero">
        <div class="container">
            <h2>Revolutionize Your Business with AI</h2>
            <p>TechWave provides cutting-edge AI solutions to streamline your operations, enhance customer experience, and drive growth.</p>
        </div>
        <div>
            <a href="#signup" class="btn secondary-btn">Get Started Free</a>
        </div>
    </section>

    
    <section class="features" id="features">
        <div class="container">
            <h3>Our Features</h3>
            <div class="feature-list">
                <div class="feature-item">
                    <h4>Automated Analytics</h4>
                    <p>Gain insights with automated data analysis that helps you make informed decisions.</p>
                </div>
                <div class="feature-item">
                    <h4>Personalized AI Solutions</h4>
                    <p>Custom-tailored AI tools that fit your unique business needs.</p>
                </div>
                <div class="feature-item">
                    <h4>24/7 Support</h4>
                    <p>Our team is here around the clock to ensure you get the support you need.</p>
                </div>
            </div>
        </div>
    </section>

    
    <section class="about" id="about">
        <div class="container">
            <h3>About TechWave</h3>
            <p>TechWave is a leading provider of AI solutions for businesses of all sizes. Our mission is to empower companies with AI technology that improves productivity, customer satisfaction, and growth potential.</p>
        </div>
    </section>

    
    <section class="pricing" id="pricing">
        <div class="container">
            <h3>Pricing Plans</h3>
            <div class="pricing-options">
                <div class="pricing-card">
                    <h4>Starter</h4>
                    <p>$29/month</p>
                    <p>Basic AI tools and analytics.</p>
                </div>
                <div class="pricing-card popular">
                    <h4>Professional</h4>
                    <p>$59/month</p>
                    <p>Advanced tools with customized features.</p>
                </div>
                <div class="pricing-card">
                    <h4>Enterprise</h4>
                    <p>Contact Us</p>
                    <p>Full suite of services and 24/7 support.</p>
                </div>
            </div>
        </div>
    </section>

    
    <section class="contact" id="contact">
        <div class="container">
            <h3>Contact Us</h3>
            <p>Have questions? Reach out to us!</p>
            <form action="submit_form.php" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit" class="btn primary-btn">Send Message</button>
            </form>
        </div>
    </section>

    
    <footer>
        <div class="container">
            <p>&copy; 2023 TechWave. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
