# your-username.github.io<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My GitHub Static Website</title>

<style>
/* ===== GLOBAL STYLES ===== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f4f6f8;
    color: #333;
}

/* ===== HEADER ===== */
header {
    background: linear-gradient(135deg, #667eea, #764ba2);
    color: #fff;
    padding: 40px 20px;
    text-align: center;
}

/* ===== NAVBAR ===== */
nav {
    background: #222;
    display: flex;
    justify-content: center;
}

nav a {
    color: #fff;
    text-decoration: none;
    padding: 14px 20px;
}

nav a:hover {
    background: #555;
}

/* ===== CONTENT ===== */
.container {
    max-width: 800px;
    margin: auto;
}

.card {
    background: #fff;
    margin: 30px 15px;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

/* ===== BUTTON ===== */
button {
    background: #667eea;
    color: white;
    border: none;
    padding: 10px 16px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #5563c1;
}

/* ===== FOOTER ===== */
footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}

/* ===== RESPONSIVE ===== */
@media (max-width: 600px) {
    header h1 {
        font-size: 24px;
    }
}
</style>
</head>

<body>

<header>
    <h1>🚀 My GitHub Website</h1>
    <p>Single HTML file • Hosted Free on GitHub Pages</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">

<section id="home" class="card">
    <h2>Home</h2>
    <p>This is a fully static website made using only one HTML file.</p>
    <br>
    <button onclick="showMessage()">Click Me</button>
</section>

<section id="about" class="card">
    <h2>About</h2>
    <p>
        This website contains:
        <ul>
            <li>HTML structure</li>
            <li>CSS styling</li>
            <li>JavaScript interaction</li>
        </ul>
    </p>
</section>

<section id="contact" class="card">
    <h2>Contact</h2>
    <p>Email: example@email.com</p>
</section>

</div>

<footer>
    <p>© 2026 My Static Website</p>
</footer>

<script>
/* ===== JAVASCRIPT ===== */
function showMessage() {
    alert("🎉 JavaScript is working perfectly on GitHub Pages!");
}
</script>

</body>
</html>
