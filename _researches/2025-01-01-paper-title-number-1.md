---
title: "Autonomous Exploration in Buildings with Climbable Robots"
# collection: researches
category: conferences
permalink: /research/2025-01-01-paper-title-number-1
# excerpt: 'This paper is about multi-agent task allocation.'
date: 2021-10-02
# venue: 'Proceedings of 2021 International Conference on Autonomous Unmanned Systems (ICAUS 2021) '
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: '../files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Zhang, X., Liu, H., Xue, L., Li, X., Guo, W., Yu, S., ... & Xu, H. (2021, September). Multi-objective Collaborative Optimization Algorithm for Heterogeneous Cooperative Tasks Based on Conflict Resolution. In International Conference on Autonomous Unmanned Systems (pp. 2548-2557). Singapore: Springer Singapore.'
# status: 'published'
---

Background

===

Inspired by ETH Zurich's NiftiBot, our lab developed a similar tracked robot designed to achieve autonomous exploration in complex building environments. The robot uses its excellent mobility to independently complete navigation and map construction of the entire building.

Challenges

===

Developing an autonomous exploration framework from scratch is a major challenge, because most existing algorithms for similar robots are not open source. The NiftiBot-inspired robot we developed is a tracked ground robot equipped with four adjustable swing arms. Compared with traditional vehicles, its mobility is significantly enhanced, and it can achieve functions such as climbing stairs and crossing obstacles. Although the track control is relatively simple, how to adjust the swing arms in real time according to the scene to climb over various obstacles is a key technical difficulty.

Contributions

===

- The development of the robot's autonomous navigation framework has been initially completed, covering modules such as perception, planning, localization (completed by other team members) and control.
- Through a large number of field experiments, the robot's autonomous exploration performance in complex environments has been verified, proving its stability and reliability.

Trajectory tracking effect:

<video width="560" height="315" controls>
  <source src="../videos/car_2/视频1.mkv" type="video/mp4">
  Your browser does not support the video tag.
</video>

<video width="560" height="315" controls>
  <source src="../videos/car_2/视频2.mkv" type="video/mp4">
  Your browser does not support the video tag.
</video>

![picture 0](../videos/car_2/图片1.png)  

![picture 1](../videos/car_2/图片4.png)  

![picture 2](../videos/car_2/图片5.png)  
