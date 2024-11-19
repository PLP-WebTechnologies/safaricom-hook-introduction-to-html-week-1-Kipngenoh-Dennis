[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.


##Answer

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="width=device-width, initial-scale=1.0">
    <title>Safaricom Hoot Amazing Journey</title>
    <style>
        /* Basic styles for readability */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        footer {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My  Webpage</h1>
        <nav>
            <ul>
                <li><a href="#about" title="Learn about us">About</a></li>
                <li><a href="#services" title="Discover our services">Services</a></li>
                <li><a href="#contact" title="Get in touch">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <!-- About Section -->
        <section id="about">
            <h2>About Us</h2>
            <p>We are dedicated to delivering top-notch solutions to our clients. Our mission is to make technology accessible and useful for everyone.</p>
            <img src="C:\Users\bradl\OneDrive\Desktop\PLP\download.jpeg" alt="Example of our work">
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Our Services</h2>
            <article>
                <h3>Web Design</h3>
                <p>We create modern, responsive websites tailored to your business needs.</p>
            </article>
            <article>
                <h3>SEO Optimization</h3>
                <p>Our SEO strategies improve your website's visibility and ranking on search engines.</p>
            </article>
            <ul>
                <li>Custom Web Development</li>
                <li>Mobile-Friendly Design</li>
                <li>Content Marketing</li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Have questions? Reach out to us anytime at:</p>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Simple Webpage. All Rights Reserved.</p>
        
    </footer>
</body>
</html>


