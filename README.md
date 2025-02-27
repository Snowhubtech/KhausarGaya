# KhausarGaya
Index: 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Based Technologies and Multimedia</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="container">
        <h1>Login</h1>
        <form action="main.html" method="get">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</body>
</html>


Main
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Page</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="main.html">Home</a></li> 
                <li><a href="main.html">Image</a></li> 
                <li><a href="main.html">Music</a></li> 
                <li><a href="main.html">Video</a></li>
                <li><a href="about.html">About/Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Welcome to the Main Page</h1>
        <p>This is the main content of the website.</p>
        <img src="images/example.jpg" alt="Example Image">  
    </main>
</body>
</html>
