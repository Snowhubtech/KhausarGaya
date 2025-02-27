# KhausarGaya
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personalized Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h2>Login</h2>
        <form id="loginForm">
            <input type="text" id="username" placeholder="Username" required>
            <input type="password" id="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
    <script>
        document.getElementById('loginForm').addEventListener('submit', function(event) {
            event.preventDefault();
            window.location.href = 'main.html';
        });
    </script>
</body>
</html>
<!-- Main Page (main.html) -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <section>
        <img src="WhatsApp Image 2025-02-27 at 4.55.38 AM.jpeg" alt="Profile Image">
        <p>Enjoy a personalized experience with multimedia elements.</p>
    </section>
    <nav>
        <a href="about.html">About/Contact</a>
    </nav>
</body>
</html>

<!-- About/Contact Page (about.html) -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About & Contact</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Me</h1>
    </header>
    <section>
        <p>This is a brief description about me.</p>
    </section>
    <h2>Contact</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" required></textarea>
        <button type="submit">Send</button>
    </form>
</body>
</html>

<!-- CSS File (styles.css) -->
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f4f4f4;
}
.container {
    width: 300px;
    margin: auto;
    padding: 20px;
    background: white;
    border-radius: 10px;
}
input, button, textarea {
    display: block;
    width: 100%;
    margin: 10px 0;
    padding: 10px;
}
button {
    background-color: #007BFF;
    color: white;
    border: none;
}
button:hover {
    background-color: #0056b3;
}
nav a {
    display: block;
    margin: 10px;
}
