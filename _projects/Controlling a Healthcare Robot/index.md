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

<div style="text-align: center;">
  <img src="/assets/images/Untitled%20design%20(3).png" alt="Robot Image" style="width:80%; height:auto;">
</div>

## System Architecture:
  - Flutter for building a responsive cross-platform mobile UI (Android & Web)
  - Node.js backend to handle API requests, mission scheduling, and system logic
  - MongoDB to store nurse login data, user profiles, and delivery requests
  - ROSBridge protocol over WebSocket for real-time communication with the ROS system
  - ZeroTier virtual network enables secure Wi-Fi communication between the robot and the app
  - Real-time publishing and subscribing to ROS topics (commands, status, telemetry)
  - Seamless integration across ROS, Node.js, MongoDB, and Flutter
  - Designed for nurses to send delivery requests and monitor robot location/status in real time

  

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


