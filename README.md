<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A-Z Fisheries</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>A-Z Fisheries</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#partners">Partners</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About A-Z Fisheries</h2>
        <p>We are committed to providing sustainable solutions to control the invasive Asian carp population in Illinois waterways. Our mass volume harvesting methods aim to reduce the carp population while creating economic opportunities for local communities.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>For more information, please reach out to us:</p>
        <p>Email: <a href="mailto:swanandy381@gmail.com">swanandy381@gmail.com</a></p>
        <p>Phone: <a href="tel:217-323-3085">217-323-3085</a></p>
    </section>

    <section id="partners">
        <h2>Our Partners</h2>
        <p>We work with various government agencies, universities, and environmental organizations to address the Asian carp issue effectively.</p>
    </section>

    <footer>
        <p>&copy; 2025 A-Z Fisheries. All rights reserved.</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>

// app.js

// Example function to interact with OpenAI API
async function fetchCarpData() {
    const response = await fetch("https://api.openai.com/v1/engines/text-davinci-003/completions", {
        method: "POST",
        headers: {
            "Content-Type": "application/json",
            "Authorization": `Bearer YOUR_API_KEY`
        },
        body: JSON.stringify({
            prompt: "Give me statistics on the invasive Asian carp population in Illinois.",
            max_tokens: 100
        })
    });

    const data = await response.json();
    console.log(data.choices[0].text);
}

fetchCarpData();

/* style.css */

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px 0;
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

Let me know how it goes when you copy and paste this!

