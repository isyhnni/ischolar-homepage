<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>iScholar Library</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body, html {
      font-family: 'Poppins', sans-serif;
      height: 100%;
      color: #333;
    }

    body {
      background: url('https://images.unsplash.com/photo-1587614382346-4ec70e388b31?auto=format&fit=crop&w=1950&q=80') no-repeat center center fixed;
      background-size: cover;
    }

    header {
      background-color: rgba(255, 255, 255, 0.95);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    header h1 {
      font-size: 1.8rem;
      color: #009688;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav a {
      text-decoration: none;
      color: #009688;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ff5722;
    }

    .hero {
      text-align: center;
      padding: 120px 20px 60px;
      background-color: rgba(255, 255, 255, 0.8);
      margin: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    .hero h2 {
      font-size: 3rem;
      color: #ff5722;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 1.3rem;
      margin-bottom: 30px;
      color: #555;
    }

    .btn {
      background-color: #009688;
      color: white;
      padding: 14px 30px;
      font-size: 1rem;
      font-weight: bold;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .btn:hover {
      background-color: #00796b;
    }

    .social {
      margin-top: 40px;
      display: flex;
      justify-content: center;
      gap: 25px;
    }

    .social img {
      width: 40px;
      height: 40px;
      transition: transform 0.3s ease;
    }

    .social img:hover {
      transform: scale(1.2);
    }

    footer {
      background-color: #f5f5f5;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #666;
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <header>
    <h1>iScholar Library</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Catalogue</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Digital Library</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to iScholar Library</h2>
    <p>Your vibrant hub for discovery, learning, and innovation!</p>
    <button class="btn">Explore Catalogue</button>

    <div class="social">
      <a href="https://facebook.com" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/145/145802.png" alt="Facebook" /></a>
      <a href="https://instagram.com" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" /></a>
      <a href="https://youtube.com" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/145/145807.png" alt="YouTube" /></a>
    </div>
  </section>

  <footer>
    &copy; 2025 iScholar Library | Bright minds, bright futures 🌟
  </footer>

</body>
</html>
