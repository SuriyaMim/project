<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I'm [Your Name], a passionate web developer. I specialize in creating stunning and functional websites. Feel free to check out my projects below.</p>
        </div>
    </section>

    <section id="projects" class="section">
        <div class="container">
            <h2>Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>Description of the project.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>Description of the project.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Project 3</h3>
                    <p>Description of the project.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me via email at <a href="mailto:your.email@example.com">your.email@example.com</a>.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 [Your Name]. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

header h1 {
    text-align: center;
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.section {
    padding: 40px 0;
    text-align: center;
}

.project-grid {
    display: flex;
    justify-content: space-between;
    gap: 20px;
}

.project-card {
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    width: 30%;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.project-card h3 {
    margin-bottom: 10px;
}

.project-card p {
    margin-bottom: 15px;
}

.project-card .btn {
    display: inline-block;
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

.project-card .btn:hover {
    background-color: #555;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}


