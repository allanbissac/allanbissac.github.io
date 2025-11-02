<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Allan Binoy Issac Portfolio</title>
<style>
  /* General Reset */
  body, html {
    background-color: white;
    margin: 0; 
    padding: 0;
    font-family: Arial, sans-serif;
  }

  h1 {
    text-align: center; 
    padding-top: 30px;
  }

  p {
    font-size: 20px;
  }

  .container {
    background-color: white;
    text-align: center;
    margin: 0 10px;
  }

  .container-right {
    text-align: right;
  }

  .center_heading {
    text-align: center;
  }

  .center_img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    max-width: 100%;
    height: auto;
    transition: transform 0.3s ease;
  }

  .center_img:hover {
    transform: scale(1.05);
  }

  .center_underline {
    text-align: center;
    text-decoration: underline;
  }

  .myDiv {
    background-color: black;
    color: white;
    padding: 40px 20%;
  }

  .myDivWhite {
    background-color: white;
    color: black;
    padding: 50px 20%;
  }

  .flex-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding: 0 10%;
  }

  footer {
    text-align: center;
    padding: 100px 50px;
    background-color: black;
    color: white;
  }

  /* Profile image adjustment */
  .profile-img {
    width: 150px;
    height: auto;
    border-radius: 10px;
    margin-left: auto;
    margin-right: auto;
    display: block;
  }

  /* Social Icons */
  .social-icons img {
    width: 70px;
    height: auto;
    margin: 0 5px;
    transition: transform 0.3s ease;
  }

  .social-icons img:hover {
    transform: scale(1.2);
  }

  /* Skills Section */
  .skills-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px 10%;
  }

  .skills-container img {
    width: 100px;
    height: auto;
  }

  /* Responsive Projects Grid */
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 40px;
    padding: 40px 10%;
  }

  .project-item h3 {
    text-align: center;
    margin-bottom: 15px;
  }

  .project-item p {
    text-align: justify;
  }

  .project-item img {
    border-radius: 8px;
  }

  @media (max-width: 768px) {
    .myDiv, .myDivWhite {
      padding: 30px 10%;
    }
    .flex-container {
      flex-direction: column;
      align-items: center;
    }
    .container-right {
      text-align: center;
      margin-top: 20px;
    }
  }

</style>
</head>

<body>

<h1>ALLAN BINOY ISSAC</h1>
<hr />

<!-- About Me Section -->
<div class="flex-container">
  <div class="myDivWhite">
    <h2 class="center_underline"><u>About me</u></h2>
    <p>I am currently a Robotics MSc student at The University of Manchester. My areas of expertise include embedded systems, control and robotics. My career goal is to become a robotics researcher.</p>
    <p class="social-icons">
      <a href="https://github.com/allanbissac" target="_blank" rel="noopener noreferrer">
        <img src="github.png" alt="GitHub" />
      </a>
      <a href="https://www.linkedin.com/in/allan-binoy-issac" target="_blank" rel="noopener noreferrer">
        <img src="linkedin.png" alt="LinkedIn" />
      </a>
    </p>
  </div>

  <div class="container-right">
    <img src="allan.png" alt="Allan Binoy Issac" class="profile-img" />
  </div>
</div>

<!-- Projects Section -->
<div class="myDiv">
  <h2 class="center_underline"><u>Projects</u></h2>

  <div class="projects-grid">
    <div class="project-item">
      <h3>Autonomous robotic platform for object detection and retrieval</h3>
      <img src="autonomous.png" alt="Autonomous Robot" class="center_img" />
      <p>As part of the MSc team project, we are developing a robotic platform based on the Leo Rover to autonomously detect and navigate towards differently coloured objects...</p>
    </div>

    <div class="project-item">
      <h3>Biomedical Radar Device for Soft-tissue Imaging Research</h3>
      <img src="SGAP_platform.png" alt="Biomedical Radar" class="center_img" />
      <p>Developed a prototype near-field radar imaging system for non-invasive soft-tissue imaging...</p>
    </div>

    <div class="project-item">
      <h3>C.U.B.O. (Cube Utilising Brutal Over-engineering)</h3>
      <img src="cubo.png" alt="CUBO" class="center_img" />
      <p>An ongoing RoboSoc project, this team project involves designing an autonomous mechatronic system to solve a 3x3 Rubik's cube under 60 seconds...</p>
    </div>

    <div class="project-item">
      <h3>DSP-based musical reverb algorithms using Blackfin devices</h3>
      <img src="reverb.png" alt="DSP Reverb" class="center_img" />
      <p>This is my third-year individual project which implemented a reverberation algorithm...</p>
    </div>

    <div class="project-item">
      <h3>Embedded Systems Project</h3>
      <img src="buggy1.png" alt="Embedded Systems Buggy" class="center_img" />
      <p>In this second-year team project, we designed a semi-autonomous buggy that could follow a white line...</p>
    </div>
  </div>
</div>

<!-- Skills Section -->
<h2 class="center_heading"><u>Skills</u></h2>
<div class="skills-container">
  <img src="c-program-icon.png" alt="C" />
  <img src="cpp_logo.png" alt="C++" />
  <img src="matlab_logo.png" alt="MATLAB" />
  <img src="jn.png" alt="Jupyter Notebook" />
  <img src="latex.png" alt="LaTeX" />
  <img src="python-logo-only.png" alt="Python" />
  <img src="Raspberry-Pi-Symbol.png" alt="Raspberry Pi" />
  <img src="logo-ros.png" alt="ROS" />
</div>

<!-- Academic Videos Section -->
<h2 class="center_heading"><u>Academic videos</u></h2>
<p align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/rEPwbM8i3BM?si=GJhMsOeDzOkjb-d4&amp;start=1" 
  title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
  referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>

<!-- Footer -->
<footer>
  <p><b>&copy; Allan Binoy Issac. All rights reserved.</b></p>
  <a href="mailto:allanbissac@outlook.com" style="color:white">allanbissac@outlook.com</a>
</footer>

</body>
</html>
