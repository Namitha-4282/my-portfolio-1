<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>My Portfolio</title>
  <style>
    :root {
      --primary: #6a11cb;
      --secondary: #2575fc;
      --text-dark: #222;
      --text-light: #fff;
      --bg-light: #f9f9f9;
      --accent: #ff4081;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--bg-light);
      color: var(--text-dark);
    }

    header {
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      color: var(--text-light);
      padding: 3rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    nav {
      background-color: #fff;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    nav a {
      display: inline-block;
      padding: 1rem 1.5rem;
      color: var(--primary);
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--accent);
    }

    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 2rem;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }

    section h2 {
      color: var(--primary);
      margin-top: 0;
    }

    ul {
      padding-left: 1.2rem;
    }

    footer {
      background: var(--primary);
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>KARNE NAMITHA</h1>
    <p>Web Developer | UI/UX Enthusiast | Tech Learner</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm a dedicated web developer passionate about creating fast, user-friendly web experiences. I specialize in
      building full-stack applications with clean code and beautiful design.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Portfolio Website:</strong> Built using HTML, CSS to showcase my skills and personal brand.</li>
      <li><strong>Gaming Leaderboard:</strong> Developed backend and frontend for a real-time leaderboard at a gaming startup.</li>
      <li><strong>Blog Platform:</strong> Created a Markdown-based content publishing system with user engagement features.</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: reddynamitha61@gmail.com</p>
    <p>LinkedIn: <a href="#" style="color: var(--accent); text-decoration: none;">linkedin.com/in/johndoe</a></p>
  </section>

  <footer>
    <p>&copy; 2025 John Doe. All rights reserved.</p>
  </footer>

</body>
</html>
