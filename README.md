<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
            position: relative;
        }

        header img {
            position: absolute;
            top: 10px;
            right: 10px;
            width: 50px;
            height: 50px;
            border-radius: 50%;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            text-align: center;
        }

        nav a:hover {
            background-color: #575757;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            padding: 2rem;
        }

        section {
            margin-bottom: 2rem;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Professional Webpage</h1>
        <p>Your tagline or professional slogan goes here</p>
        <img src="/mnt/data/Linkedin R_.jpg" alt="Your Profile Picture">
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Write a brief introduction about yourself, your background, and what you do.</p>
        </section>

        <section id="services">
            <h2>Services</h2>
            <p>List the professional services or skills you offer.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Provide your contact information or a form for visitors to reach out to you.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
