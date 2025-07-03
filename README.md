<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rig Bist | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #0f172a;
      color: #f8fafc;
      scroll-behavior: smooth;
    }
    nav {
      background-color: #1e293b;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav ul {
      display: flex;
      list-style: none;
      gap: 2rem;
    }
    nav a {
      color: #f8fafc;
      text-decoration: none;
      transition: 0.3s;
    }
    nav a:hover {
      color: #38bdf8;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      background: linear-gradient(to right, #0f172a, #1e293b);
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
    }
    .hero p {
      font-size: 1.25rem;
      color: #94a3b8;
    }
    .btn {
      margin-top: 1.5rem;
      padding: 0.75rem 1.5rem;
      background-color: #38bdf8;
      border: none;
      border-radius: 8px;
      color: #0f172a;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }
    .btn:hover {
      background-color: #0ea5e9;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #38bdf8;
    }
    .project-card {
      background-color: #1e293b;
      padding: 1.5rem;
      margin: 1rem 0;
      border-radius: 12px;
      transition: transform 0.3s;
    }
    .project-card:hover {
      transform: scale(1.02);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    input, textarea, button {
      padding: 0.75rem;
      border-radius: 6px;
      border: none;
    }
    input, textarea {
      background-color: #334155;
      color: #f8fafc;
    }
    button {
      background-color: #38bdf8;
      color: #0f172a;
      font-weight: bold;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #1e293b;
      color: #94a3b8;
    }
    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
        gap: 1rem;
      }
      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <nav>
    <div><strong>Rig Bist</strong></div>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section class="hero" id="home">
    <h1>Hi, I'm Rig Bist</h1>
    <p>Frontend Developer & Java Enthusiast</p>
    <a href="#contact" class="btn">Contact Me</a>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate frontend developer, currently pursuing BCA at JIIT. I enjoy crafting beautiful and responsive websites and continuously learning new technologies to improve user experiences.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Image Gallery</h3>
      <p>A responsive gallery with filters and lightbox view.</p>
    </div>
    <div class="project-card">
      <h3>Music Player</h3>
      <p>JavaScript-powered audio player with playlist and controls.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Rig Bist | Designed by Rig bist</p>
  </footer>
</body>
</html>
