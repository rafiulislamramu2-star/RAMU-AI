<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>RAMU Web Design & Digital Services</title>

  <meta name="description"
        content="RAMU Web Design & Digital Services provides professional website design, web development and digital services.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #08111f;
      color: #ffffff;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    .container {
      width: 92%;
      max-width: 1100px;
      margin: auto;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(8, 17, 31, 0.95);
      border-bottom: 1px solid #233047;
    }

    nav {
      height: 70px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
    }

    .logo span {
      color: #8b5cf6;
    }

    nav ul {
      display: flex;
      gap: 20px;
      list-style: none;
    }

    nav a {
      color: #cbd5e1;
    }

    nav a:hover {
      color: white;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      align-items: center;
      background:
        radial-gradient(circle at 80% 20%, #5134a955, transparent 35%),
        radial-gradient(circle at 10% 80%, #008cff33, transparent 30%);
    }

    .badge {
      display: inline-block;
      padding: 8px 14px;
      border: 1px solid #8b5cf6;
      border-radius: 30px;
      color: #c4b5fd;
      margin-bottom: 20px;
      font-size: 14px;
    }

    h1 {
      font-size: clamp(40px, 7vw, 70px);
      line-height: 1.05;
      max-width: 800px;
    }

    h1 span {
      color: #8b5cf6;
    }

    .hero p {
      color: #aab8ca;
      max-width: 700px;
      font-size: 18px;
      margin: 22px 0 30px;
    }

    .buttons {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      padding: 13px 22px;
      border-radius: 10px;
      font-weight: bold;
    }

    .primary {
      background: linear-gradient(90deg, #8b5cf6, #0284c7);
    }

    .secondary {
      background: #172338;
      border: 1px solid #30405a;
    }

    section {
      padding: 75px 0;
    }

    .title {
      text-align: center;
      margin-bottom: 40px;
    }

    .title h2 {
      font-size: 35px;
    }

    .title p {
      color: #94a3b8;
      margin-top: 8px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .card {
      padding: 28px;
      background: #101c2e;
      border: 1px solid #26364e;
      border-radius: 18px;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: #8b5cf6;
    }

    .icon {
      font-size: 35px;
      margin-bottom: 12px;
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .card p {
      color: #9fb0c5;
    }

    .about {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 25px;
    }

    .box {
      background: #0e1a2b;
      border: 1px solid #26364e;
      padding: 30px;
      border-radius: 18px;
    }

    .box p {
      color: #aab8ca;
      margin-top: 10px;
    }

    .contact {
      text-align: center;
      background: linear-gradient(135deg, #8b5cf633, #0284c733);
      border: 1px solid #6852b866;
      border-radius: 22px;
      padding: 50px 20px;
    }

    .contact p {
      color: #b9c6d8;
      margin: 12px auto 25px;
    }

    footer {
      text-align: center;
      padding: 30px 0;
      border-top: 1px solid #233047;
      color: #7f91a8;
    }

    @media (max-width: 750px) {

      nav ul {
        display: none;
      }

      .services,
      .about {
        grid-template-columns: 1fr;
      }

      .hero {
        min-height: 75vh;
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <div class="container">
      <nav>

        <a href="#home" class="logo">
          RAMU<span>.</span>
        </a>

        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>

      </nav>
    </div>
  </header>


  <!-- HERO -->
  <section class="hero" id="home">
    <div class="container">

      <div class="badge">
        Web Design • Development • Digital Services
      </div>

      <h1>
        Modern Websites for
        <span>Growing Businesses.</span>
      </h1>

      <p>
        RAMU Web Design & Digital Services provides
        clean, responsive and professional web solutions
        for businesses, entrepreneurs and individuals.
      </p>

      <div class="buttons">

        <a href="#contact" class="btn primary">
          Get Started
        </a>

        <a href="#services" class="btn secondary">
          Our Services
        </a>

      </div>

    </div>
  </section>


  <!-- SERVICES -->
  <section id="services">

    <div class="container">

      <div class="title">
        <h2>Our Services</h2>
        <p>Professional digital solutions for your business.</p>
      </div>

      <div class="services">

        <div class="card">

          <div class="icon">🌐</div>

          <h3>Website Design</h3>

          <p>
            Professional and responsive websites
            for businesses, portfolios and personal brands.
          </p>

        </div>


        <div class="card">

          <div class="icon">💻</div>

          <h3>Web Development</h3>

          <p>
            Modern HTML, CSS and JavaScript
            websites with mobile-friendly interfaces.
          </p>

        </div>


        <div class="card">

          <div class="icon">📈</div>

          <h3>Digital Services</h3>

          <p>
            Website updates, online presence
            and digital support for small businesses.
          </p>

        </div>

      </div>

    </div>

  </section>


  <!-- ABOUT -->
  <section id="about">

    <div class="container">

      <div class="title">
        <h2>About RAMU</h2>
        <p>Simple. Professional. Customer-focused.</p>
      </div>

      <div class="about">

        <div class="box">

          <h3>What We Do</h3>

          <p>
            RAMU Web Design & Digital Services focuses
            on creating responsive and professional
            websites for businesses and individuals.
          </p>

        </div>


        <div class="box">

          <h3>Why Choose RAMU?</h3>

          <p>
            Mobile-first design, clean code,
            practical solutions and clear communication
            with clients.
          </p>

        </div>

      </div>

    </div>

  </section>


  <!-- CONTACT -->
  <section id="contact">

    <div class="container">

      <div class="contact">

        <h2>Let's Work Together</h2>

        <p>
          Have a project in mind?
          Contact RAMU Web Design & Digital Services.
        </p>

        <!-- CHANGE THIS EMAIL TO YOUR REAL EMAIL -->
        <a
          href="mailto:YOUR-EMAIL@example.com"
          class="btn primary">
          Contact Us
        </a>

      </div>

    </div>

  </section>


  <!-- FOOTER -->
  <footer>

    <div class="container">

      © 2026 RAMU Web Design & Digital Services.
      All Rights Reserved.

    </div>

  </footer>


</body>
</html>