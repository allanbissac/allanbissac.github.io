<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Allan Binoy Issac</title>
<style>
  body, html {
    margin: 0;
    padding: 0;
    background-color: #fff;
  }

  h1, h2, h3 {
    text-align: center;
    margin: 0 0 20px 0;
  }

  p {
    font-size: 18px;
    line-height: 1.6;
  }

  /* About Me Section */
  .about-me {
    display: flex;
    flex-direction: row; /* Row on large screens */
    align-items: center;
    justify-content: space-between;
    padding: 50px 10%;
    background-color: #f9f9f9;
  }

  .about-text {
    flex: 1;
    padding-right: 20px;
  }

  .about-img {
    flex-shrink: 0;
    max-width: 200px;
    width: 100%;
    border-radius: 10px;
    transition: transform 0.3s ease; /* Hover effect */
  }

  .about-img:hover {
    transform: scale(1.05);
  }

  /* Projects Section */
  section.projects {
    background-color: #000;
    color: white;
    padding: 50px 10%;
  }

  section.projects img {
    max-width: 50%;
    height: auto;
    display: block;
    margin: 20px auto;
    transition: transform 0.3s ease;
  }

  section.projects img:hover {
    transform: scale(1.05);
  }

  /* Skills Section */
  section.skills {
    background-color: #fff;
    padding: 50px 10%;
    text-align: center;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px; /* space between icons */
  }

  section.skills img {
    height: 80px; /* adjust as needed */
    width: auto;
    transition: transform 0.3s ease;
  }

  section.skills img:hover {
    transform: scale(1.1);
  }

  /* Academic Videos Section */
  section.videos {
    background-color: #f0f0f0;
    padding: 50px 10%;
    text-align: center;
  }

  /* Footer */
  footer {
    text-align: center;
    padding: 50px 10%;
    background-color: #000;
    color: white;
  }

  /* Responsive Design */
  @media screen and (max-width: 1024px) {
    .about-me {
      padding: 50px 5%;
    }

    section.projects {
      padding: 50px 5%;
    }

    section.skills {
      padding: 50px 5%;
    }

    section.videos {
      padding: 50px 5%;
    }

    footer {
      padding: 50px 5%;
    }
  }

  @media screen and (max-width: 768px) {
    .about-me {
      flex-direction: column; /* Stack image above text */
      text-align: center;
    }

    .about-text {
      padding: 0;
    }

    .about-img {
      margin-bottom: 20px;
      max-width: 150px;
    }

    section.projects img {
      max-width: 80%;
    }
  }

</style>
</head>
<body>

<h1>ALLAN BINOY ISSAC</h1>
<hr />

<section class="about-me">
  <img src="allan.png" alt="Allan Binoy Issac" class="about-img">
  <div class="about-text">
    <h2>About Me</h2>
    <p>I am currently a Robotics MSc student at The University of Manchester. My areas of expertise include embedded systems, control and robotics. My career goal is to become a robotics researcher.</p>
    <p>
      <a href="https://github.com/allanbissac" target="_blank" rel="noopener noreferrer">
        <img src="github.png" style="width:50px; height:auto" />
      </a>
      <a href="https://www.linkedin.com/in/allan-binoy-issac" target="_blank" rel="noopener noreferrer">
        <img src="linkedin.png" style="width:50px; height:auto" />
      </a>
    </p>
  </div>
</section>

<section class="projects">
  <h2>Projects</h2>

  <h3>Autonomous robotic platform for object detection and retrieval</h3>
  <img src="autonomous.png" alt="Autonomous Robot">
  <p>As part of the MSc team project, we are developing a robotic platform based on the Leo Rover to autonomously detect and navigate towards differently coloured objects. The robot will carry the object using a gripper attached to its manipulator and place the object in a bin that is of the same colour as the object. I worked on assembly and manipulator setup, and my next task is to focus on the computer vision to train the manipulator using YOLOv8.</p>

  <h3>C.U.B.O. (Cube Utilising Brutal Over-engineering)</h3>
  <img src="cubo.png" alt="Cube Project">
  <p>An ongoing RoboSoc project, this team project involves designing an autonomous mechatronic system to solve a 3x3 Rubik's cube under 60 seconds. It features a customised mechanical holder for holding and rotating the cube, and a Raspberry Pi Zero 2 W for performing the computing. At the time of writing, we are working on circuit board design and the computer vision.</p>
  
  <h3>Biomedical Radar Device for Soft-tissue Imaging Research</h3>
  <img src="SGAP_platform.png" alt="Radar Device">
  <p>Developed a prototype near-field radar imaging system for non-invasive soft-tissue imaging. I largely focused on writing the firmware for a Texas Instruments LAUNCHXL-F28379D board and Arduino Uno board for phase-locked loop frequency generation and communication with a mechatronic rig, respectively.</p>

  <h3>DSP-based musical reverb algorithms using Blackfin devices</h3>
  <img src="reverb.png" alt="Reverb Project">
  <p>This is my third-year individual project which implemented a reverberation algorithm, supervised by Prof. Patrick Gaydecki. The algorithm comprised digital comb filters, low pass filters and allpass filters arranged logically to simulate direct and indirect audio reflections. Separate offline and real-time algorithms were made. The offline algorithm was programmed in Delphi and could be applied to .WAV files selected via a custom graphical user interface. Real-time audio processing was achieved by programming an ADSP-BF706 EZ-KIT Mini Evaluation board with the algorithm and then applying it to an audio input.</p>

  <h3>Embedded Systems Project</h3>
  <img src="buggy1.png" alt="Buggy Project">
  <p>In this second-year team project, we designed a semi-autonomous buggy that could follow a white line. In terms of hardware, the buggy featured an STM32 microcontroller board to perform all the computing, an optical sensor array to detect the white line, motors, gearboxes and the customised chassis holding everything together. My duties involved writing the PID control algorithm to ensure that the buggy stayed on track and the design of the PCB incorporating the TCRT5000 sensor array.</p>
</section>

<section class="skills">
  <h2>Skills</h2>
  <img src="c-program-icon.png" alt="C">
  <img src="cpp_logo.png" alt="C++">
  <img src="matlab_logo.png" alt="MATLAB">
  <img src="jn.png" alt="Jupyter Notebook">
  <img src="latex.png" alt="LaTeX">
  <img src="python-logo-only.png" alt="Python">
  <img src="Raspberry-Pi-Symbol.png" alt="Raspberry Pi">
  <img src="logo-ros.png" alt="ROS">
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

