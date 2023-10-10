# portfolio

#html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>My - Portfolio</title>
</head>
<body>
    <header>
        <h1>Ayush Tiwari</h1>
        <p>Web Developer | Designer</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p> My self Ayush Tiwari. I am currently pursuing my Btech from Galgotias University. <br> I have a good command on C, C++ , HTML and currently I a learning python. <br> I am also a Web developer and  Designer. I am working in Bharat Intern program runned by Government of India.</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <!---->
        <div class="project">
            <h3>Temprature Converter</h3>
            <p> I have created a temprature converter in which converts celsius to Fahrenheit using HTML, CSS, JavaScript.</p>
            <a href="#https://github.com/Ayush3025/Temprature/blob/3fcb811b94553a1488e257fb3082d2972ab93875/README.md">View Project</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>mobile number: +91 9151413025 , +91 842907530<br> email: pandit30ayush@gmail.com 
      </p>
    </section>

    <footer>
        <p>&copy; 2023 Ayush Tiwari</p>
    </footer>
</body>
</html>

#css

/* Reset some default styles */
body, h1, h2, h3, p, ul, li, a {
    margin: 0;
    padding: 0;
}

/* Basic styles for the layout */
body {
    font-family: Arial, sans-serif;
    background-color: #f7f7f7;
}

header {
    text-align: center;
    padding: 30px 0;
    background-color: #333;
    color: #fff;
}

header h1 {
    font-size: 36px;
}

header p {
    font-size: 18px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    background-color: #333;
    padding: 10px 0;
}

nav li {
    margin: 0 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

section {
    padding: 40px;
}

h2 {
    font-size: 24px;
    margin-bottom: 20px;
}

.project {
    margin-bottom: 40px;
}

/* Customize other styles as needed */

