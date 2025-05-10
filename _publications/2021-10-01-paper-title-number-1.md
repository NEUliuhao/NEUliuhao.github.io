---
title: "Multi-objective Collaborative Optimization Algorithm for Heterogeneous Cooperative Tasks Based on Conflict Resolution"
collection: publications
category: conferences
permalink: /publication/2021-10-01-paper-title-number-1
excerpt: 'This paper is about multi-agent task allocation.'
date: 2021-10-01
venue: 'Proceedings of 2021 International Conference on Autonomous Unmanned Systems (ICAUS 2021) '
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: '../files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Zhang, X., Liu, H., Xue, L., Li, X., Guo, W., Yu, S., ... & Xu, H. (2021, September). Multi-objective Collaborative Optimization Algorithm for Heterogeneous Cooperative Tasks Based on Conflict Resolution. In International Conference on Autonomous Unmanned Systems (pp. 2548-2557). Singapore: Springer Singapore.'
status: 'published'
---
This paper presents a novel algorithm for multi-objective task assignment in air–ground cooperative missions, focusing on the challenges of heterogeneous agents and task conflicts. The proposed algorithm, called Heterogeneous Conflict Resolution Multi-tasking Optimization (HCRMO), builds upon NSGA-III (Non-dominated Sorting Genetic Algorithm III) and incorporates two key modules:

1. Conflict-Free Minimum Solution Space: This limits the search space for task-agent assignments, ensuring that solutions meet task requirements while avoiding agent conflicts. It improves the efficiency of agent allocation by eliminating redundant allocations.

2. Task-Agent Conflict Resolution Module (TCCRM): This module quantifies potential conflicts between agents and tasks, helping to minimize the impact of conflicts in the task assignment process. It ensures that the tasks and agents are allocated in a way that avoids timing and spatial conflicts.

The algorithm optimizes for three objectives:

- Total driving distance: Minimizing the total distance traveled by all agents, which directly reduces fuel consumption.

- Undesirable distance: Avoiding undesirable areas on the map that agents must cross during tasks.

- Agent utilization: Ensuring that agents are used efficiently across tasks.

The paper demonstrates the effectiveness of the HCRMO algorithm through simulation experiments, comparing it with traditional NSGA-III and other methods. The results show that HCRMO significantly improves task allocation efficiency and convergence speed, making it six times faster than traditional approaches.
