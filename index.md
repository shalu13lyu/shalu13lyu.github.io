
---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, initial-scale=1">
  <title>Shahar | Academic Portfolio</title>
  <style>
    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f6fc;
      color: #25304a;
      line-height: 1.7;
    }

    nav {
      background: #111a30;
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    nav strong { color: white; font-size: 20px; }

    nav a {
      color: #c8c9f5;
      margin-left: 18px;
      text-decoration: none;
    }

    nav a:hover { color: white; }

    header {
      background: linear-gradient(135deg,
        #111a30, #46318c, #7560c9);
      color: white;
      text-align: center;
      padding: 95px 20px;
    }

    header h1 {
      font-size: clamp(36px, 6vw, 58px);
      margin: 0 0 12px;
    }

    header p {
      font-size: 20px;
      color: #e0dcff;
    }

    .button {
      display: inline-block;
      background: #8066e9;
      color: white;
      padding: 12px 24px;
      border-radius: 9px;
      text-decoration: none;
      margin: 10px 5px;
      font-weight: bold;
    }

    .button:hover { background: #6247cc; }

    .container {
      max-width: 1050px;
      margin: auto;
      padding: 55px 22px;
    }

    h2 {
      color: #302369;
      font-size: 30px;
      margin-bottom: 22px;
    }

    .grid {
      display: grid;
      grid-template-columns:
        repeat(auto-fit, minmax(240px, 1fr));
      gap: 22px;
    }

    .card {
      background: white;
      border-radius: 16px;
      padding: 28px;
      box-shadow: 0 6px 24px #18214a12;
      border: 1px solid #e9e7f5;
    }

    .card h3 {
      color: #6247bd;
      margin-top: 0;
    }

    .tag {
      display: inline-block;
      background: #eae5ff;
      color: #5039a1;
      border-radius: 20px;
      padding: 5px 13px;
      margin: 5px;
      font-size: 14px;
    }

    footer {
      background: #111a30;
      color: #cbd0e5;
      text-align: center;
      padding: 30px;
    }

    footer a { color: #bbaaff; }
  </style>
</head>

<body>

<nav>
  <strong>Shahar.</strong>
  <div>
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#python">Python</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<header>
  <h1>Hello, I'm Shahar 👋</h1>
  <p>Science | Research | Data Analysis</p>
  <p>Welcome to my academic portfolio</p>
  <a class="button" href="#about">Explore My Work</a>
  <a class="button"
     href="https://github.com/shalu13lyu">
    My GitHub ↗
  </a>
</header>

<main>
  <section class="container" id="about">
    <h2>✨ About Me</h2>
    <div class="card">
      <p>
        Hello! I'm Shahar, currently studying
        [your degree] at [your institution].
      </p>
      <p>
        My academic interests include scientific
        research, data analysis, and developing
        new computational skills.
      </p>
    </div>
  </section>

  <section class="container" id="research">
    <h2>🔬 Research & Academic Background</h2>
    <div class="grid">
      <div class="card">
        <h3>🎓 Education</h3>
        <p>[Your degree and university]</p>
        <p>[Your academic achievements]</p>
      </div>

      <div class="card">
        <h3>🧪 My Research</h3>
        <p>[Your lab or research group]</p>
        <p>[Brief description of your research]</p>
      </div>

      <div class="card">
        <h3>💡 Research Interests</h3>
        <span class="tag">[Interest 1]</span>
        <span class="tag">[Interest 2]</span>
        <span class="tag">[Interest 3]</span>
      </div>
    </div>
  </section>

  <section class="container" id="python">
    <h2>💻 My Python Learning Journey</h2>
    <div class="card">
      <h3>Python Course 2026</h3>
      <p>
        I am learning Python to improve my
        programming, data analysis, and
        scientific visualization skills.
      </p>
      <p>My goals include:</p>
      <ul>
        <li>Learn Python fundamentals</li>
        <li>Analyze and visualize data</li>
        <li>Automate research tasks</li>
        <li>Develop practical coding projects</li>
      </ul>
      <a class="button"
         href="https://github.com/Code-Maven/wis-python-course-2026-10">
        View Python Course ↗
      </a>
    </div>
  </section>

  <section class="container" id="contact">
    <h2>📬 Connect With Me</h2>
    <div class="card">
      <p>
        Explore my programming projects
        and academic work on GitHub.
      </p>
      <a class="button"
         href="https://github.com/shalu13lyu">
        Visit My GitHub ↗
      </a>
    </div>
  </section>
</main>

<footer>
  <p>© 2026 Shahar | Academic Portfolio</p>
  <p>
    Built with GitHub Pages & Jekyll
  </p>
</footer>

</body>
</html>

