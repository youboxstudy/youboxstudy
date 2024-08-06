<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Youbox Study - IIT JEE Coaching</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Youbox Study Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#courses">Courses</a></li>
                <li><a href="#faculty">Faculty</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <div class="banner">
                <h1>Empowering Your IIT JEE Dreams with Youbox Study</h1>
                <a href="#courses" class="cta-button">Join Now</a>
            </div>
            <div class="intro-video">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </section>

        <section id="intro">
            <h2>Welcome to Youbox Study</h2>
            <p>Your success in IIT JEE starts here. With experienced faculty, comprehensive study material, and personalized attention, we ensure that you are well-prepared for your journey ahead.</p>
        </section>

        <section id="featured-courses">
            <h2>Our Courses</h2>
            <div class="course-list">
                <div class="course-item">
                    <h3>Course 1</h3>
                    <p>Details about the course.</p>
                </div>
                <div class="course-item">
                    <h3>Course 2</h3>
                    <p>Details about the course.</p>
                </div>
            </div>
            <a href="#courses" class="cta-button">View All Courses</a>
        </section>

        <section id="testimonials">
            <h2>What Our Students Say</h2>
            <div class="testimonial-slider">
                <div class="testimonial">
                    <p>"Youbox Study transformed my preparation for IIT JEE. The faculty is incredibly supportive!"</p>
                    <cite>- Student Name</cite>
                </div>
                <div class="testimonial">
                    <p>"Thanks to Youbox Study, my child is now confident and ready for the exam!"</p>
                    <cite>- Parent Name</cite>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>Contact Us: 123-456-7890 | info@youboxstudy.com</p>
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">LinkedIn</a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo img {
    height: 50px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.banner {
    background-image: url('banner.jpg');
    background-size: cover;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}

.cta-button {
    background-color: #ff5722;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    display: inline-block;
    margin-top: 20px;
}

main {
    padding: 20px;
}

#intro, #featured-courses, #testimonials {
    margin-bottom: 40px;
}

#featured-courses .course-list {
    display: flex;
    gap: 20px;
}

.course-item {
    background-color: #f0f0f0;
    padding: 20px;
    border-radius: 5px;
}

.testimonial-slider {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

footer .social-media a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
}

