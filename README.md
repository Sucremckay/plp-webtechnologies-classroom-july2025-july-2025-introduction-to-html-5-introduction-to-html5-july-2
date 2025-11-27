# 📘 /* Assignment1 : HTML5 + Accessibility & SEO Basics

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
* Follow clean, readable HTML code structure.*/




/* html-wk1-assignment */

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



/* html-wk2-assignment:

Submit a single HTML file named enhanced-form.html. It should include:

Well-structured content using lists, tables, and media.

A complete HTML5 form including a variety of input fields.

Correct use of form attributes such as placeholder, required, autocomplete, and readonly.

HTML5 validation features implemented correctly across all relevant fields.

A clear, accessible layout using semantic tags.*/


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enhanced Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        section {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #333;
        }
        form {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        label {
            font-weight: bold;
            margin-bottom: 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="checkbox"] {
            width: auto;
        }
        button {
            grid-column: span 2;
            padding: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 4px;
        }
        button:hover {
            background-color: #218838;
        }
        .form-section {
            margin-bottom: 20px;
        }
        .list-style {
            list-style-type: square;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table th, table td {
            padding: 10px;
            border: 1px solid #ccc;
        }
        table th {
            background-color: #f2f2f2;
        }
        .media {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<header>
    <h1>Enhanced HTML5 Form</h1>
</header>

<section>
    <h2>Personal Information</h2>
    <form action="#" method="post">
        <!-- Name Field -->
        <div class="form-section">
            <label for="full-name">Full Name:</label>
            <input type="text" id="full-name" name="full-name" placeholder="John Doe" required autocomplete="name">
        </div>

        <!-- Email Field -->
        <div class="form-section">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="example@mail.com" required autocomplete="email">
        </div>

        <!-- Phone Number Field -->
        <div class="form-section">
            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" placeholder="123-456-7890" required autocomplete="tel">
        </div>

        <!-- Date of Birth Field -->
        <div class="form-section">
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
        </div>

        <!-- Gender Selection -->
        <div class="form-section">
            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="" disabled selected>Select your gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
        </div>

        <!-- Subscribe Checkbox -->
        <div class="form-section">
            <label for="subscribe">
                <input type="checkbox" id="subscribe" name="subscribe" checked> Subscribe to newsletter
            </label>
        </div>

        <!-- Comments Section -->
        <div class="form-section">
            <label for="comments">Comments:</label>
            <textarea id="comments" name="comments" rows="4" placeholder="Write your comments here..." autocomplete="off"></textarea>
        </div>

        <button type="submit">Submit</button>
    </form>
</section>

<section>
    <h2>Additional Information</h2>

    <!-- List -->
    <h3>Top Programming Languages:</h3>
    <ul class="list-style">
        <li>JavaScript</li>
        <li>Python</li>
        <li>Java</li>
        <li>Ruby</li>
    </ul>

    <!-- Table -->
    <h3>Course Details</h3>
    <table>
        <tr>
            <th>Course</th>
            <th>Duration</th>
            <th>Instructor</th>
        </tr>
        <tr>
            <td>Web Development</td>
            <td>3 Months</td>
            <td>John Smith</td>
        </tr>
        <tr>
            <td>Data Science</td>
            <td>6 Months</td>
            <td>Jane Doe</td>
        </tr>
        <tr>
            <td>Machine Learning</td>
            <td>4 Months</td>
            <td>Jim Bean</td>
        </tr>
    </table>

    <!-- Media Section -->
    <h3>Our Office Location</h3>
    <img src="https://via.placeholder.com/800x400" alt="Office Location" class="media">
    <p>We are located at the heart of the city. Our office hours are 9 AM to 5 PM, Monday through Friday.</p>
</section>

</body>
</html>


/* html-wk3-Assignment:
‎Submit the following files:
‎
‎index.html: A basic HTML page with structured content.
‎
‎styles.css: Your external stylesheet containing all your CSS rules.
‎
‎Both files should work together to showcase:
‎
‎Proper use of selectors and basic styling properties
‎
‎Clear implementation of the CSS Box Model
‎
‎Consistent spacing, sizing, and layout styling */
‎
‎
‎/* index.html */
‎<!DOCTYPE html>
‎<html lang="en">
‎<head>
‎    <meta charset="UTF-8">
‎    <meta name="viewport" content="width=device-width, initial-scale=1.0">
‎    <title>Basic HTML and CSS Example</title>
‎    <link rel="stylesheet" href="styles.css">
‎</head>
‎<body>
‎    <header>
‎        <h1>Welcome to My Website</h1>
‎        <p>This is a basic page demonstrating HTML and CSS styling.</p>
‎    </header>
‎
‎    <section class="content">
‎        <article>
‎            <h2>Article 1</h2>
‎            <p>This is some content for the first article. It demonstrates basic layout and styling.</p>
‎        </article>
‎
‎        <article>
‎            <h2>Article 2</h2>
‎            <p>This is some content for the second article. It demonstrates basic layout and styling as well.</p>
‎        </article>
‎    </section>
‎
‎    <footer>
‎        <p>&copy; 2025 My Website</p>
‎    </footer>
‎</body>
‎</html>
‎
‎
‎/* style.css */
‎/* Resetting default margin and padding */
‎* {
‎    margin: 0;
‎    padding: 0;
‎    box-sizing: border-box;
‎}
‎
‎/* Body styling */
‎body {
‎    font-family: Arial, sans-serif;
‎    line-height: 1.6;
‎    background-color: #f4f4f4;
‎    color: #333;
‎    margin: 0;
‎    padding: 20px;
‎}
‎
‎/* Header styling */
‎header {
‎    background-color: #333;
‎    color: #fff;
‎    padding: 20px;
‎    text-align: center;
‎    margin-bottom: 20px;
‎}
‎
‎header h1 {
‎    margin: 0;
‎    font-size: 2.5rem;
‎}
‎
‎header p {
‎    font-size: 1rem;
‎}
‎
‎/* Content section styling */
‎.content {
‎    display: flex;
‎    justify-content: space-between;
‎    gap: 20px;
‎    margin-bottom: 20px;
‎}
‎
‎article {
‎    background-color: #fff;
‎    border: 1px solid #ddd;
‎    padding: 20px;
‎    width: 48%; /* Flexbox will manage spacing */
‎    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
‎}
‎
‎article h2 {
‎    margin-bottom: 15px;
‎    font-size: 1.5rem;
‎}
‎
‎article p {
‎    font-size: 1rem;
‎    line-height: 1.5;
‎}
‎
‎/* Footer styling */
‎footer {
‎    background-color: #333;
‎    color: #fff;
‎    text-align: center;
‎    padding: 10px;
‎}
‎
‎
‎
