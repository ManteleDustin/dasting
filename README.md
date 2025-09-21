<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="A modern, responsive personal portfolio website." />
  <title>John Doe | Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <script defer src="script.js"></script>
</head>
<body>

  <header class="header" role="banner">
    <nav class="navbar" aria-label="Main navigation">
      <a href="#" class="logo">JohnDoe</a>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
        <li>
          <button class="dark-toggle" aria-label="Toggle Dark Mode">🌓</button>
        </li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="hero" class="hero-section">
      <h1>Hello, I'm <span class="highlight">John Doe</span></h1>
      <p>I'm a web developer passionate about creating modern websites.</p>
      <a href="#projects" class="btn">View Projects</a>
    </section>

    <section id="about" class="about-section">
      <h2>About Me</h2>
      <p>I specialize in front-end development with a love for clean code and performance.</p>
      <img src="https://via.placeholder.com/300x200" alt="John working on code" />
    </section>

    <section id="projects" class="projects-section">
      <h2>Projects</h2>
      <div class="projects-grid">
        <article class="project-card">
          <h3>Portfolio Website</h3>
          <p>A sleek personal portfolio built with HTML, CSS, and JS.</p>
        </article>
        <article class="project-card">
          <h3>Weather App</h3>
          <p>Displays live weather data using a public API.</p>
        </article>
      </div>
    </section>

    <section id="contact" class="contact-section">
      <h2>Contact</h2>
      <form aria-label="Contact form">
        <label>
          Name:
          <input type="text" required />
        </label>
        <label>
          Email:
          <input type="email" required />
        </label>
        <label>
          Message:
          <textarea required></textarea>
        </label>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer class="footer" role="contentinfo">
    <p>&copy; 2025 John Doe. All rights reserved.</p>
  </footer>
</body>
</html>
