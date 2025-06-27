<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Yadhu | Creative Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0f0f0f;
      --accent: #03dac6;
      --text: #e0e0e0;
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      background: var(--bg);
      font-family: 'Poppins', sans-serif;
      color: var(--text);
      line-height: 1.6;
    }
    header {
      padding: 4rem 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      color: var(--accent);
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      color: var(--text);
      text-decoration: none;
      margin: 0 1rem;
      transition: color 0.3s;
    }
    nav a:hover {
      color: var(--accent);
    }
    .hero {
      display: grid;
      place-items: center;
      padding: 5rem 2rem;
      background: #1a1a1a;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      max-width: 600px;
      text-align: center;
    }
    .projects {
      padding: 4rem 2rem;
      background: #111;
    }
    .projects h2 {
      text-align: center;
      margin-bottom: 2rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }
    .card {
      background: #222;
      padding: 1.5rem;
      border-radius: 12px;
      transition: transform 0.2s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 20px rgba(3,218,198,0.2);
    }
    footer {
      padding: 2rem;
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Yadhu</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section class="hero" id="about">
    <h2>Crafting Digital Experiences</h2>
    <p>I’m a creative front-end developer from Kerala, India, turning code into beautiful, user-focused designs.</p>
  </section>
  <section class="projects" id="projects">
    <h2>Selected Projects</h2>
    <div class="grid">
      <div class="card">
        <h3>Smart Portfolio</h3>
        <p>A dynamic web portfolio powered by GitHub and modern tech stack.</p>
      </div>
      <div class="card">
        <h3>Responsive UI Kit</h3>
        <p>Reusable components with interactive UX and minimalist design.</p>
      </div>
    </div>
  </section>
  <footer id="contact">
    <p>📧 Connect with me: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
  </footer>
</body>
</html>
