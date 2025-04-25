<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Coffee Galore</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background-color: #f9f6f2;
      color: #3e2a1a;
    }
    header {
      background-color: #4b2e2e;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header img {
      height: 80px;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #3b1f1f;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: 700;
    }
    section {
      padding: 3rem 2rem;
      max-width: 800px;
      margin: 0 auto;
    }
    .menu-item {
      border-bottom: 1px solid #ddd;
      padding: 1rem 0;
    }
    footer {
      background-color: #4b2e2e;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.jpg" alt="Coffee Galore Logo" />
    <h1>Welcome to Coffee Galore</h1>
    <p>Your daily dose of chocolatey joy</p>
  </header>

  <nav>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-item">
      <strong>Coffee</strong><br />
      Freshly brewed coffee, served hot or iced
    </div>
    <div class="menu-item">
      <strong>Tea</strong><br />
      A variety of herbal and black teas
    </div>
    <div class="menu-item">
      <strong>Donuts</strong><br />
      Soft, sweet, and glazed to perfection
    </div>
    <div class="menu-item">
      <strong>Chocolate Cake</strong><br />
      Rich and moist chocolate cake slices
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>At Coffee Galore, we believe in the power of a great cup of coffee and a slice of cake to brighten your day. Whether you're here for a quick pick-me-up or a cozy sit-down, our team is here to serve you with a smile.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> +254 707 345 665</p>
    <p><strong>Hours:</strong> 9:00 AM – 6:00 PM</p>
    <p><strong>Email:</strong> info@classicdelightke.com</p>
    <!-- Optional map embed or contact form can go here -->
  </section>

  <footer>
    &copy; 2025 Coffee Galore. All rights reserved.
  </footer>
</body>
</html>
