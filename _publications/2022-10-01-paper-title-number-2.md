---
title: "A bounded near-bottom cruise trajectory planning algorithm for underwater vehicles"
collection: publications
category: manuscripts
permalink: /publication/2022-10-01-paper-title-number-2
excerpt: 'This paper is about the large scale path planning algorithm for AUV.'
date: 2022-10-01
venue: 'Journal of Marine Science and Engineering'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://neuliuhao.github.io/files/under_water.pdf'
citation: 'Ru, J., Yu, H., Liu, H., Liu, J., Zhang, X., & Xu, H. (2022). A bounded near-bottom cruise trajectory planning algorithm for underwater vehicles. Journal of Marine Science and Engineering, 11(1), 7.'
---

This paper introduces a Bounded Near-Bottom Cruise Trajectory Planning Algorithm for autonomous underwater vehicles (AUVs), focusing on the challenges of navigating near the ocean floor. The study addresses the need for efficient and safe trajectory planning, especially in complex underwater environments, which may include large-scale maps and terrain features like ridges. The paper presents a ridge-based A* (RA*) algorithm for AUVs that integrates safety constraints and a parallel computing framework to enhance performance.

**Key Contributions:**

1. Trajectory Planning for AUVs: The study targets the near-bottom trajectory planning problem, emphasizing safety, efficiency, and adaptability in real-world underwater conditions.

2. Safety Map Construction: The paper introduces a new safety map construction method to ensure that the AUV maintains a safe distance from underwater obstacles. Different types of safety maps (vertical, horizontal, spherical) are proposed for various scenarios.

3. RA Algorithm*: The proposed algorithm, RA*, combines bounded trajectory planning with terrain considerations. It prioritizes traversal of ocean ridges to minimize detection and improve mission success.

4. Parallel Computing Framework: The algorithm includes a map compression and parallel computing strategy (MCPC) to handle large-scale maps efficiently. This approach segments maps for parallel processing, significantly improving computational speed.

**Experimentation:**

- The paper presents a variety of experiments, including:

- Map Generation: Using digital elevation models (DEM) to create terrain maps.

- Safety Map Evaluation: Comparing the effectiveness of different safety map types (vertical, horizontal, and spherical).

- RA Performance*: The RA* algorithm's performance is tested on large-scale maps (e.g., 5000x5000), showing its ability to efficiently plan trajectories while traversing ridge features.

- Computational Efficiency: The RA* algorithm with MCPC was compared to traditional A* and other methods, demonstrating its superior computational efficiency, especially in large-scale applications.

**Conclusion:**

The RA* algorithm provides an effective solution for trajectory planning in underwater environments, especially for AUVs performing near-bottom missions. The integration of safety distance constraints and parallel computation ensures that the algorithm is both efficient and practical for real-world applications.