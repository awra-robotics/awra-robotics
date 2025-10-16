<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>AWRA — Work Methodology</title>
  <style>
    body {font-family: Inter, system-ui, sans-serif; background:#0b1220; color:#e8edf3; margin:0; padding:32px;}
    h1, h2 {color:#00bcd4;}
    .section {margin-bottom: 24px; background: rgba(255,255,255,0.03); padding: 20px; border-radius: 12px;}
    ul {line-height:1.7;}
  </style>
</head>
<body>
  <h1>Work Methodology</h1>
  <p>The implementation of the project is based on several key stages, each focusing on a major aspect of system design and development.</p>

  <div class="section">
    <h2>1. Study and Analysis Phase</h2>
    <ul>
      <li>Conducting a study of the needs of the target group (patients with quadriplegia and mobility impairments):
        <ul>
          <li>Reducing the need for an assistant to help with mobility.</li>
          <li>Compensating for hand movement disabilities in quadriplegic patients.</li>
        </ul>
      </li>
      <li>Identifying areas to improve in traditional wheelchairs to define technical requirements:
        <ul>
          <li>Adding autonomous navigation for self-driving capabilities.</li>
          <li>Integrating an assistive robotic arm to replace hand functions.</li>
          <li>Developing a smart assistive system for task automation.</li>
        </ul>
      </li>
      <li>Defining technical specifications to be achieved:
        <ul>
          <li>Maximum load capacity of the wheelchair.</li>
          <li>Maximum payload of the robotic arm.</li>
          <li>Operational range and degrees of motion of the arm.</li>
          <li>Optimal indoor navigation speed.</li>
          <li>Battery capacity ensuring adequate runtime.</li>
        </ul>
      </li>
    </ul>
  </div>

  <div class="section">
    <h2>2. Mechanical Design Phase</h2>
    <ul>
      <li>Creating a design model that meets the required specifications:
        <ul>
          <li>Selecting suitable dimensions and materials.</li>
          <li>Choosing appropriate transmission mechanisms.</li>
          <li>Using CAD software such as <strong>SolidWorks</strong>.</li>
        </ul>
      </li>
      <li>Analyzing loads and stresses to ensure design reliability:
        <ul>
          <li>Testing design performance using <strong>ANSYS</strong>.</li>
          <li>Defining appropriate safety factors.</li>
        </ul>
      </li>
      <li>Selecting suitable manufacturing techniques for all project components.</li>
    </ul>
  </div>

  <div class="section">
    <h2>3. Programming and Control Phase</h2>
    <ul>
      <li>Programming the microcontroller to receive sensor readings and execute tasks accordingly.</li>
      <li>Controlling wheelchair and robotic arm motors to reach target positions.</li>
      <li>Implementing robotic arm control algorithms using:
        <ul>
          <li><strong>ROS (Robot Operating System):</strong> main system for coordinating all components.</li>
          <li><strong>ROS MoveIt:</strong> for forward and inverse kinematics motion planning.</li>
          <li><strong>Gazebo:</strong> for modeling and simulating performance before real-world testing.</li>
        </ul>
      </li>
      <li>Developing autonomous driving capabilities for navigation and obstacle avoidance using:
        <ul>
          <li><strong>ROS Navigation Stack:</strong> path planning and localization.</li>
          <li><strong>SLAM algorithms:</strong> for indoor mapping and localization.</li>
        </ul>
      </li>
      <li>Integrating voice recognition systems to interpret spoken commands using:
        <ul>
          <li><strong>Speech Recognition Frameworks:</strong> Google Speech-to-Text API, Vosk.</li>
        </ul>
      </li>
      <li>Programming computer vision systems for object recognition using:
        <ul>
          <li><strong>Object Detection Models:</strong> YOLOv8, Faster R-CNN.</li>
          <li><strong>Deep Learning Frameworks:</strong> OpenCV, PyTorch for image analysis.</li>
        </ul>
      </li>
    </ul>
  </div>
</body>
</html>
