<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Rena Shrestha</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600&display=swap"
      rel="stylesheet"
    />
    <style>
      body {
        margin: 0;
        font-family: 'Outfit', sans-serif;
        background-color: #0f172a;
        color: #e2e8f0;
      }
      header {
        border-bottom: 1px solid #334155;
        padding: 1rem 2rem;
      }
      header h1 {
        color: #3b82f6;
        font-size: 1.5rem;
        font-weight: bold;
        margin: 0;
      }
      nav {
        max-width: 1000px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1.5rem 2rem;
      }
      nav .left {
        font-weight: bold;
        font-size: 1.1rem;
      }
      nav .right a {
        margin-left: 1.5rem;
        color: #e2e8f0;
        text-decoration: none;
        font-size: 0.95rem;
        font-weight: 500;
      }
      .main-content {
        text-align: center;
        padding: 2rem;
      }
      .profile-pic {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        object-fit: cover;
        margin-bottom: 1rem;
        border: 3px solid #475569;
      }
      h1 {
        font-size: 2.2rem;
        font-weight: 600;
        margin-top: 1rem;
        margin-bottom: 0.5rem;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 0.5rem;
      }
      h2 {
        font-size: 1.3rem;
        font-weight: 600;
        margin-bottom: 1.5rem;
        border-bottom: 2px solid #475569;
        display: inline-block;
        padding-bottom: 0.3rem;
      }
      p {
        max-width: 600px;
        margin: 0 auto 1.2rem auto;
        font-size: 1rem;
        line-height: 1.6;
        color: #cbd5e1;
      }
      .resume-button {
        margin-top: 1.5rem;
        padding: 0.6rem 1.5rem;
        border: 1.5px solid #d8d8f6;
        border-radius: 12px;
        text-decoration: none;
        color: #d8d8f6;
        font-weight: 500;
        background: transparent;
        transition: all 0.3s ease;
        display: inline-block;
      }
      .resume-button:hover {
        background-color: #1f2937;
        box-shadow: 0 2px 8px rgba(100, 116, 139, 0.3);
      }
      .icons {
        margin-top: 1.8rem;
        display: flex;
        justify-content: center;
        gap: 1.5rem;
        font-size: 1.2rem;
      }
      .icons a {
        color: #e2e8f0;
        text-decoration: none;
        transition: color 0.2s;
      }
      .icons a:hover {
        color: #3b82f6;
      }
    </style>
  </head>

  <body>
    <header>
      <h1>Rena Shrestha</h1>
    </header>
    <nav>
      <div class="left">RS</div>
      <div class="right">
        <a href="#">projects</a>
        <a href="#">experience</a>
        <a href="#">skills</a>
      </div>
    </nav>
    <div class="main-content">
      <img
        src="https://i.imgur.com/t1JPBSE.png"
        alt="Profile photo"
        class="profile-pic"
      />
      <h1>👋 Hi, I'm Rena</h1>
      <h2>First-Year Data Science Major at UC Berkeley</h2>
      <p>
        I'm passionate about using data as a tool to solve challenges faced by businesses.
        I'm especially interested in the intersection of data and economics and excited to
        grow as I learn more.
      </p>
      <p>
        This summer, I’m building my skills in machine learning and working on data-driven projects.
      </p>
      <a href="#" class="resume-button">resume</a>
      <div class="icons">
        <a href="#"><span>🌐</span></a>
        <a href="#"><span>🔗</span></a>
        <a href="#"><span>✉️</span></a>
      </div>
    </div>
  </body>
</html>
