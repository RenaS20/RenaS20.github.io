<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hi, I'm Rena</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #1A1D3A;
      color: #E1E1FF;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
    }

    header {
      width: 100%;
      display: flex;
      justify-content: flex-end;
      gap: 2rem;
      padding: 1rem 2rem;
      font-weight: 600;
      font-size: 1rem;
    }

    header a {
      color: #E1E1FF;
      text-decoration: none;
    }

    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      max-width: 700px;
      text-align: center;
    }

    .hero img {
      border-radius: 50%;
      width: 200px;
      height: 200px;
      object-fit: cover;
      margin-bottom: 1rem;
    }

    .hero h1 {
      font-size: 2.5rem;
    }

    .hero h2 {
      font-size: 1.5rem;
      margin: 0.5rem 0;
    }

    .hero p {
      font-size: 1rem;
      line-height: 1.6;
      color: #C7C9FF;
    }

    .social-icons {
      margin-top: 1.5rem;
    }

    .social-icons a {
      margin: 0 0.5rem;
      font-size: 1.3rem;
      color: #C7C9FF;
    }

    .resume-button {
      border: 1px solid #C7C9FF;
      border-radius: 9999px;
      padding: 0.5rem 1rem;
      font-size: 1rem;
      margin-top: 1.5rem;
      color: #C7C9FF;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <a href="#">TJ</a>
    <a href="#">projects</a>
    <a href="#">experience</a>
    <a href="#">skills</a>
    <i class="fas fa-cog"></i>
  </header>

  <section class="hero">
    <img src="Rena_Linkedin.jpg" alt="Rena Shrestha" />
    <h1><span style="font-size: 1.5rem;">👋</span> Hi, I'm [Your Name]</h1>
    <h2>Sophomore studying Data Science major with a concentration in Economics at UC Berkeley</h2>
    <p>I'm passionate about leveraging data science to tell compelling stories, address real-world challenges, and influence meaningful strategies.</p>
    <p>I am interested in exploring the intersection of data and economics and cannot wait to learn more through my classes and opportunities!</p>

    <a class="resume-button" href="your-resume.pdf" target="_blank">resume</a>
    <div class="social-icons">
      <a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://linkedin.com/in/yourusername" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:youremail@example.com"><i class="fas fa-envelope"></i></a>
    </div>
  </section>
</body>
</html>
