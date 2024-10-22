<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Suriya Sharmin Mim - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Suriya Sharmin Mim</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#extra">Extra Info</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>Hi, I'm Suriya Sharmin Mim, a 23-year-old passionate about web development and design. I enjoy creating beautiful, functional websites and exploring new technologies in the field.</p>
        </div>
    </section>

    <section id="extra" class="section">
        <div class="container">
            <h2>Extra Information</h2>
            <p>I am always eager to learn new skills and take on new challenges. In addition to web development, I have a strong interest in graphic design and user experience.</p>
            <ul>
                <li>Age: 23</li>
                <li>Location: [Your City]</li>
                <li>Skills: HTML, CSS, JavaScript, and more</li>
                <li>Interests: Web Development, Graphic Design, UI/UX</li>
            </ul>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch, feel free to email me at <a href="mailto:your.email@example.com">your.email@example.com</a>.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Suriya Sharmin Mim. All rights reserved.</p>
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
    background-color: #4CAF50;
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
    font-size: 18px;
}

.section {
    padding: 40px 0;
    text-align: center;
}

.section h2 {
    margin-bottom: 20px;
    font-size: 28px;
}

.section p {
    margin-bottom: 20px;
    font-size: 18px;
}

ul {
    list-style: disc;
    margin: 20px auto;
    text-align: left;
    max-width: 500px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
