<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bhavani | Frontend Developer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #ffe8ec, #e0f7fa);
      color: #1e293b;
    }

    header {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      padding: 2rem;
      background: linear-gradient(135deg, #fbd786, #f7797d);
      color: #fff;
    }

    header h1 {
      font-size: 3.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.5rem;
      margin-bottom: 2rem;
    }

    .cta {
      background: #ffffff;
      color: #f7797d;
      padding: 1rem 2rem;
      font-size: 1.1rem;
      font-weight: bold;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      box-shadow: 0 10px 25px rgba(255, 255, 255, 0.3);
      transition: transform 0.3s ease, background 0.3s ease;
    }

    .cta:hover {
      transform: scale(1.05);
      background: #ffe3e3;
    }

    section {
      padding: 4rem 2rem;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      text-align: center;
      color: #f97316;
    }

    .project {
      margin-bottom: 2rem;
      background: linear-gradient(135deg, #e0c3fc, #8ec5fc);
      padding: 1.5rem;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
      color: #1e293b;
    }

    .project img {
      width: 100%;
      border-radius: 10px;
      margin-top: 1rem;
    }

    .project a {
      color: #1d4ed8;
      text-decoration: none;
      margin-right: 1rem;
    }

    .contact-form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      background: #fff8f0;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
    }

    .contact-form input,
    .contact-form textarea {
      padding: 0.9rem;
      border-radius: 8px;
      border: 2px solid #fcd34d;
      font-size: 1rem;
    }

    .contact-form button {
      background: #38bdf8;
      color: white;
      padding: 1rem;
      border: none;
      border-radius: 8px;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s;
    }

    .contact-form button:hover {
      background: #0ea5e9;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: linear-gradient(135deg, #ede7f6, #e3f2fd);
      color: #334155;
    }

    footer a {
      margin: 0 10px;
      color: #3b82f6;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi, I’m Bhavani – Frontend Developer</h1>
    <p>Crafting engaging, responsive web experiences with clean code and vibrant design.</p>
    <button class="cta" onclick="document.getElementById('projects').scrollIntoView({ behavior: 'smooth' })">View Projects</button>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a passionate frontend developer with a love for colorful, interactive, and accessible web design. I specialize in HTML, CSS, and JavaScript, and enjoy building vibrant and responsive websites that leave an impression. Always eager to explore new tech and turn ideas into reality.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Weather App</h3>
      <p>A dynamic weather forecasting app built with JavaScript and OpenWeather API. Features include animated icons, responsive layout, and dark/light mode toggle.</p>
      <img src="https://via.placeholder.com/800x400" alt="Weather App Screenshot">
      <p><a href="#">Live Demo</a> | <a href="#">GitHub Code</a></p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Bhavani. All rights reserved.</p>
    <p><a href="#about">About</a> | <a href="#projects">Projects</a> | <a href="#contact">Contact</a></p>
  </footer>
</body>
</html>
