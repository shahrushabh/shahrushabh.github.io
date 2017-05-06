+++
# Date this page was created.
date = "2014-04-27"

# Project title.
title = "Mars Rover"

# Project summary to display on homepage.
summary = "iRobot navigation on artificial maze."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "marsrover/boundary.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["embedded_systems"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = "My caption :smile:"

+++

Mars Rover is an embedded system projects, that exposes students to embedded programming. Making use of C programming language along with the VORTEX platform, "that includes iRobot Create, the Cerebot II board, and attachments such as servo, SONAR, IR sensor, and LCD" panel. Teams, group of 3-4, are asked to calibrate sensors and program the robot for different tasks, one at a time. For example, Moving and turning the robot accurately, receiving and sending messages using serial communication, calibration of various sensors, and so on. The final project demonstration depends on the accuracy with which data is being fetched and analyzed. Demo required students to navigate the robot to the destination, without looking at the course, by analysis of data, in real time, received from the robot's sensors.

### Design and Implementation
* Calibration of iRobot's sensors, including Sonar sensor, IR sensor, Servo.
* Serial Data transmission for sending commands and receiving data.
* Implement GUI and communication between the robot and desktop in Matlab.
* Plot and update the graph with the most recent data received from the iRobot.

<div id="carousel-marsrover" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner" role="listbox">
    <div class="item active">
      <img src="/img/marsrover/home_view.png" class="img-responsive" alt="Home View">
      <div class="carousel-caption">
      <p style="color:grey">Object detection</p>
      </div>
    </div>
    <div class="item">
      <img src="/img/marsrover/course.jpg" class="img-responsive" alt="Maze">
      <div class="carousel-caption">
      <p>Maze to Navigate</p>
      </div>
    </div>
    <div class="item">
      <img src="/img/marsrover/destination.png" class="img-responsive" alt="Destination detection">
      <div class="carousel-caption">
      <p style="color:darkblue">Destination detection by sensors</p>
      </div>
    </div>
    <div class="item">
      <img src="/img/marsrover/commands.png" class="img-responsive" alt="Command Execution">
      <div class="carousel-caption">
      <p style="color:grey">Data collection</p>
      </div>
    </div>
    <div class="item">
      <img src="/img/marsrover/goal_reached.png" class="img-responsive" alt="Goal Reached!">
      <div class="carousel-caption">
        <p style="color:green">Goal Reached!</p>
      </div>
    </div>
  </div>
</div>
