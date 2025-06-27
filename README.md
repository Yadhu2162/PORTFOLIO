<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Yadhu | Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #000, #333);
      color: black;
    }
    header {
      background: #154de8;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #00ffd5;
    }
    nav a {
      margin: 0 15px;
      color: #ddd;
      text-decoration: none;
    }
    section {
      padding: 3rem;
    }
    .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .project-card {
      background: #222;
      padding: 1rem;
      border-radius: 8px;
      width: 250px;
      box-shadow: 0 0 10px rgba(0,255,213,0.2);
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi, I'm Yadhu</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section id="about">
    <h2>About Me</h2>
    <p>A passionate developer creating awesome things.</p>
  </section>
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Project One</h3>
        <p>Description goes here</p>
      </div>
      <div class="project-card">
        <h3>Project Two</h3>
        <p>Description goes here</p>
      </div>
    </div>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: yourname@example.com</p>
  </section>
</body>
</html>
