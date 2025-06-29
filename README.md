# Roblox
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>GameVerse Login</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="login-container">
    <h1>GameVerse</h1>
    <p class="subtitle">Log in to start your adventure</p>
    <form action="#" method="POST">
      <input type="text" name="username" placeholder="Username" required>
      <input type="password" name="password" placeholder="Password" required>
      <button type="submit">Log In</button>
    </form>
    <p class="signup">Don’t have an account? <a href="#">Sign up</a></p>
  </div>
</body>
</html>
* {
  box-sizing: border-box;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
  margin: 0;
  padding: 0;
  background-color: #e7e7e7;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.login-container {
  background-color: #fff;
  padding: 40px 30px;
  border-radius: 10px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  text-align: center;
  width: 100%;
  max-width: 350px;
}

.login-container h1 {
  font-size: 32px;
  color: #d42626;
  margin-bottom: 10px;
}

.subtitle {
  color: #666;
  margin-bottom: 30px;
}

form input {
  width: 100%;
  padding: 12px 10px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
  border-radius: 6px;
}

form button {
  width: 100%;
  padding: 12px;
  background-color: #d42626;
  border: none;
  color: #fff;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
}

form button:hover {
  background-color: #b31f1f;
}

.signup {
  margin-top: 20px;
  font-size: 14px;
}

.signup a {
  color: #d42626;
  text-decoration: none;
}
