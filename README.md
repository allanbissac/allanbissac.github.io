<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    h1 {
      text-align: center; padding-top: 30px;
    }
    .container{
      text-align:center;
    }
    .container-right{
      text-align:right;
    }
    body, html{
      background-color: white;
      margin: 0; padding: 0;
    }
    .center_img{
      display: block;
      margin-left: auto;
      margin-right:auto;
    }
    .myDiv{
      background-color: black; color: white;
      padding-top:40px; padding-right:75px; padding-left:75px; padding-bottom:50px;
    }
    .myDivWhite{
      background-color: white; color: black;
      padding-top:50px; padding-right:75px; padding-left:75px; padding-bottom:50px;
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
      <h2>About me</h2>
      <p style="color:black;">I am a Robotics MSc student at The University of Manchester. My areas of expertise include embedded systems, control and robotics.</p>
    </div>
    <div class="container-right">
    <img src="newton.png" style="width:125px; height:auto">
      </div>
    </div>
  

  <div class="myDiv">
    <h2>Projects</h2>
    <!-- <p style="font-size:120%;"><b>Autonomous robotic platform for object detection and retrieval</b></p> -->
    <h3><b>Autonomous robotic platform for object detection and retrieval</b></h3>
    <p>Currently developing a robotic platform based on the Leo Rover to autonomously detect and navigate towards differently coloured objects. The robot is expected to carry the object using a gripper attached to its manipulator and place the object in a bin that is of the same colour as the object.</p>
    <h3>Biomedical Radar Device for Soft-tissue Imaging Research</h3>
    <img src="mechatronic_rig.png" class="center_img">
    <p>Developed a prototype near-field radar imaging system for non-invasive soft-tissue imaging. Focused on writing firmware for a Texas Instruments LAUNCHXL-F28379D board and Arduino Uno board for phase-locked loop frequency generation and communication with a mechatronic rig, respectively.</p>
    <h3>C.U.B.O. (Cube Utilising Brutal Over-engineering)</h3>
    <p>Designing a robotic system powered by a Raspberry Pi board to solve a 3x3 Rubik's cube under 1 minute. Features a mechanical holder for the Rubik's cube and computer vision algorithms to perform the pattern identification and action implementation.</p>
    <h3>DSP-based musical reverb algorithms using Blackfin devices</h3>
    <p>Implemented a reverberation algorithm comprised of digital comb filters, low pass filters and allpass filters for offline and real-time audio. The offline algorithm was applied to audio files through a custom graphical user interface in Delphi. Real-time audio processing was achieved on an Analog Devices Evaluation board featuring an ADSPBF706 digital signal processor</p>
    <h3>Embedded Systems Project</h3>
    <p>Designed a line-following buggy featuring an STM32 microcontroller board. Duties involved writing the PID control algorithm and TCRT5000 sensor array PCB design.</p>
    
  </div>
  
<h2 class="myDivWhite">Skills</h2>
<div class="container">
  <img src="C_logo.png" style="width:100px; height:auto">
  <img src="cpp_logo.png" style="width:100px; height:auto">
  <img src="matlab_logo.png" style="width:100px; height:auto">
  <img src="jupyter-notebook-logo.png" style="width:100px; height:auto">
  <img src="latex-project-logp.png" style="width:100px; height:auto">
  <img src="python-logo-only.png" style="width:100px; height:auto">
  <img src="Raspberry-Pi-Symbol.png" style="width:100px; height:auto">
  <img src="logo-ros.png" style="width:100px; height:auto">
  
</div>

<h2 class="myDivWhite">Video</h2>

<footer>
  <h4>&copy;Allan Binoy Issac. All rights reserved.</h4>
  <a href="mailto:allanbissac@outlook.com" style="color:white">allanbissac@outlook.com</a>
</footer>



</body>

</html>
