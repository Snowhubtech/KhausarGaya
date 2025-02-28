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
            <label for="username">Username</label>
            <input type="text" id="username" placeholder="Enter Username" required>
            <label for="password">Password</label>
            <input type="password" id="password" placeholder="Enter Password" required>
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
                <h1>Khausar Nura Gaya</h1>
                        <h1>CMM/23/INF/01114</h1>
    </header>
    <section>
        <img src="WhatsApp Image 2025-02-27 at 4.55.38 AM.jpeg" alt="Profile Image">
        <p>Enjoy a personalized experience with multimedia elements.</p>
        <video controls width="600">
            <source src="WhatsApp Video 2025-02-27 at 4.57.03 AM.webm" type="video/webm">
            Your browser does not support the video tag.
        </video>
    </section>
    <nav>
        <a href="about.html">About/Contact</a>
    </nav>
    <section>
        <h2>Leave a Comment</h2>
        <form>
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Enter your email" required>
            <label for="comment">Comment</label>
            <textarea id="comment" placeholder="Write your comment here" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
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
        <p>I'm Khausar Nura Gaya, a 19-year-old makeup artist from Kano, Nigeria, who attended Khadija Memorial College for secondary education and is now studying at Bayero University. I have a passion for beauty, creativity, and self-expression, and I'm lovingly known as the last born in my family.</p>
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
