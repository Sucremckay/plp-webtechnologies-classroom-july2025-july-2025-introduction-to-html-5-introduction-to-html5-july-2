# 📘 Assignment: HTML5 + Accessibility & SEO Basics

## Overview

This assignment will help you solidify your understanding of modern HTML5 structure while applying foundational concepts of web accessibility and search engine optimization (SEO). You’ll create a simple, semantically correct web page that prioritizes both human and machine readability—two pillars of great web design.

## Objective

Build a basic web page using HTML5 semantic tags, applying accessibility best practices and beginner-friendly SEO principles. Your final output should demonstrate a well-structured layout that supports screen readers and is optimized for discoverability.

## Guidelines

Use only HTML5. No CSS or JavaScript is required at this stage. Focus on using meaningful semantic elements to structure your page. Avoid using `<div>` or `<span>` unless absolutely necessary. Ensure your page has clearly defined sections such as a header, navigation, main content, and a footer.

Incorporate accessibility by using proper HTML5 landmarks and attributes that improve navigation for assistive technologies. Your HTML should reflect thoughtful planning of hierarchy and readability, both for users and search engines.

For SEO, emphasize the use of heading tags in the correct order, provide descriptive text, and ensure your content is both human-readable and crawler-friendly. Consider how a search engine would interpret your page in terms of structure and content clarity.

## Deliverables

A single HTML file named `index.html`. It should include:

* A semantic structure using appropriate HTML5 elements.
* Clear headings in a logical hierarchy.
* Accessibility enhancements using proper tags and attributes.
* SEO-friendly metadata and content.

## Tips

* Use HTML5 semantic tags appropriately.
* Organize content with accessibility in mind.
* Apply basic on-page SEO techniques.
* Follow clean, readable HTML code structure.


<!DOCTYPE html>
‎<html lang="en">
‎
‎<head>
‎    <meta charset="UTF-8">
‎    <meta name="viewport" content="width=device-width, initial-scale=1.0">
‎    <meta name="description" content="Welcome to our website, where you can find a range of services to help you achieve your goals. Learn more about what we offer and get in touch.">
‎    <meta name="keywords" content="services, solutions, goals, contact">
‎    <meta name="author" content="Your Company Name">
‎    <title>Welcome to Our Company</title>
‎    <!-- SEO: Proper metadata for search engines -->
‎</head>
‎
‎<body>
‎    <header>
‎        <nav>
‎            <ul>
‎                <li><a href="#home" title="Go to Home Page">Home</a></li>
‎                <li><a href="#services" title="View Our Services">Services</a></li>
‎                <li><a href="#about" title="Learn About Us">About Us</a></li>
‎                <li><a href="#contact" title="Contact Us">Contact</a></li>
‎            </ul>
‎        </nav>
‎    </header>
‎
‎    <main>
‎        <section id="home">
‎            <h1>Welcome to Our Company</h1>
‎            <p>We are committed to helping you achieve your goals with the best solutions tailored to your needs. Explore what we can do for you!</p>
‎        </section>
‎
‎        <section id="services">
‎            <h2>Our Services</h2>
‎            <p>We offer a wide range of services designed to meet your needs. From consulting to implementation, we’re here to help you succeed.</p>
‎            <ul>
‎                <li><h3>Consulting</h3><p>Expert advice to guide your decisions.</p></li>
‎                <li><h3>Implementation</h3><p>Efficient and effective project implementation.</p></li>
‎                <li><h3>Support</h3><p>Ongoing support to ensure success.</p></li>
‎            </ul>
‎        </section>
‎
‎        <section id="about">
‎            <h2>About Us</h2>
‎            <p>We are a team of passionate professionals who work tirelessly to deliver top-notch solutions. With over 10 years of experience, we know what it takes to help you succeed.</p>
‎        </section>
‎
‎        <section id="contact">
‎            <h2>Contact Us</h2>
‎            <p>If you have any questions or would like to get in touch, we’d love to hear from you!</p>
‎            <address>
‎                <p>Email us at: <a href="mailto:info@yourcompany.com">info@yourcompany.com</a></p>
‎                <p>Call us: <a href="tel:+1234567890">+1 (234) 567-890</a></p>
‎            </address>
‎        </section>
‎    </main>
‎
‎    <footer>
‎        <p>&copy; 2025 Your Company Name. All rights reserved.</p>
‎    </footer>
‎
‎</body>
‎
‎</html>
‎
