<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav {
            background-color: #444;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            width: 80%;
            margin: 20px auto;
        }

        .bio, .skills, .projects, .contact {
            background-color: #fff;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            margin-top: 0;
            color: #333;
        }

        .skills ul, .projects ul {
            list-style: none;
            padding: 0;
        }

        .skills ul li, .projects ul li {
            background-color: #eee;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact-form input[type="submit"] {
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        .contact-form input[type="submit"]:hover {
            background-color: #555;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>

<body>

    <header>
        <h1>John Doe</h1>
        <p>Web Developer | Designer | Programmer</p>
    </header>

    <nav>
        <a href="#bio">Bio</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="bio" class="bio">
            <h2>About Me</h2>
            <p>Hello! I'm John Doe, a passionate web developer with experience in creating dynamic and responsive
                websites. I love coding and am always eager to learn new technologies to enhance my skills.</p>
        </section>

        <section id="skills" class="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>React.js</li>
                <li>Node.js</li>
                <li>Python</li>
            </ul>
        </section>

        <section id="projects" class="projects">
            <h2>Projects</h2>
            <ul>
                <li>Project 1: Personal Blog - A blog website where users can share their thoughts and ideas.</li>
                <li>Project 2: E-commerce Site - A fully functional online store with a shopping cart and payment
                    integration.</li>
                <li>Project 3: Portfolio Website - A personal portfolio website to showcase my work and skills.</li>
            </ul>
        </section>

        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <input type="submit" value="Send Message">
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>

</body>

</html># Intern---123
