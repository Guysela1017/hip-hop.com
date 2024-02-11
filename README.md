<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h1>Welcome to My Website</h1>
            <p>This is a paragraph on the homepage.</p>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>Information about the website or company.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <input type="submit" value="Submit">
            </form>
        </section>
    </main>
    <footer>
        <p>Copyright © Your Website 2024</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
