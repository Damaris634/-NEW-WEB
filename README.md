<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MULANGO GIRLS High School</title>
  <style>
    :root {
      --primary-green: #2e7d32;
      --accent-green: #66bb6a;
      --background: #f0f9f1;
      --text-dark: #1b1b1b;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--background);
      color: var(--text-dark);
    }

    header {
      background-color: var(--primary-green);
      color: white;
      padding: 1.5rem;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: var(--accent-green);
      padding: 1rem 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 2rem;
    }

    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background-color: white;
    }

    .gallery {
      background-image: url('gallery_bg.jpg');
      background-size: cover;
      background-position: center;
      padding: 2rem;
    }

    .gallery img {
      width: 100%;
      max-width: 300px;
      margin: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .contact-form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: auto;
    }

    .contact-form input,
    .contact-form textarea {
      margin: 0.5rem 0;
      padding: 0.75rem;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    footer {
      background-color: var(--primary-green);
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>MULANGO GIRLS High School</h1>
    <p>"Empowering Girls, Building the Future"</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#academics">Academics</a>
    <a href="#cocurricular">Co-curricular</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>MULANGO GIRLS High School is a premier institution dedicated to academic excellence and holistic development of young women in Kenya.</p>
  </section>

  <section id="academics">
    <h2>Academics</h2>
    <p>We offer a rigorous academic curriculum focused on preparing students for KCSE and beyond.</p>
  </section>

  <section id="cocurricular">
    <h2>Co-curricular Activities</h2>
    <p>Our students thrive in clubs, sports, music, drama, and leadership activities.</p>
  </section>

  <section id="gallery" class="gallery">
    <h2>Gallery</h2>
    <img src="https://via.placeholder.com/300x200" alt="School Life" />
    <img src="https://via.placeholder.com/300x200" alt="Events" />
    <img src="https://images.unsplash.com/photo-1571260899304-425eee4c7efc?auto=format&fit=crop&w=800&q=80" alt="Students at Assembly" />
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="5"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 MULANGO GIRLS High School. All rights reserved.</p>
  </footer>
</body>
</html>


# -NEW-WEB
