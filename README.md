<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome to my portfolio website! I'm a passionate [your profession] based in [your location]. Here you can learn more about me and my work.</p>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <!-- Your portfolio items go here -->
            <div class="portfolio-item">
                <img src="portfolio-item1.jpg" alt="Portfolio Item 1">
                <h3>Project Name</h3>
                <p>Description of the project...</p>
            </div>
            <div class="portfolio-item">
                <img src="portfolio-item2.jpg" alt="Portfolio Item 2">
                <h3>Project Name</h3>
                <p>Description of the project...</p>
            </div>
            <!-- Add more portfolio items as needed -->
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me via the form below or through my email: example@example.com</p>
            <form action="send_message.php" method="post">
                <input type="text" name="name" placeholder="Your Name">
                <input type="email" name="email" placeholder="Your Email">
                <textarea name="message" placeholder="Your Message"></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
