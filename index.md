
---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Shahar | Membrane Protein Research</title>

<style>
* { box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f3f8f7;
  color: #263b3d;
  line-height: 1.7;
}

nav {
  background: #103c42;
  padding: 20px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 15px;
}

.logo {
  color: white;
  font-size: 20px;
  font-weight: bold;
}

nav a {
  color: #d1e9e5;
  text-decoration: none;
  margin-left: 18px;
}

nav a:hover { color: #71e2cd; }

.hero {
  background: linear-gradient(135deg, #103c42, #176b68);
  color: white;
  padding: 95px 8%;
  text-align: center;
}

.hero h1 {
  font-size: clamp(34px, 6vw, 58px);
  margin: 0 0 20px;
  line-height: 1.2;
}

.hero p {
  max-width: 760px;
  margin: 15px auto;
  color: #d2eae5;
  font-size: 19px;
}

.label {
  color: #90ead9;
  letter-spacing: 3px;
  font-size: 13px;
  text-transform: uppercase;
}

.button {
  display: inline-block;
  background: #12a58f;
  color: white;
  text-decoration: none;
  padding: 12px 25px;
  border-radius: 7px;
  margin: 12px 5px;
  font-weight: bold;
}

.button:hover { background: #087e70; }

.container {
  max-width: 1100px;
  margin: auto;
  padding: 65px 22px;
}

h2 {
  color: #125b59;
  font-size: 32px;
  margin-bottom: 18px;
}

.subtitle {
  color: #647b7d;
  margin-bottom: 28px;
}

.grid {
  display: grid;
  grid-template-columns:
    repeat(auto-fit, minmax(250px, 1fr));
  gap: 24px;
}

.card {
  background: white;
  border-radius: 12px;
  padding: 28px;
  border: 1px solid #dcebe7;
  box-shadow: 0 5px 18px #123e3e0c;
}

.card h3 {
  color: #11796f;
  margin-top: 0;
}

.tag {
  display: inline-block;
  padding: 7px 13px;
  margin: 5px;
  background: #dcefeb;
  color: #17665f;
  border-radius: 20px;
  font-size: 14px;
}

.highlight {
  background: #e1f1ed;
  border-left: 5px solid #16a28c;
  padding: 25px;
  border-radius: 8px;
}

footer {
  background: #103c42;
  color: #d2e6e2;
  text-align: center;
  padding: 35px;
}

footer a { color: #9ee9d9; }

@media (max-width: 600px) {
  nav a { margin: 0 10px 0 0; }
  .hero { padding: 65px 20px; }
}
</style>
</head>

<body>

<nav>
  <div class="logo">SHAHAR | RESEARCH</div>
  <div>
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#methods">Methods</a>
    <a href="#python">Python</a>
  </div>
</nav>

<header class="hero">
  <p class="label">Membrane Protein Research</p>

  <h1>Exploring Membrane Proteins<br>
      at the Nanoscale</h1>

  <p>
    Investigating membrane proteins using
    Electron Microscopy (EM) and
    Atomic Force Microscopy (AFM).
  </p>

  <p>
    Connecting experimental imaging
    with computational data analysis.
  </p>

  <a class="button" href="#research">
    Explore My Research
  </a>
</header>

<main>

<section class="container" id="about">
  <h2>About Me</h2>

  <div class="card">
    <p>
      Hello! I'm Shahar, and my research
      focuses on membrane proteins.
    </p>

    <p>
      In our laboratory, we use microscopy
      techniques to investigate membrane
      proteins and their structural properties.
    </p>

    <p>
      I am also developing programming
      skills to support our research
      and analyze experimental data.
    </p>
  </div>
</section>

<section class="container" id="research">
  <h2>My Research</h2>

  <p class="subtitle">
    Understanding biological membranes
    through advanced imaging methods.
  </p>

  <div class="highlight">
    <h3>Why Membrane Proteins?</h3>
    <p>
      Membrane proteins play essential roles
      in cellular communication, transport,
      and many biological processes.
    </p>

    <p>
      Studying their structures and
      properties can help us understand
      how they function in biological systems.
    </p>
  </div>
</section>

<section class="container" id="methods">
  <h2>Research Techniques</h2>

  <div class="grid">

    <div class="card">
      <h3>Electron Microscopy (EM)</h3>
      <p>
        Electron microscopy is a powerful
        technique for studying biological
        structures at very small scales.
      </p>
      <p>
        We use EM as part of our research
        into membrane proteins.
      </p>
    </div>

    <div class="card">
      <h3>Atomic Force Microscopy (AFM)</h3>
      <p>
        AFM provides nanoscale information
        about surfaces and molecular
        structures.
      </p>
      <p>
        It allows us to investigate
        membrane-associated systems.
      </p>
    </div>

    <div class="card">
      <h3>Computational Analysis</h3>
      <p>
        Programming helps us process,
        analyze, and visualize
        experimental measurements.
      </p>
      <p>
        I am learning Python to develop
        these skills for research.
      </p>
    </div>

  </div>
</section>

<section class="container" id="python">
  <h2>Python for Scientific Research</h2>

  <div class="card">
    <h3>My Python Learning Journey</h3>

    <p>
      I am participating in the
      Weizmann Python Course 2026.
    </p>

    <p>
      My goal is to use programming
      to support experimental research
      in our laboratory.
    </p>

    <h3>My Learning Goals</h3>

    <ul>
      <li>Learn Python programming fundamentals</li>
      <li>Analyze microscopy datasets</li>
      <li>Visualize experimental measurements</li>
      <li>Automate repetitive analysis tasks</li>
      <li>Develop tools for research workflows</li>
    </ul>

    <div>
      <span class="tag">Python</span>
      <span class="tag">Microscopy</span>
      <span class="tag">Data Analysis</span>
      <span class="tag">Scientific Computing</span>
    </div>

    <p>
      <a class="button"
        href="https://github.com/Code-Maven/wis-python-course-2026-10">
        Python Course
      </a>

      <a class="button"
        href="https://github.com/shalu13lyu">
        My GitHub
      </a>
    </p>
  </div>
</section>

</main>

<footer>
  <p>Shahar | Membrane Protein Research</p>
  <p>
    Electron Microscopy · Atomic Force Microscopy
    · Python
  </p>
  <p>
    <a href="https://github.com/shalu13lyu">
      GitHub Profile
    </a>
  </p>
  <p>© 2026 Shahar</p>
</footer>

</body>
</html>
