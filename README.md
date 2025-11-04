<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  
  <title>Allan Binoy Issac</title>
  
  <!--  SEO Meta Tags -->
  <meta name="description" content="Personal website of Allan Binoy Issac, MSc Robotics student at The University of Manchester. Passionate about embedded systems, control, and robotics engineering." />
  <meta name="keywords" content="Allan Binoy Issac, Allan Issac, engineer" />
  <meta name="author" content="Allan Binoy Issac" />

  <!--  Open Graph (for Google, LinkedIn, and social previews) -->
  <meta property="og:title" content="Allan Binoy Issac - Robotics Engineer" />
  <meta property="og:description" content="MSc Robotics student at The University of Manchester, specializing in embedded systems, control, and robotics." />
  <meta property="og:url" content="https://allanbissac.github.io/" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://allanbissac.github.io/allan.png" />

  <!--  Structured Data for Google -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Allan Binoy Issac",
    "url": "https://allanbissac.github.io/",
    "image": "https://allanbissac.github.io/allan.png",
    "sameAs": [
      "https://github.com/allanbissac",
      "https://www.linkedin.com/in/allan-binoy-issac"
    ],
    "alumniOf": {
      "@type": "CollegeOrUniversity",
      "name": "The University of Manchester"
    },
    "jobTitle": "MSc Robotics Student"
  }
  </script>

  <!--  Styling (your original CSS) -->
  <style>
    /* Your existing CSS goes here — no changes needed */
    body, html {
      margin: 0;
      padding: 0;
      background-color: #fff;
    }
    h1, h2, h3 {
      text-align: center;
      margin: 0 0 20px 0;
    }
    h1 { margin-top: 30px; }
    p { font-size: 18px; line-height: 1.6; }
    a { text-decoration: none; }
    .about-me {
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: space-between;
      padding: 50px 10%;
      background-color: #f9f9f9;
    }
    .about-text { flex: 1; padding-right: 30px; }
    .about-text h2 { text-align: center; }
    .about-img {
      flex-shrink: 0;
      max-width: 200px;
      width: 100%;
      border-radius: 10px;
      margin-left: 30px;
      transition: transform 0.3s ease;
    }
    .about-img:hover { transform: scale(1.05); }
    section.projects {
      background-color: #000;
      color: white;
      padding: 50px 10%;
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      justify-content: center;
      align-items: stretch;
    }
    .project {
      background-color: #111;
      padding: 20px;
      flex: 1 1 45%;
      min-width: 300px;
      box-sizing: border-box;
      border-radius: 10px;
      display: flex;
      flex-direction: column;
    }
    .project img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 10px auto;
      transition: transform 0.3s ease;
    }
    .project img:hover { transform: scale(1.05); }
    .project p { flex-grow: 1; }
    section.skills {
      background-color: #fff;
      padding: 50px 10%;
      text-align: center;
    }
    section.skills h2 { margin-bottom: 30px; }
    .skills-icons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .skills-icons img {
      height: 80px;
      width: auto;
      transition: transform 0.3s ease;
    }
    .skills-icons img:hover { transform: scale(1.1); }
    section.videos {
      background-color: #f0f0f0;
      padding: 50px 10%;
      text-align: center;
    }
    section.videos iframe { max-width: 100%; }
    footer {
      text-align: center;
      padding: 50px 10%;
      background-color: #000;
      color: white;
    }
    @media screen and (max-width: 1024px) {
      .about-me, section.projects, section.skills, section.videos, footer {
        padding: 50px 5%;
      }
    }
    @media screen and (max-width: 768px) {
      .about-me {
        flex-direction: column;
        text-align: center;
      }
      .about-text { padding: 0; }
      .about-img {
        margin-left: 0;
        margin-bottom: 20px;
        max-width: 150px;
      }
      .project { flex: 1 1 100%; }
      section.projects img { max-width: 80%; }
    }
  </style>
</head>

<body>

<h1>ALLAN BINOY ISSAC</h1>
<hr />

<section class="about-me">
  <div class="about-text">
    <h2>About Me</h2>
    <p>I am currently a Robotics MSc student at The University of Manchester. My areas of expertise include embedded systems, control and robotics. My career goal is to become a robotics engineer.</p>
    <p>
      <a href="https://github.com/allanbissac" target="_blank" rel="noopener noreferrer">
        <img src="github.png" style="width:50px; height:auto" />
      </a>
      <a href="https://www.linkedin.com/in/allan-binoy-issac" target="_blank" rel="noopener noreferrer">
        <img src="linkedin.png" style="width:50px; height:auto" />
      </a>
    </p>
  </div>
  <img src="allan.png" alt="Allan Binoy Issac" class="about-img">
</section>

<section class="projects">
  <h2 style="width:100%;">Projects</h2>

  <div class="project">
    <h3>Autonomous robotic platform for object detection and retrieval</h3>
    <img src="autonomous.png" alt="Autonomous Robot">
    <p>As part of the MSc team project, we are developing a robotic platform based on the Leo Rover to autonomously detect and navigate towards differently coloured objects. The robot will carry the object using a gripper attached to its manipulator and place the object in a bin that is of the same colour as the object. I worked on assembly and manipulator setup, and my next task is to focus on the computer vision to train the manipulator using YOLOv8.</p>
  </div>

  <div class="project">
    <h3>C.U.B.O. (Cube Utilising Brutal Over-engineering)</h3>
    <img src="cubo.png" alt="Cube Project">
    <p>An ongoing RoboSoc project, this team project involves designing an autonomous mechatronic system to solve a 3x3 Rubik's cube under 60 seconds. It features a customised mechanical holder for holding and rotating the cube, and a Raspberry Pi Zero 2 W for performing the computing. At the time of writing, we are working on circuit board design and the computer vision.</p>
  </div>

  <div class="project">
    <h3>Biomedical Radar Device for Soft-tissue Imaging Research</h3>
    <img src="SGAP_platform.png" alt="Radar Device">
    <p>Developed a prototype near-field radar imaging system for non-invasive soft-tissue imaging. I largely focused on writing the firmware for a Texas Instruments LAUNCHXL-F28379D board and Arduino Uno board for phase-locked loop frequency generation and communication with a mechatronic rig, respectively.</p>
  </div>

  <div class="project">
    <h3>DSP-based musical reverb algorithms using Blackfin devices</h3>
    <img src="reverb.png" alt="Reverb Project">
    <p>Third-year individual project which implemented a reverberation algorithm, supervised by Prof. Patrick Gaydecki. The algorithm comprised digital comb filters, low pass filters and allpass filters to simulate direct and indirect sound reflections. An offline algorithm was programmed in Delphi and applied to .WAV files selected via a user interface. Real-time audio processing was achieved by programming an ADSP-BF706 EZ-KIT Mini Evaluation board with the algorithm and then applying it to an audio input.</p>
  </div>

  <div class="project">
    <h3>Embedded Systems Project</h3>
    <img src="buggy1.png" alt="Buggy Project">
    <p>In this second-year team project, we designed a semi-autonomous buggy that could follow a white line. In terms of hardware, the buggy featured an STM32 microcontroller board to perform all the computing, an optical sensor array to detect the white line, motors, gearboxes and the customised chassis holding everything together. My duties involved writing the PID control algorithm to ensure that the buggy stayed on track and the design of the PCB incorporating the TCRT5000 sensor array.</p>
  </div>
</section>

<section class="skills">
  <h2>Skills</h2>
  <div class="skills-icons">
    <img src="c-program-icon.png" alt="C">
    <img src="cpp_logo.png" alt="C++">
    <img src="matlab_logo.png" alt="MATLAB">
    <img src="jn.png" alt="Jupyter Notebook">
    <img src="latex.png" alt="LaTeX">
    <img src="python-logo-only.png" alt="Python">
    <img src="Raspberry-Pi-Symbol.png" alt="Raspberry Pi">
    <img src="logo-ros.png" alt="ROS">
  </div>
</section>

<section class="videos">
  <h2>Academic Videos</h2>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/rEPwbM8i3BM?si=GJhMsOeDzOkjb-d4&amp;start=1" 
          title="YouTube video player" frameborder="0" allowfullscreen></iframe>
</section>

<footer>
  <p><b>&copy; Allan Binoy Issac. All rights reserved.</b></p>
  <a href="mailto:allanbissac@outlook.com" style="color:white">allanbissac@outlook.com</a>
</footer>

</body>
</html>

