<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    h1 {
      text-align: center; padding-top: 30px;
    }
    .container{
      background-color: white;
      text-align:center;
      margin-right: 10px;
      margin-left: 10px;
    }
    .container-right{
      text-align:right;
    }
    body, html{
      background-color: white;
      margin: 0; padding: 0;
    }
    .center_heading{
      text-align: center;
    }
    .center_img{
      display: block;
      margin-left: auto;
      margin-right:auto;
    }
    .center_underline{
      text-align: center; text-decoration: underline;
    }
    .myDiv{
      background-color: black; color: white;
      padding-top:40px; padding-right:20%; padding-left:20%; padding-bottom:50px;
    }
    .myDivWhite{
      background-color: white; color: black;
      padding-top:50px; padding-right:20%; padding-left:20%; padding-bottom:100px;
    }
    .flex-container{
      display: flex; justify-content: space-around;
    }
    footer {
      text-align: center;
      padding-top:100px; padding-bottom: 100px; padding-right:50px; padding-left:50px;
      background-color: black;
      color: white;
      }
  </style>
</head>
  
<body>
  <h1>ALLAN BINOY ISSAC</h1>
  <hr>

  <div class="flex-container">
    <div class="myDivWhite">
      <h2 class="center_underline"><u>About me</u></h2>
      <p style="color:black;">I am a Robotics MSc student at The University of Manchester. My areas of expertise include embedded systems, control and robotics. My career goal is to become a robotics researcher.</p>
      <p><a href="https://github.com/allanbissac" target="_blank" rel="noopener noreferrer">
        <img src="github.png" style="width:75px;height:auto">
        </a></p>
    </div>
    <div class="container-right">
    <img src="allan.png" style="width:150px; height:auto">
      </div>
    </div>
  

  <div class="myDiv">
    <h2 class="center_underline"><u>Projects</u></h2>
    <!-- <p style="font-size:120%;"><b>Autonomous robotic platform for object detection and retrieval</b></p> -->
    <h3 class="center_heading"><b>Autonomous robotic platform for object detection and retrieval</b></h3>
    <img src="autonomous.png" class="center_img" style="width:50%; height:auto;">
    <p>As part of the MSc team project, we are developing a robotic platform based on the Leo Rover to autonomously detect and navigate towards differently coloured objects. The robot will carry the object using a gripper attached to its manipulator and place the object in a bin that is of the same colour as the object. I worked on assembly and manipulator setup, and my next task is to focus on the computer vision to train the manipulator using YOLOv8.</p>
    <h3 class="center_heading">Biomedical Radar Device for Soft-tissue Imaging Research</h3>
    <img src="SGAP_platform.png" class="center_img" style="width:50%; height:auto;">
    <p>Developed a prototype near-field radar imaging system for non-invasive soft-tissue imaging. I largely focused on writing the firmware for a Texas Instruments LAUNCHXL-F28379D board and Arduino Uno board for phase-locked loop frequency generation and communication with a mechatronic rig, respectively.</p>
    <h3 class="center_heading">C.U.B.O. (Cube Utilising Brutal Over-engineering)</h3>
    <img src="cubo.png" class="center_img" style="width:50%; height:auto;">
    <p>An ongoing RoboSoc project, this team project involves designing an autonomous mechatronic system to solve a 3x3 Rubik's cube under 60 seconds. It features a customised mechanical holder for holding and rotating the cube, and a Raspberry Pi Zero 2 W for performing the computing. At the time of writing, we are working on circuit board design and the computer vision.</p>
    <h3 class="center_heading">DSP-based musical reverb algorithms using Blackfin devices</h3>
    <img src="reverb.png" class="center_img" style="width:50%; height:auto;">
    <p>This is my third-year individual project which implemented a reverberation algorithm, supervised by Prof. Patrick Gaydecki. The algorithm comprised digital comb filters, low pass filters and allpass filters arranged logically to simulate direct and indirect audio reflections. Separate offline and real-time algorithms were made. The offline algorithm was programmed in Delphi and could be applied to .WAV files selected via a custom graphical user interface. Real-time audio processing was achieved by programming an ADSP-BF706 EZ-KIT Mini Evaluation board with the algorithm and then applying it to an audio input.</p>
    <h3 class="center_heading">Embedded Systems Project</h3>
    <img src="buggy1.png" class="center_img" style="width:50%; height:auto;">
    <p>In this second-year team project, we designed a semi-autonomous buggy that could follow a white line. In terms of hardware, the buggy featured an STM32 microcontroller board to perform all the computing, an optical sensor array to detect the white line, motors, gearboxes and the customised chassis holding everything together. My duties involved writing the PID control algorithm to ensure that the buggy stayed on track and the design of the PCB incorporating the TCRT5000 sensor array.</p>
    
  </div>
  
<h2 class="center_heading"><u>Skills</u></h2>
<div class="container">
  <img src="c-program-icon.png" style="width:100px; height:auto">
  <img src="cpp_logo.png" style="width:100px; height:auto">
  <img src="matlab_logo.png" style="width:100px; height:auto">
  <img src="jn.png" style="width:100px; height:auto">
  <img src="latex.png" style="width:100px; height:auto">
  <img src="python-logo-only.png" style="width:100px; height:auto">
  <img src="Raspberry-Pi-Symbol.png" style="width:100px; height:auto">
  <img src="logo-ros.png" style="width:100px; height:auto">
  
</div>

<h2 class="center_heading"><u>Academic videos</u></h2>
<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/rEPwbM8i3BM?si=GJhMsOeDzOkjb-d4&amp;start=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>

<footer>
  <h4>&copy;Allan Binoy Issac. All rights reserved.</h4>
  <a href="mailto:allanbissac@outlook.com" style="color:white">allanbissac@outlook.com</a>
</footer>



</body>

</html>
