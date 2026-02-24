---
layout: single
permalink: /
title: "Ling Zhang"
author_profile: false
classes: wide
---

<style>
  /* 1. Hide the default page title */
  .page__title { display: none !important; }

  /* 2. Container and Text Alignment */
  .profile-container {
    display: flex;
    align-items: center;
    margin-bottom: 25px;
  }

  .profile-text {
    display: flex;
    flex-direction: column;
    justify-content: center; /* Vertically centers the text against the photo */
    height: 100px; /* Matches your 100px image height */
    line-height: 1.2;
  }

  /* 3. Color Logic for Day/Night Mode */
  .profile-name {
    margin: 0; 
    padding: 0; 
    border: none; 
    font-size: 1.4em; 
    color: #000000; /* Default black for Day mode */
  }

  .profile-title {
    font-size: 0.95em; 
    font-weight: 600; 
    color: #333333; /* Dark grey for Day mode */
  }

  /* Automatically switch colors if the user is in Dark Mode */
  @media (prefers-color-scheme: dark) {
    .profile-name { color: #ffffff !important; }
    .profile-title { color: #eeeeee !important; }
    .profile-links a { color: #4fb3ff !important; }
  }

  /* 4. Link Styling */
  .profile-links {
    font-size: 0.85em;
    margin-top: 5px;
  }
  .profile-links a {
    margin-right: 12px;
    text-decoration: none;
  }
</style>

<div style="display: flex; align-items: center; margin-bottom: 25px;">
  <!-- Profile Photo (100px) -->
  <img src="/images/profile.jpg" style="width: 100px; height: 100px; border-radius: 50%; margin-right: 20px; object-fit: cover; border: 1px solid #eee;">
  
  <!-- Text Container (Matched to 100px height) -->
  <div style="display: flex; flex-direction: column; justify-content: center; height: 100px; line-height: 1.2;">
    
    <!-- Name (Using your requested style, set to font-weight: normal) -->
    <h2 class="adaptive-text" style="margin: 0; padding: 0; border: none; font-size: 1.5em; font-weight: bold;">
      Ling Zhang
    </h2>
    
    <div class="profile-desc" style="font-size: 1.0em; font-weight: normal;">
      Senior Researcher at Microsoft Research Asia
    </div>

    <div class="profile-links">
      <a href="mailto:zhangling@microsoft.com">
        <i class="fas fa-fw fa-envelope"></i> Email
      </a>
      <a href="https://scholar.google.com/citations?user=JzRpUcMAAAAJ" target="_blank" rel="noopener noreferrer">
        <i class="fas fa-fw fa-graduation-cap"></i> Scholar
      </a>
      <a href="/files/my_cv.pdf" target="_blank" rel="noopener noreferrer" class="btn btn--info" style="margin: 0; padding: 2px 8px; font-size: 0.8em; border-radius: 4px; color: white !important;">
        Download CV
      </a>
    </div>
  </div>
</div>

<hr>

# About Me
I am currently a Senior Researcher at Microsoft Research Asia. I received my PhD in 2024 from the University of Washington, advised by [Prof. Baosen Zhang](https://zhangbaosen.github.io/).
My research focuses on learning-based optimization for power system operations under high renewable penetration and uncertainty.  I develop methods that guarantee hard constraint satisfaction by embedding optimization structures directly into the learning process.  At MSRA, I also explore applying LLMs to large-scale combinatorial optimization (e.g., logistics) and improving their alignment with downstream tasks.

## Selected Publications

### Large Language Models & Combinatorial Optimization
*   **Holdout-Loss-Based Data Selection for LLM Finetuning via In-Context Learning**  
    **L. Zhang**, X. Yang, J. Yu, P. Cheonyoung, M. Lee, L. Song, and J. Bian.  
    *International Conference on Learning Representations (ICLR)*, 2026. (To appear)  
    *Explores principled data curation strategies for improving LLM alignment.*

*   **HeurAgenix: Leveraging LLMs for Solving Complex Combinatorial Optimization Challenges**  
    X. Yang, **L. Zhang**, H. Qian, L. Song, and J. Bian.  
    *arXiv preprint: 2506.15196*, 2025.  
    *Uses LLMs to generate and evolve heuristic programs for large-scale combinatorial optimization.*

### Learning-based Optimization for Power Systems
*   **An Efficient Learning‑based Solver for Two‑stage DC Optimal Power Flow with Feasibility Guarantees**  
    **L. Zhang**, D. Tabas, and B. Zhang.  
    *arXiv preprint: 2304.01409*, 2023.  
    *Introduces a gauge mapping approach to solve two-stage stochastic LP with feasibility guarantees.*

*   **An Iterative Approach to Improving Solution Quality for AC Optimal Power Flow Problems**  
    **L. Zhang** and B. Zhang.  
    *e-Energy '22: Proceedings of the Thirteenth ACM International Conference on Future Energy Systems*, 2022.  
    🏆 **Best Paper Finalist**  
    *Develops a Lagrangian-based warm-start method to improve solution quality in AC-OPF.*

*   **A Convex Neural Network Solver for DCOPF with Generalization Guarantees**  
    **L. Zhang**, Y. Chen, and B. Zhang.  
    *IEEE Transactions on Control of Networked Systems*, 2021.  
    *Leverages duality and KKT conditions to guarantee linear constraint satisfaction in neural solvers.*

My vision is to build reliable AI-driven decision-making for safety-critical systems. As hyperscale AI data centers become coupled with the grid, I am particularly interested in modeling these dynamic systems to develop robust, adaptive operation methods.
