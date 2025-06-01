<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rena Shrestha</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0f1629;
      color: #d8d8f6;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      background-color: transparent;
    }

    nav .logo {
      font-weight: bold;
      font-size: 1.2rem;
      color: #d8d8f6;
    }

    nav a {
      color: #d8d8f6;
      text-decoration: none;
      margin-left: 1.5rem;
      font-weight: 500;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 4rem 2rem;
      text-align: center;
    }

    .profile-pic {
      width: 180px;
      height: 180px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #d8d8f6;
      margin-bottom: 2rem;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    h2 {
      font-size: 1.5rem;
      font-weight: 600;
      margin-bottom: 1rem;
    }

    p {
      max-width: 600px;
      margin: 0 auto 1.5rem;
      font-size: 1rem;
      line-height: 1.6;
    }

    .icons a {
      color: #d8d8f6;
      margin: 0 0.6rem;
      font-size: 1.4rem;
      transition: color 0.3s;
    }

    .icons a:hover {
      color: #a5b4fc;
    }

    .resume-button {
      margin-top: 1.5rem;
      padding: 0.5rem 1.2rem;
      border: 2px solid #d8d8f6;
      border-radius: 10px;
      text-decoration: none;
      color: #d8d8f6;
      font-weight: 500;
      transition: background 0.3s;
    }

    .resume-button:hover {
      background-color: #1e293b;
    }
  </style>
</head>
<body>

  <nav>
    <div class="logo">RS</div>
    <div>
      <a href="#">projects</a>
      <a href="#">experience</a>
      <a href="#">skills</a>
    </div>
  </nav>

  <div class="container">
    <img src="Rena_Linkedin.jpg" alt="Rena Shrestha" class="profile-pic" />
    <h1>👋 Hi, I'm Rena</h1>
    <h2>First-Year Data Science Major at UC Berkeley</h2>
    <p>
      I'm passionate about using data as a tool to solve challenges faced by businesses.
      I'm especially interested in the intersection of data and economics and excited to grow as I learn more.
    </p>
    <p>
      This summer, I’m building my skills in machine learning and working on data-driven projects.
    </p>
    <a class="resume-button" href="your_resume.pdf" target="_blank">resume</a>
    <div class="icons" style="margin-top: 1.5rem;">
      <a href="https://github.com/yourgithub" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://www.linkedin.com/in/rena-shrestha-970352265/" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:renashrestha@berkeley.edu"><i class="fas fa-envelope"></i></a>
    </div>
  </div>

</body>
</html>
