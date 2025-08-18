# aayushgauravrawat.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aayush Gaurav Rawat | Portfolio</title>
  <style>
    /* Reset + Fonts */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { background: #0d0d0d; color: #f0f0f0; line-height: 1.6; }

    /* Navbar */
    nav { display: flex; justify-content: space-between; align-items: center; padding: 20px 50px; background: #111; position: sticky; top: 0; z-index: 10; }
    nav a { color: #f0f0f0; text-decoration: none; margin: 0 15px; transition: 0.3s; }
    nav a:hover { color: #ff6600; }

    /* Hero Section */
    .hero { display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; height: 100vh; padding: 0 20px; }
    .hero h1 { font-size: 3rem; color: #ff6600; margin-bottom: 10px; }
    .hero p { max-width: 600px; font-size: 1.2rem; }

    /* Section */
    section { padding: 60px 50px; }
    h2 { font-size: 2rem; color: #ff6600; margin-bottom: 20px; }

    /* Projects */
    .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
    .card { background: #1a1a1a; padding: 20px; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.4); transition: transform 0.3s; }
    .card:hover { transform: translateY(-8px); }
    .card h3 { color: #ff6600; margin-bottom: 10px; }
    .card p { font-size: 0.95rem; }

    /* Contact */
    .contact a { color: #ff6600; text-decoration: none; margin-right: 15px; }
    .contact a:hover { text-decoration: underline; }

    /* Footer */
    footer { text-align: center; padding: 20px; background: #111; font-size: 0.9rem; }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <div><strong>Aayush Gaurav Rawat</strong></div>
    <div>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero" id="home">
    <h1>Hi, I'm Aayush 👋</h1>
    <p>Aspiring AI/ML Research Scientist | B.Tech CSE @ MIT Manipal | Builder of ideas like <strong>konkordia</strong>. Passionate about research, innovation, and impactful technology.</p>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm a Computer Science undergraduate at MIT Manipal with a strong interest in AI, Machine Learning, and building real-world impactful projects.
      Currently working on <strong>konkordia</strong>, a student-friendly social networking platform, and learning advanced computer science concepts(trying;).
    </p>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Konkordia</h3>
        <p>A web app to help students connect with peers of similar interests and hobbies. Built with Python, Flask(python's framework), and Firebase(google).</p>
        <a href="https://github.com/aayushgauravrawat/konkordia-project_1-" target="_blank">🔗 GitHub</a>
      </div>
      <div class="card">
        <h3>Netflix Dataset Analysis(discontinued at moment)</h3>
        <p>Analysing Netflix TV shows and movies dataset to uncover trends and insights using Python and data visualization.</p>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <p>Python, C, HTML&CSS(novice), Git/GitHub, Firebase, Flask</p>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact">
      <a href="aayush.g.rawat@gmail.com">📧 Email</a>
      <a href="https://www.linkedin.com/in/aayush-gaurav-rawat-a8a49933b/" target="_blank">💼 LinkedIn</a>
      <a href="https://github.com/aayushgauravrawat" target="_blank">💻 GitHub</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 Aayush Gaurav Rawat | Built with ❤️ and Black+Orange theme
  </footer>
</body>
</html>
