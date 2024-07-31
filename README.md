


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Movie Streamer</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <h1>My Movie Streamer</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#browse">Browse</a></li>
                <li><a href="#account">Account</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to My Movie Streamer</h2>
        <!-- Featured content here -->
    </section>

    <section id="browse">
        <h2>Browse Movies</h2>
        <!-- Movie grid here -->
    </section>

    <section id="account">
        <h2>Your Account</h2>
        <!-- User account details here -->
    </section>

    <footer>
        <p>&copy; 2024 My Movie Streamer. All rights reserved.</p>
    </footer>
</body>
</html>
```

**3.2. **CSS (styles.css)**

```css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #fff;
    background-color: #2a2a2a;
}

header {
    background-color: #004d00;
    padding: 10px 0;
    color: #fff;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

nav h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
}

footer {
    background-color: #004d00;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
```

