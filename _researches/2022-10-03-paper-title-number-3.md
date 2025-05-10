---
title: "Autonomous driving vehicle passing through an intersection in an open scene"
collection: researches
category: conferences
permalink: /research/2022-10-03-paper-title-number-3
# excerpt: 'This paper is about multi-agent task allocation.'
date: 2022-10-03
# venue: 'Proceedings of 2021 International Conference on Autonomous Unmanned Systems (ICAUS 2021) '
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: '../files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Zhang, X., Liu, H., Xue, L., Li, X., Guo, W., Yu, S., ... & Xu, H. (2021, September). Multi-objective Collaborative Optimization Algorithm for Heterogeneous Cooperative Tasks Based on Conflict Resolution. In International Conference on Autonomous Unmanned Systems (pp. 2548-2557). Singapore: Springer Singapore.'
# status: 'published'
---


Background
======
As a team member, I contributed to the development of L2 autonomous driving solutions, assisting with the design and optimization of navigation algorithms. My role focused on addressing the issue of reference line failure at intersections by developing an algorithm to generate safe, drivable paths in real time for complex road conditions and dynamic obstacles.

Challenges
======
Intersections are complex environments with heavy pedestrian and vehicle traffic, requiring navigation algorithms to ensure path safety, smoothness, and real-time performance. Traditional reference-line-based algorithms often fail when encountering dynamic obstacles like temporary roadblocks, necessitating an efficient algorithm to generate adaptive paths while maintaining computational efficiency for real-time applications.

Contributions
======
- **Hybrid Path Planning Approach:** I assisted in designing a path planning method combining the A* algorithm with Dubins curves to generate discrete path points as an initial reference line solution, followed by discrete point optimization to improve path smoothness and feasibility.
- **Exploration of Optimization Libraries:** I contributed to the exploration of an optimization scheme using the OSQP library to replace the existing optimization library on the embedded platform. By participating in the evaluation of solvers like OOQP and CVXGEN, I helped analyze their performance and applicability, supporting system optimization efforts.
- **Testing of Real-Time Planning Framework:** I supported the development and testing of a real-time path planning framework, validating its performance across various real-world road scenarios to confirm its ability to generate stable and safe navigation paths at intersections.

Results
======
Through collaborative efforts with the team, I made modest contributions to enhancing the path planning capabilities of the L2 autonomous driving system in intersection scenarios. The developed algorithm performed well in terms of real-time performance, safety, and smoothness, as validated through real-world road tests, providing some technical support to the team’s autonomous driving solutions.

