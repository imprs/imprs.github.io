---
layout: page
title: GRASPberry
description: Innovate UK funded project for soft fruit harvesting.
img: /assets/img/projects/graspberry-poster.jpeg
importance: 1
category: work
---

PI: <a href="https://staff.lincoln.ac.uk/gcielniak" target="blank">Dr. Grzegorz Cielniak</a> and <a href="https://staff.lincoln.ac.uk/mhanheide" target="blank">Prof. Marc Hanheide</a><br>
Project year: 2020-21

<div class="row justify-content-md-center">
    <div class="col-lg-8">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/graspberry-poster.jpeg' | relative_url }}" alt="" data-zoomable title="graspberry-poster"/>
    </div>
</div>
<div class="caption">
    Thorvald robot with the manipulator. <br>
    Image copyright Saga Robotics/ Aftenposten Newspaper (Norway)
</div>

<br>
##### I worked on different things in this project. Some of them are:

<br>

##### Low-level control interface for the manipulator

Developed the low-level control interface using CANOpen (along with Dr. Grzegorz Cielniak, who provided amazing base code!) for the manipulator and integrated it with the ROS ecosystem using ros_control. I also worked with a colleague to integrate the manipulator with Moveit!.

<div class="row justify-content-md-center">
    <div class="col-lg-6">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/graspberry-robot.gif' | relative_url }}" alt="" data-zoomable title="graspberry-robot"/>
    </div>
</div>

<br>

##### Integration of motion planning and scheduling package 

In another project, I worked with one of my colleagues to refactor their work and integrate it with the project code. I also added some visualizations (e.g., arm workspace, planned and actual path) that you can see in the image below. Moreover, I slightly helped another colleague to develop realistic strawberry models in ROS/ Gazebo, which can be used to simulate the grasping scenario in Gazebo.

<div class="row justify-content-md-center">
    <div class="col-lg-8">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/projects/graspberry-planning-demo.gif' | relative_url }}" alt="" data-zoomable title="graspberry-planning-demo"/>
    </div>
</div>

<br>

##### Development and version control

I also contributed to the development and version control for some of the common packages in the project repository (e.g., launch system, simulation).

