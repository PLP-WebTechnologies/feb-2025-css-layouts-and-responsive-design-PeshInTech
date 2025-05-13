# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Layouts and Responsive Design</title>
    <link rel="stylesheet" href="layout-styles.css">
</head>
<body>
    <header class="navbar">
        <h1>My Responsive Site</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main class="content">
        <section class="hero" id="home">
            <h2>Welcome to My Responsive Website</h2>
            <p>This is a demonstration of CSS Flexbox and Grid layouts.</p>
        </section>
        <section class="about" id="about">
            <h2>About</h2>
            <p>Learn more about the power of responsive design and flexible layouts.</p>
        </section>
        <section class="services" id="services">
            <h2>Services</h2>
            <div class="service-grid">
                <div class="service">Web Design</div>
                <div class="service">Web Development</div>
                <div class="service">SEO Optimization</div>
                <div class="service">Content Creation</div>
            </div>
        </section>
        <section class="contact" id="contact">
            <h2>Contact</h2>
            <p>Get in touch to discuss your next project.</p>
        </section>
    </main>
    
    <footer>
        <p>© 2025 My Responsive Site. All rights reserved.</p>
    </footer>
</body>
</html>
