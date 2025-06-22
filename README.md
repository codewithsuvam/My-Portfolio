# My-Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Suvam Shaw | Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #fdfdfd;
      color: #222;
    }
    header {
      background: #1e1e2f;
      color: white;
      padding: 30px 0;
      text-align: center;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      padding: 0;
      margin: 20px 0 0 0;
    }
    nav ul li {
      margin: 0 20px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: 600;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #1e1e2f;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .project {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
    }
    footer {
      background: #1e1e2f;
      color: white;
      text-align: center;
      padding: 25px 0;
      margin-top: 40px;
    }
    button {
      background-color: #007acc;
      color: white;
      border: none;
      padding: 10px 18px;
      cursor: pointer;
      border-radius: 5px;
      margin-top: 10px;
    }
    a {
      color: #007acc;
    }
  </style>
</head>
<body>
  <header>
    <h1>I'm Suvam Shaw</h1>
    <p>Frontend Web Developer | AI Engineer (Aspiring) | Software Developer (Aspiring)</p>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Suvam Shaw, a B.Tech student graduating from KIIT University in 2028. I'm deeply interested in frontend web development, and passionate about becoming a skilled AI Engineer and Software Developer. I enjoy solving problems using Python, C, C++, and Java, and love turning ideas into interactive and useful applications.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Simple Calculator</h3>
        <p>A functional web calculator built using HTML, CSS, and JavaScript.</p>
        <button onclick="alert('Demo coming soon!')">View Demo</button>
      </div>
      <div class="project">
        <h3>Portfolio Website</h3>
        <p>This personal portfolio site to showcase my skills and experience.</p>
        <button onclick="alert('You are here!')">Visit Site</button>
      </div>
      <div class="project">
        <h3>To-Do App</h3>
        <p>A task manager to add, delete and complete tasks using local storage.</p>
        <button onclick="alert('GitHub repo coming soon')">GitHub</button>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5, CSS3, JavaScript</li>
      <li>Frontend Web Development</li>
      <li>Python Programming</li>
      <li>C, C++, Java</li>
      <li>AI Concepts (Beginner Level)</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📧 Email: <a href="mailto:suvshaw22@gmail.com">suvshaw22@gmail.com</a></p>
    <p>📍 Location: India</p>
  </section>

  <footer>
    <p>&copy; 2025 Suvam Shaw. Made with ❤️ using HTML, CSS & JS.</p>
  </footer>

  <script>
    // Log navigation
    document.querySelectorAll('nav a').forEach(link => {
      link.addEventListener('click', () => {
        console.log('Navigating to section:', link.getAttribute('href'));
      });
    });
  </script>
</body>
</html>
