---
layout: post
title: Controlling a Healthcare Robot using a Mobile Application
description: >-  
  An autonomous mobile robot controlled via a Flutter-based mobile application, supported by a Node.js backend.  
  The system allows nurses to send real-time delivery requests, monitor robot status, and view its live location.  
  The robot communicates with the backend through Wi-Fi, while ROS handles low-level control, including motion planning and feedback-based navigation.  
  A differential-drive model is used, with controllers like PID and LQR implemented for stability and trajectory tracking.
skills:
  - ROS
  - Flutter
  - Node.js
  - PID & LQR Control
  - Arduino
main-image: /image1.jpeg
---
---

## User Interface for Controlling the Assistive Nurse Robot

<img src="/assets/images/Untitled%20design%20(3).png" alt="Robot Image" style="width:70%; height:auto;">
.Built using Flutter for the mobile user interface, supporting both Android and web platforms.

.Backend developed with Node.js to handle API requests, mission scheduling, and data management.

.Used MongoDB to store nurse login credentials, user data, and delivery request records.

.Established communication between the robot and the app over Wi-Fi using a ZeroTier virtual network for secure and reliable remote access.

.Implemented a real-time WebSocket connection with the ROSBridge protocol to:

   Publish commands to the robot’s ROS topics.

   Subscribe to live robot telemetry (e.g., status, location, sensor data).

.Enabled low-latency, bidirectional communication for smooth robot control and real-time updates.

.Designed for nurses to send delivery requests, monitor robot status, and track its live location through the app.

.Ensured modular integration between ROS, Node.js backend, MongoDB, and the Flutter frontend.
  

## Demo Videos

Here’s a demonstration of key features and real-time control of a healthcare robot using a Flutter mobile application:

{% include youtube-video.html id="mclKxxoTl5U" autoplay="false" %}
{% include youtube-video.html id="U26JCEndvNg" autoplay="false" %}

<br>

## Awards
1. Recipient of AUB’s Dean’s Creative Achievement Award for outstanding
 innovation in engineering.
2. 2nd Place Winner at IEEE iCORE - FYP Demo Day Competition 2025
 hosted by the Lebanese American University. <br>

## Project Report

You can download the full project report here:

[Download PDF Report](/assets/FYP_Final_Report_Spring_compressed.pdf)


