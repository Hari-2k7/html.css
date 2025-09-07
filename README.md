# html.css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* Reset default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
    }

    /* Navbar */
    nav {
      background: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
      position: sticky;
      top: 0;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #f39c12;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(to right, #3498db, #2ecc71);
      color: white;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2rem;
    }

    /* Sections */
    section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      margin-bottom: 20px;
      text-align: center;
    }

    /* Projects */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      text-align: center;
    }

    .project-card h3 {
      margin-bottom: 10px;
    }

    /* Contact */
    .contact {
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      background: #333;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    .contact a:hover {
      background: #f39c12;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #333;
      color: #fff;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Hero -->
  <section class="hero" id="home">
    <h1>Hello, I'm Hari</h1>
    <p>Aspiring Developer & Tech Enthusiast 🚀</p>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a passionate student learning web development and AI. 
      I love building projects that solve real-world problems 
      and experimenting with new technologies.
    </p>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>A personal website to showcase my skills and work.</p>
      </div>
      <div class="project-card">
        <h3>AI SQL Assistant</h3>
        <p>An AI-powered assistant that generates secure SQL queries.</p>
      </div>
      <div class="project-card">
        <h3>Database Optimizer</h3>
        <p>A tool to clean and manage poorly structured databases.</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <a href="mailto:hari@example.com">Email</a>
    <a href="https://linkedin.com" target="_blank">LinkedIn</a>
  </section>

  <footer>
    <p>© 2025 Hari. All rights reserved.</p>
  </foo


