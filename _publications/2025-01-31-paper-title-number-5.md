---
title: "In-Pipe Navigation Development Environment and A Smooth Path Planning Method on Pipeline Surface."
collection: publications
category: conferences
permalink: /publication/2025-01-31-paper-title-number-5
excerpt: 'This paper is about climbing robot simulation environment and planning algorithm.'
date: 2025-01-31
venue: '2025 IEEE International Conference on Robotics & Automation(ICRA2025)'
paperurl: 'http://neuliuhao.github.io/files/ICRA2025.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
status: 'accepted'

images:
  - ../images/homepage.png
  - /images/homepage.png
  - ../images/liuhao.png
---

Background
======
As the lead researcher on this project, I was responsible for the autonomous navigation system of a magnetic wheeled climbing robot for industrial applications. The robot was equipped with a hardware prototype but lacked a navigation framework, which brought unique challenges to the development of navigation algorithms due to limited previous research and the lack of open source simulation tools specifically for climbing robots.

Challenges
======
The project required the creation of a novel navigation algorithm framework, a custom simulation system for a climbing robot, and a specialized path planning method. The lack of reference material and the need for a custom simulation environment posed significant obstacles, requiring innovative solutions for algorithm and simulation development.

Contributions
======
- **Novel Path-Planning Method:** I proposed a path-planning approach optimized for pipeline environments. By leveraging the pipeline's centerline and employing a three-dimensional Frenet coordinate system, I developed a method to generate feasible paths on a two-dimensional manifold, ensuring robust navigation in constrained spaces.
- **Custom Gazebo Plugin and Simulation Environment:** I independently developed a Gazebo plugin tailored for climbing robots, accompanied by a comprehensive environment model. This simulation framework, designed to be open-sourced, enables accurate testing and validation of navigation algorithms for climbing robots.
- **Algorithm Validation:** I rigorously validated the proposed algorithm through extensive simulations and real-world experiments, demonstrating its effectiveness in pipeline navigation tasks.
- **Publication at ICRA 2025:** I synthesized the research into a high-quality publication accepted at ICRA 2025, detailing the methodology, experimental results, and publication [1].

Results
======
The developed system achieved fully autonomous navigation for the climbing robot in pipeline environments. Compared to traditional methods, the proposed approach significantly improved planning success rates and path smoothness. Detailed experimental results are presented in the ICRA 2025 publication [1]. The navigation framework and simulation tools are poised for open-source release, offering valuable resources for future research and industrial applications.

Video
======
<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

<!-- 或者使用本地视频 -->

The video submitted to ICRA2025:

<video width="560" height="315" controls>
  <source src="../videos/magbot/媒体1.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Field experiment video:

<video width="560" height="315" controls>
  <source src="../videos/magbot/媒体2.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<video width="560" height="315" controls>
  <source src="../videos/magbot/媒体3.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<video width="560" height="315" controls>
  <source src="../videos/magbot/媒体4.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

