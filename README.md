<html>
<head>
  <style>
    * {
      box-sizing: border-box
    }
    .column{
      float: left; width: 25%; padding: 5px;
    }
    .row::after{
      content: ""; clear: both; display: table;
    }
    body, html{
      background-color: white;
      margin: 0; padding: 0;
    }
    .myDiv {
      background-color: black; color: white; width: 100%;
      margin: 0; padding: 0;
    }
  </style>
</head>
  
<body>
  <h1>About me</h1>
  <p style="color:black;">I am a Robotics MSc student at The University of Manchester. My areas of expertise include embedded systems, control and robotics.</p>

  <div class="myDiv">
    <h1>Projects</h1>
    <!-- <p style="font-size:120%;"><b>Autonomous robotic platform for object detection and retrieval</b></p> -->
    <h2><b>Autonomous robotic platform for object detection and retrieval</b></h2>
  </div>
  
<h1>Skills and interests</h1>
<div class="row">
  <div class="column">
    <img src="C_logo.png" alt="C" style="width:100px;height:auto">
  </div>
  <div class="column">
    <img src="cpp_logo.png" alt="C++" style="width:100px;height:auto">
  </div>
  <div class="column">
    <img src="jupyter-notebook-logo.png" alt="Jupyter Notebook" style="width:100px;height:auto">
  </div>
  <div>
    <img src="matlab_logo.png" alt="MATLAB" style="width:100px;height:auto">
  </div>
</div>


</body>

</html>
