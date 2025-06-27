<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Yadhu | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #2b2d42;
      --accent: #ef476f;
      --bg: #f7f9fc;
      --text: #2b2d42;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
    }
    header {
      padding: 2rem;
      text-align: center;
      background: #fff;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      animation: slideIn 1s ease-out forwards;
    }
    header h1 {
      font-size: 3rem;
      color: var(--accent);
    }
    nav {
      margin-top: 1rem;
      animation: fadeIn 1.5s ease-out forwards;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: var(--primary);
      font-weight: 600;
      position: relative;
    }
    nav a::after {
      content: '';
      display: block;
      width: 0%;
      height: 2px;
      background: var(--accent);
      transition: width 0.3s;
    }
    nav a:hover::after {
      width: 100%;
    }
    section {
      padding: 4rem 2rem;
      max-width: 900px;
      margin: auto;
      opacity: 0;
      transform: translateY(50px);
      animation: fadeSlideIn 1s forwards;
    }
    section:nth-of-type(2) { animation-delay: 0.3s; }
    section:nth-of-type(3) { animation-delay: 0.6s; }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }
    .project {
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.05);
      transition: transform 0.3s ease;
    }
    .project:hover {
      transform: translateY(-5px);
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #666;
    }

    @keyframes slideIn {
      from { transform: translateY(-30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes fadeSlideIn {
      to {
        opacity: 1;
        transform: translateY(0);
      }
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

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I'm Yadhu — a front-end developer and creative technologist bringing simplicity and elegance to the web.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Interactive Resume</h3>
        <p>A résumé site with micro-interactions and printable sections.</p>
      </div>
      <div class="project">
        <h3>UI Toolkit</h3>
        <p>Lightweight CSS components you can plug into any project.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📧 <a href="mailto:yourname@example.com">yourname@example.com</a></p>
  </section>

  <footer>
    <p>© 2025 Yadhu. Designed with ❤️ using HTML & CSS.</p>
  </footer>

</body>
</html>
