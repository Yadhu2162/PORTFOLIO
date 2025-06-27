<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yadhu Krishna A S | Professional Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="sha512-y..." crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background: #f8f9fa;
            color: #343a40;
            line-height: 1.6;
            overflow-x: hidden;
        }

        header {
            background: linear-gradient(to right, #1e3c72, #2a5298);
            color: #fff;
            padding: 60px 20px;
            text-align: center;
        }

        header img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 4px solid #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }

        header h1 {
            font-size: 3rem;
            animation: fadeInUp 1s ease-in-out;
        }

        header p {
            font-size: 1.3rem;
            margin-top: 10px;
            animation: fadeInUp 1.5s ease-in-out;
        }

        nav {
            background: #fff;
            display: flex;
            justify-content: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        nav a {
            padding: 15px 25px;
            text-decoration: none;
            color: #343a40;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #1e3c72;
        }

        section {
            max-width: 1000px;
            margin: 60px auto;
            padding: 0 20px;
            animation: fadeIn 1s ease-in;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #1e3c72;
        }

        .about p,
        .projects p,
        .contact p {
            font-size: 1.1rem;
            margin-bottom: 20px;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .project-item {
            background: #fff;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .project-item:hover {
            transform: translateY(-5px);
        }

        footer {
            background: #2a2a2a;
            color: #fff;
            text-align: center;
            padding: 30px 10px;
            margin-top: 60px;
        }

        .social-icons a {
            margin: 0 10px;
            color: #fff;
            font-size: 1.5rem;
            transition: color 0.3s;
        }

        .social-icons a:hover {
            color: #007bff;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(40px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>

<body>
    <header>
        <img src="profile.jpg" alt="Yadhu Krishna Profile Photo">
        <h1>Yadhu Krishna A S</h1>
        <p>Law Graduate | Technology Law & Data Privacy Enthusiast</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>I am a dedicated law graduate with a strong focus on technology law, data privacy, and digital rights. My academic and project experience span across AI regulation, dark patterns, intermediary liability, and blockchain use cases in legal frameworks. I’m passionate about bridging the gap between law and emerging technologies.</p>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-grid">
            <div class="project-item">
                <img src="project1.jpg" alt="Dark Patterns Project" style="width:100%; border-radius:8px; margin-bottom:10px;">
                <h3>Dark Patterns & User Rights</h3>
                <p>Analyzed the legal implications of deceptive UI design practices in Indian and EU digital laws, highlighting Planet49 and India’s 2023 Guidelines.</p>
            </div>
            <div class="project-item">
                <img src="project2.jpg" alt="Blockchain IPR Project" style="width:100%; border-radius:8px; margin-bottom:10px;">
                <h3>Blockchain for IPR Management</h3>
                <p>Researched blockchain solutions for copyright and patent management, ensuring transparency and traceability in rights enforcement.</p>
            </div>
            <div class="project-item">
                <img src="project3.jpg" alt="AI Compliance Project" style="width:100%; border-radius:8px; margin-bottom:10px;">
                <h3>AI & Data Protection Compliance</h3>
                <p>Developed a compliance framework for large language models across GDPR, India DPDP Act, and other international regulations.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:yadhukrishna4mail@gmail.com">yadhukrishna4mail@gmail.com</a></p>
               <p>Phone: +91 7356376050</p>
        <div class="social-icons">
            <a href="https://github.com/yadhukrishna" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://linkedin.com/in/yadhukrishna" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="mailto:yadhukrishna4mail@gmail.com"><i class="fas fa-envelope"></i></a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Yadhu Krishna A S. All rights reserved.</p>
    </footer>
</body>

</html>
