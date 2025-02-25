<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign In</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="logo">LOGO</div>
        <h1>Welcome to MyPlatform</h1>
        <p>Sign in</p>
        <form>
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Email" required>

            <label for="password">Password</label>
            <input type="password" id="password" placeholder="Password" required>

            <button type="submit">Sign in</button>
        </form>
        <div class="signin">
            Don’t have an account yet? <a href="sign up.html">Sign up</a>
        </div>
    </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="logo">LOGO</div>
        <h1>Welcome to MyPlatform</h1>
        <p>Sign up</p>
        <form>
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Email" required>

            <label for="password">Password</label>
            <input type="password" id="password" placeholder="Password" required>

            <button type="submit">Sign up</button>
        </form>
        <div class="signin">
            Already have an account? <a href="sign in.html">Sign in</a>
        </div>
    </div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f9f9f9;
}

.container {
    text-align: center;
    max-width: 400px;
    width: 100%;
    padding: 20px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.logo {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
}

h1 {
    font-size: 20px;
    margin-bottom: 10px;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    text-align: left;
    margin-bottom: 5px;
    font-size: 14px;
}

input[type="email"], input[type="password"] {
    padding: 10px;
    margin-bottom: 15px;
    font-size: 16px;
    border: 1px solid #ddd;
    border-radius: 4px;
}

button {
    padding: 10px;
    font-size: 16px;
    color: #fff;
    background-color: #000;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #333;
}

.signin {
    margin-top: 10px;
    font-size: 14px;
}

.signin a {
    color: #007bff;
    text-decoration: none;
}

.signin a:hover {
    text-decoration: underline;
}

body{
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f9f9f9;
}

.container {
    text-align: center;
    max-width: 400px;
    width: 100%;
    padding: 20px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.logo {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
    text-align: center;
}

h1 {
    font-size: 20px;
    margin-bottom: 10px;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    text-align: left;
    margin-bottom: 5px;
    font-size: 14px;
}

input[type="email"], input[type="password"] {
    padding: 10px;
    margin-bottom: 15px;
    font-size: 16px;
    border: 1px solid #ddd;
    border-radius: 4px;
}

button {
    padding: 10px;
    font-size: 16px;
    color: #fff;
    background-color: #000;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #333;
}

.signin {
    margin-top: 10px;
    font-size: 14px;
}

.signin a {
    color: #007bff;
    text-decoration: none;
}

.signin a:hover {
    text-decoration: underline;
}# pablo
