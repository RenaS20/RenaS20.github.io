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
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
        }

        section {
            margin-bottom: 2rem;
            flex: 1;
        }

        .about-section {
            display: flex;
            align-items: center;
            gap: 2rem;
        }

        .about-section img {
            width: 200px;
            height: auto;
            border-radius: 10px;
        }

        .about-section .details {
            text-align: left;
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

    <nav>
        <a href="#about">About</a>
        <a href="experience.html">Experience</a>
        <a href="coursework.html">Coursework</a>
        <a href="contact.html">Contact</a>
    </nav>

    <div class="container">
        <section id="about" class="about-section">
            <img src="Rena_Linkedin.jpg" alt="Rena Shrestha">
            <div class="details">
                <h2>About Me</h2>
                <p>Hello! My name is Rena, and I’m a first-year Data Science major with a domain emphasis in Economics. I’m passionate about using data as a tool to overcome and address challenges faced by businesses.I am interested to exploring the intersection of data and economics and cannot wait to explore more as I learn and grow!</p>
                <p><strong>Rena Shrestha</strong><br>
                UC Berkeley | Class of 2028<br>
                B.A. in Data Science</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Rena Shrestha. All rights reserved.</p>
    </footer>
</body>
</html>
