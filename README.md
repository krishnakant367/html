<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
        }

        nav {
            background: #34495e;
            padding: 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #3498db;
        }

        section {
            padding: 3rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        #about {
            display: flex;
            gap: 2rem;
            align-items: center;
            flex-wrap: wrap;
        }

        #about img {
            max-width: 200px;
            border-radius: 50%;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }

        .skill-item {
            background: #f4f4f4;
            padding: 1rem;
            text-align: center;
            border-radius: 5px;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 1rem;
        }

        .project-card {
            background: #f4f4f4;
            padding: 1rem;
            border-radius: 5px;
            text-align: center;
        }

        .project-card img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .resume, .contact {
            text-align: center;
        }

        .resume a {
            display: inline-block;
            background: #3498db;
            color: white;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }

        .resume a:hover {
            background: #2980b9;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        @media (max-width: 768px) {
            #about {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <p>Web Developer & Designer</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <img src="https://via.placeholder.com/200" alt="Profile Picture">
        <div>
            <h2>About Me</h2>
            <p>I'm a passionate web developer with 3 years of experience in creating responsive and user-friendly websites. Skilled in HTML, CSS, JavaScript, and modern frameworks, I enjoy turning ideas into reality through clean and efficient code.</p>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills-grid">
            <div class="skill-item">HTML5</div>
            <div class="skill-item">CSS3</div>
            <div class="skill-item">JavaScript</div>
            <div class="skill-item">React</div>
            <div class="skill-item">Node.js</div>
            <div class="skill-item">Git</div>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects-grid">
            <div class="project-card">
                <img src="https://via.placeholder.com/300x200" alt="Project 1">
                <h3>Project One</h3>
                <p>A responsive e-commerce website built with HTML, CSS, and JavaScript.</p>
            </div>
            <div class="project-card">
                <img src="https://via.placeholder.com/300x200" alt="Project 2">
                <h3>Project Two</h3>
                <p>A task management app developed using React and Node.js.</p>
            </div>
            <div class="project-card">
                <img src="https://via.placeholder.com/300x200" alt="Project 3">
                <h3>Project Three</h3>
                <p>A portfolio website showcasing my web development skills.</p>
            </div>
        </div>
    </section>

    <section id="resume" class="resume">
        <h2>Resume</h2>
        <p>Download my resume to learn more about my qualifications and experience.</p>
        <a href="resume.pdf" download>Download Resume</a>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>Email: johndoe@example.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 2025 John Doe. All rights reserved.</p>
    </footer>
</body>
</html>
