# Ashleena
Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ashleena Shop</title>
  {{content_for_header}}
  <link rel="stylesheet" href="/css/styles.css">
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background-color: blue; color: white; padding: 10px 20px; text-align: center; }
    header nav a { color: white; margin: 0 10px; text-decoration: none; }
    footer { background-color: red; color: white; text-align: center; padding: 10px 0; }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Ashleena Shop</h1>
    <nav>
      <a href="#categories">Categories</a>
      <a href="#login">Login</a>
      <a href="#register">Register</a>
    </nav>
  </header>
  {{content_for_layout}}
  <footer>
    <p>&copy; 2024 Ashleena Shop. All rights reserved.</p>
  </footer>
  <script src="/js/main.js"></script>
</body>
</html>
