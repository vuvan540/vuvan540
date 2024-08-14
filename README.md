<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paban Rawat's Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #1a1a1a;
            color: #fff;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        nav {
            margin: 0;
            padding: 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2rem;
            margin: 1rem;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        h1 {
            margin-top: 0;
        }
        p {
            line-height: 1.6;
        }
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }
        .project {
            flex: 1 1 300px;
            background-color: #e6e6e6;
            padding: 1rem;
            border-radius: 8px;
            transition: transform 0.3s;
        }
        .project:hover {
            transform: translateY(-5px);
        }
        .project h3 {
            margin-top: 0;
        }
        footer {
            background-color: #1a1a1a;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
<header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <h1>Paban Rawat's Portfolio</h1>
</header>

<section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Paban Rawat, a passionate Information Technology student specializing in coding and technology. I thrive on learning new skills and applying them to exciting projects.</p>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="projects">
        <div class="project">
            <h3>Project One</h3>
            <p>This project involved building a responsive web application using HTML, CSS, and JavaScript. It features dynamic content loading and a user-friendly interface.</p>
        </div>
        <div class="project">
            <h3>Project Two</h3>
            <p>In this project, I developed a mobile app using Flutter and Firebase. It includes real-time data synchronization and a robust authentication system.</p>
        </div>
        <!-- Add more projects as needed -->
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:pabanrawat50@gmail.com">pabanrawat50@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/paban-rawat-ba0574242" target="_blank">Connect with me on LinkedIn</a>
" target="_blank">Paban Rawat</a></p>
    <!-- Add more contact information or links as needed -->
</section>

<footer>
    <p>&copy; 2024 Paban Rawat. All rights reserved.</p>
</footer>
</body>
</html>
