
<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Shahar | Academic Website</title>

<style>

/* GENERAL DESIGN */

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: "Segoe UI", Arial, sans-serif;
  background: #ffffff;
  color: #252525;
  line-height: 1.8;
}

a {
  color: inherit;
}

/* NAVIGATION */

nav {
  max-width: 1000px;
  margin: auto;
  padding: 28px 25px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 15px;
  border-bottom: 1px solid #eeeeee;
}

.logo {
  font-size: 23px;
  font-weight: 700;
  letter-spacing: -1px;
}

nav a {
  text-decoration: none;
  color: #777777;
  margin-left: 22px;
  font-size: 14px;
}

nav a:hover {
  color: #987a60;
}

/* INTRODUCTION */

.hero {
  max-width: 1000px;
  margin: auto;
  padding: 110px 25px 120px;
}

.small-title {
  color: #987a60;
  font-size: 12px;
  letter-spacing: 3px;
  font-weight: 600;
}

.hero h1 {
  font-size: clamp(48px, 8vw, 78px);
  font-weight: 650;
  line-height: 1.15;
  letter-spacing: -2px;
  margin: 22px 0;
}

.hero h2 {
  font-size: clamp(23px, 4vw, 34px);
  font-weight: 400;
  color: #555555;
  max-width: 760px;
  line-height: 1.5;
}

.hero p {
  color: #888888;
  font-size: 15px;
  margin-top: 25px;
}

/* CONTENT SECTIONS */

section {
  max-width: 1000px;
  margin: auto;
  padding: 75px 25px;
  border-top: 1px solid #eeeeee;
}

.section-number {
  font-size: 12px;
  color: #987a60;
  font-weight: 600;
  letter-spacing: 2px;
}

section h2 {
  font-size: clamp(29px, 5vw, 40px);
  font-weight: 600;
  letter-spacing: -1px;
  margin: 15px 0 25px;
}

section p {
  max-width: 760px;
  color: #666666;
  font-size: 17px;
}

/* RESEARCH CARDS */

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 25px;
  margin-top: 35px;
}

.card {
  background: #f8f7f5;
  padding: 32px;
  border-radius: 10px;
}

.card-number {
  color: #987a60;
  font-size: 12px;
  letter-spacing: 2px;
}

.card h3 {
  font-size: 23px;
  font-weight: 600;
  margin: 15px 0;
}

.card p {
  font-size: 15px;
  margin-bottom: 0;
}

/* PYTHON SECTION */

.python-box {
  background: #f8f7f5;
  border-radius: 10px;
  padding: 35px;
  margin-top: 30px;
}

.python-box ul {
  color: #666666;
  padding-left: 22px;
}

.python-box li {
  margin-bottom: 10px;
}

/* LINKS AND BUTTONS */

.button {
  display: inline-block;
  text-decoration: none;
  background: #292929;
  color: white;
  padding: 12px 24px;
  border-radius: 5px;
  font-size: 14px;
  margin: 15px 12px 0 0;
  transition: background 0.2s;
}

.button:hover {
  background: #987a60;
}

/* FOOTER */

footer {
  background: #f8f7f5;
  text-align: center;
  padding: 45px 20px;
  color: #777777;
  font-size: 14px;
}

footer a {
  color: #987a60;
  text-decoration: none;
}

/* MOBILE DESIGN */

@media (max-width: 650px) {

  .hero {
    padding: 75px 25px;
  }

  .research-grid {
    grid-template-columns: 1fr;
  }

  nav a {
    margin-left: 10px;
  }

  section {
    padding: 55px 25px;
  }

}

</style>
</head>

<body>

<!-- NAVIGATION -->

<nav>
  <div class="logo">Shahar.</div>

  <div>
    <a href="#about">About</a>
    <a href="#research">Research</a>
    <a href="#python">Python</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- INTRODUCTION -->

<header class="hero">

  <div class="small-title">
    WELCOME TO MY PERSONAL WEBSITE
  </div>

  <h1>Hi, I'm Shahar.</h1>

  <h2>
    Exploring membrane proteins
    through microscopy and science.
  </h2>

  <p>
    Electron Microscopy (EM) ·
    Atomic Force Microscopy (AFM) ·
    Python
  </p>

</header>

<!-- ABOUT ME -->

<section id="about">

  <div class="section-number">
    01 — ABOUT ME
  </div>

  <h2>A little about me</h2>

  <p>
    My research focuses on membrane proteins,
    using electron microscopy and atomic
    force microscopy to investigate their
    structures and properties.
  </p>

  <p>
    In our laboratory, we combine
    experimental microscopy with
    computational approaches to better
    understand biological systems.
  </p>

  <p>
    I am currently learning Python to
    develop programming skills that can
    support our research and scientific
    data analysis.
  </p>

</section>

<!-- RESEARCH -->

<section id="research">

  <div class="section-number">
    02 — MY RESEARCH
  </div>

  <h2>Membrane protein research</h2>

  <p>
    Membrane proteins are essential for
    many cellular processes, including
    molecular transport and communication.
  </p>

  <p>
    My research involves studying these
    proteins using complementary
    microscopy techniques.
  </p>

  <div class="research-grid">

    <div class="card">

      <div class="card-number">
        METHOD 01
      </div>

      <h3>Electron Microscopy</h3>

      <p>
        Electron microscopy (EM) allows
        us to investigate biological
        structures at very small scales
        and obtain structural information
        about membrane proteins.
      </p>

    </div>

    <div class="card">

      <div class="card-number">
        METHOD 02
      </div>

      <h3>Atomic Force Microscopy</h3>

      <p>
        Atomic force microscopy (AFM)
        provides nanoscale information
        about surfaces and molecular
        structures, complementing
        electron microscopy.
      </p>

    </div>

  </div>

</section>

<!-- PYTHON -->

<section id="python">

  <div class="section-number">
    03 — PYTHON & SCIENCE
  </div>

  <h2>Learning to code for research</h2>

  <p>
    Programming is an important tool
    in modern scientific research.
    It helps researchers process data,
    create visualizations, and automate
    repetitive tasks.
  </p>

  <div class="python-box">

    <h3>My goals for the Python course</h3>

    <p>
      I am taking the Weizmann Python
      Course 2026 to learn how to use
      programming in our laboratory.
    </p>

    <ul>
      <li>Learn Python fundamentals</li>
      <li>Analyze microscopy data</li>
      <li>Create scientific graphs</li>
      <li>Automate data analysis</li>
      <li>Develop tools for research</li>
    </ul>

    <a class="button"
       href="https://github.com/Code-Maven/wis-python-course-2026-10"
       target="_blank" rel="noopener noreferrer">
       Python Course
    </a>

    <a class="button"
       href="https://github.com/shalu13lyu"
       target="_blank" rel="noopener noreferrer">
       My GitHub
    </a>

  </div>

</section>

<!-- CONTACT -->

<section id="contact">

  <div class="section-number">
    04 — CONTACT
  </div>

  <h2>Let's connect</h2>

  <p>
    You can explore my programming
    projects and follow my Python
    learning journey on GitHub.
  </p>

  <a class="button"
     href="https://github.com/shalu13lyu"
     target="_blank" rel="noopener noreferrer">
     Visit My GitHub
  </a>

</section>

<!-- FOOTER -->

<footer>

  <p>
    Shahar · Membrane Protein Research
  </p>

  <p>
    © 2026 Shahar |
    <a href="https://github.com/shalu13lyu">
      GitHub
    </a>
  </p>

</footer>

</body>
</html>
