
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Shahar | Membrane Protein Research</title>

<style>
* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: #fafaf8;
  color: #203247;
  line-height: 1.8;
}

nav {
  max-width: 1050px;
  margin: auto;
  padding: 28px 24px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 12px;
}

.logo {
  font-size: 23px;
  font-weight: bold;
  letter-spacing: 2px;
}

nav a {
  color: #526779;
  text-decoration: none;
  margin-left: 22px;
  font-size: 14px;
}

nav a:hover {
  color: #267b8c;
}

.hero {
  max-width: 1050px;
  margin: auto;
  padding: 105px 24px 115px;
}

.eyebrow {
  color: #267b8c;
  text-transform: uppercase;
  letter-spacing: 3px;
  font-size: 12px;
  font-weight: bold;
}

.hero h1 {
  font-size: clamp(48px, 8vw, 88px);
  line-height: 1.1;
  margin: 20px 0;
  letter-spacing: -2px;
}

.hero h2 {
  color: #587084;
  font-size: clamp(23px, 4vw, 35px);
  font-weight: normal;
  max-width: 750px;
  line-height: 1.4;
}

.hero p {
  color: #738394;
  font-size: 16px;
}

section {
  max-width: 1050px;
  margin: auto;
  padding: 75px 24px;
  border-top: 1px solid #e0e5e6;
}

.section-label {
  color: #267b8c;
  font-size: 12px;
  letter-spacing: 3px;
  font-weight: bold;
}

section h2 {
  font-size: clamp(29px, 5vw, 42px);
  margin: 12px 0 25px;
  line-height: 1.25;
}

section p {
  max-width: 750px;
  font-size: 17px;
  color: #536779;
}

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  margin-top: 35px;
}

.research-card {
  background: white;
  border: 1px solid #e4e9eb;
  border-radius: 12px;
  padding: 30px;
}

.research-card h3 {
  font-size: 23px;
  margin-top: 0;
}

.research-card p {
  font-size: 15px;
}

.number {
  color: #267b8c;
  font-size: 13px;
  font-weight: bold;
}

.python {
  background: #edf3f4;
  border-radius: 14px;
  padding: 35px;
  margin-top: 25px;
}

.python ul {
  color: #536779;
  padding-left: 22px;
}

.button {
  display: inline-block;
  background: #203f55;
  color: white;
  text-decoration: none;
  padding: 11px 22px;
  border-radius: 6px;
  margin: 12px 10px 0 0;
  font-size: 14px;
}

.button:hover {
  background: #267b8c;
}

footer {
  text-align: center;
  padding: 40px 20px;
  background: #203247;
  color: #dce5ec;
}

footer a {
  color: #a9dce5;
}

@media (max-width: 650px) {
  .hero {
    padding-top: 65px;
    padding-bottom: 75px;
  }

  .research-grid {
    grid-template-columns: 1fr;
  }

  nav a {
    margin-left: 10px;
  }
}
</style>
</head>

<body>

<nav>
  <div class="logo">SHAHAR.</div>
  <div>
    <a href="#about">About</a>
    <a href="#science">Research</a>
    <a href="#python">Python</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<header class="hero">
  <div class="eyebrow">Welcome to my website</div>

  <h1>Hi, I'm Shahar.</h1>

  <h2>
    Exploring the fascinating world
    of membrane proteins.
  </h2>

  <p>
    Electron Microscopy · Atomic Force Microscopy
    · Scientific Computing
  </p>
</header>

<section id="about">
  <div class="section-label">01 / ABOUT ME</div>

  <h2>Curiosity drives my research.</h2>

  <p>
    My research focuses on membrane proteins,
    using advanced microscopy techniques
    to explore their structure and properties.
  </p>

  <p>
    In our laboratory, we combine experimental
    approaches with computational tools to
    better understand biological systems.
  </p>
</section>

<section id="science">
  <div class="section-label">02 / THE SCIENCE</div>

  <h2>Looking closer at membrane proteins.</h2>

  <p>
    Membrane proteins are essential components
    of biological membranes. They participate
    in transport, signaling, and many other
    cellular processes.
  </p>

  <p>
    My work involves studying these proteins
    using complementary microscopy techniques.
  </p>

  <div class="research-grid">

    <div class="research-card">
      <div class="number">METHOD 01</div>
      <h3>Electron Microscopy</h3>
      <p>
        Electron microscopy (EM) enables
        the investigation of biological
        structures at the nanoscale.
      </p>
      <p>
        It provides valuable structural
        information about membrane proteins.
      </p>
    </div>

    <div class="research-card">
      <div class="number">METHOD 02</div>
      <h3>Atomic Force Microscopy</h3>
      <p>
        Atomic force microscopy (AFM)
        allows the examination of surfaces
        and molecular features at the nanoscale.
      </p>
      <p>
        It complements other structural
        techniques in membrane research.
      </p>
    </div>

  </div>
</section>

<section id="python">
  <div class="section-label">03 / LEARNING PYTHON</div>

  <h2>From microscopy to code.</h2>

  <p>
    Scientific research generates large
    amounts of experimental data.
    Programming can help us analyze,
    visualize, and interpret these results.
  </p>

  <div class="python">
    <h3>Why am I learning Python?</h3>

    <p>
      I am taking the Weizmann Python
      Course 2026 to develop programming
      skills that I can apply directly
      to our laboratory research.
    </p>

    <ul>
      <li>Analyze experimental datasets</li>
      <li>Process microscopy measurements</li>
      <li>Create scientific visualizations</li>
      <li>Automate data analysis workflows</li>
      <li>Develop computational research tools</li>
    </ul>

    <a class="button"
      href="https://github.com/Code-Maven/wis-python-course-2026-10">
      Python Course ↗
    </a>

    <a class="button"
      href="https://github.com/shalu13lyu">
      My GitHub ↗
    </a>
  </div>
</section>

<section id="contact">
  <div class="section-label">04 / CONNECT</div>

  <h2>Let's connect.</h2>

  <p>
    Interested in my research or
    programming projects?
    Explore my work on GitHub.
  </p>

  <a class="button"
    href="https://github.com/shalu13lyu">
    Visit GitHub ↗
  </a>
</section>

<footer>
  <p>Shahar · Membrane Protein Research</p>
  <p>© 2026 | Built with GitHub Pages</p>
</footer>

</body>
</html>
