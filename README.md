<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Homepage</title>
    <link rel="stylesheet" href="styles.css"> <!-- Optional CSS link -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
        }
        main {
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Homepage</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>This is a brief introduction about myself. I am learning web development and creating simple web pages.</p>
        </section>
        <section id="projects">
            <h2>My Projects</h2>
            <p>Here are some of my projects:</p>
            <ul>
                <li>Project 1: Description</li>
                <li>Project 2: Description</li>
                <li>Project 3: Description</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <p>You can reach me at myemail@example.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Homepage</p>
    </footer>
</body>
</html>
