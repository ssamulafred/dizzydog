<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Nova Studio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: #0f172a;
      color: white;
    }

    header {
      width: 100%;
      padding: 25px 80px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: fixed;
      top: 0;
      left: 0;
      background: rgba(15, 23, 42, 0.85);
      backdrop-filter: blur(10px);
      z-index: 1000;
    }

    header h1 {
      font-size: 26px;
      font-weight: 700;
      color: #38bdf8;
    }

    nav a {
      margin-left: 25px;
      text-decoration: none;
      color: white;
      font-weight: 500;
      transition: 0.3s;
    }

    nav a:hover {
      color: #38bdf8;
    }

    .hero {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 100px 80px;
      background: linear-gradient(to right, #0f172a, #1e293b);
    }

    .hero-content {
      max-width: 600px;
    }

    .hero-content h2 {
      font-size: 55px;
      line-height: 1.2;
      margin-bottom: 20px;
    }

    .hero-content p {
      font-size: 18px;
      opacity: 0.8;
      margin-bottom: 30px;
    }

    .btn {
      padding: 14px 28px;
      background: #38bdf8;
      border: none;
      color: black;
      font-size: 16px;
      font-weight: 600;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: white;
      transform: scale(1.05);
    }

    .hero-image img {
      width: 450px;
      border-radius: 20px;
      box-shadow: 0 0 40px rgba(56, 189, 248, 0.3);
    }

    section {
      padding: 80px;
      text-align: center;
    }

    section h3 {
      font-size: 36px;
      margin-bottom: 20px;
      color: #38bdf8;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 40px;
    }

    .card {
      background: #1e293b;
      padding: 30px;
      border-radius: 16px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 25px rgba(56, 189, 248, 0.3);
    }

    .card h4 {
      margin-bottom: 10px;
      font-size: 20px;
    }

    footer {
      padding: 30px;
      text-align: center;
      background: #0b1120;
      font-size: 14px;
      opacity: 0.7;
    }

    /* Responsive */
    @media (max-width: 900px) {
      .hero {
        flex-direction: column;
        text-align: center;
      }

      .hero-image img {
        margin-top: 40px;
        width: 90%;
      }

      header {
        padding: 20px 40px;
      }
    }
  </style>
</head>

<body>

  <!-- Navbar -->
  <header>
    <h1>Nova Studio</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <div class="hero">
    <div class="hero-content">
      <h2>Creative Studio for Modern Brands</h2>
      <p>
        We design stunning visuals, build powerful digital experiences,
        and help brands stand out in the world.
      </p>
      <button class="btn">Book a Session</button>
    </div>

    <div class="hero-image">
      <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f"
        alt="Studio Image">
    </div>
  </div>

  <!-- Services Section -->
  <section id="services">
    <h3>Our Services</h3>
    <p>Everything you need to launch your next creative project.</p>

    <div class="services">
      <div class="card">
        <h4>Brand Design</h4>
        <p>Logo, identity, and visual systems that look premium.</p>
      </div>

      <div class="card">
        <h4>Photography</h4>
        <p>Professional studio shoots for products and portraits.</p>
      </div>

      <div class="card">
        <h4>Web Experiences</h4>
        <p>Modern landing pages and websites that convert.</p>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <h3>About Nova Studio</h3>
    <p>
      Nova Studio is a creative agency built for dreamers, creators, and brands.
      We combine design, storytelling, and digital innovation.
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h3>Let’s Work Together</h3>
    <p>Email us at: <strong>hello@novastudio.com</strong></p>
    <button class="btn">Contact Now</button>
  </section>

  <!-- Footer -->
  <footer>
    © 2026 Nova Studio. All Rights Reserved.
  </footer>

</body>
</html>
