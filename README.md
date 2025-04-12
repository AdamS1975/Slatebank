<!-- index.html (Dashboard) --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Slatebank Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
  <script src="js/main.js" defer></script>
</head>
<body class="dark">
  <div class="sidebar">
    <h2>Slatebank</h2>
    <ul>
      <li><a href="index.html">Dashboard</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </div>
  <div class="main-content">
    <h1>Welcome, Adam Slagle</h1>
    <p class="balance">Account Balance: <strong>$120,034,726.66</strong></p>
    <p>Email: adamslagle94@gmail.com</p>
  </div>
</body>
</html><!-- about.html --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About - Slatebank</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body class="dark">
  <div class="sidebar">
    <h2>Slatebank</h2>
    <ul>
      <li><a href="index.html">Dashboard</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </div>
  <div class="main-content">
    <h1>About Slatebank</h1>
    <p>Slatebank is a modern digital banking platform offering a sleek user experience, high security, and quick access to your financial data.</p>
  </div>
</body>
</html><!-- contact.html --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Slatebank</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body class="dark">
  <div class="sidebar">
    <h2>Slatebank</h2>
    <ul>
      <li><a href="index.html">Dashboard</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </div>
  <div class="main-content">
    <h1>Contact Us</h1>
    <p>Email: support@slatebank.com</p>
    <p>Phone: +1 (800) 123-4567</p>
  </div>
</body>
</html>/* css/style.css */ body.dark { background-color: #121212; color: #f0f0f0; font-family: Arial, sans-serif; margin: 0; display: flex; }

.sidebar { width: 200px; background-color: #1e1e1e; padding: 20px; height: 100vh; }

.sidebar h2 { color: #4fc3f7; }

.sidebar ul { list-style: none; padding: 0; }

.sidebar ul li a { color: #ccc; text-decoration: none; display: block; padding: 10px 0; }

.sidebar ul li a:hover { color: #4fc3f7; }

.main-content { padding: 40px; flex: 1; }

.balance { font-size: 1.5em; color: #81c784; }

/* js/main.js */ document.addEventListener("DOMContentLoaded", function () { console.log("Slatebank loaded for Adam Slagle"); });


