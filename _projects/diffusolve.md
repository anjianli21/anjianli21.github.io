---
layout: page
title: "DiffuSolve: Diffusion-Based Solver for Non-Convex Trajectory Optimization"
# description: A brief description of Project 1.
img: /assets/img/diffusolve/experiment_example.png
importance: 1
category: work
# related_publications: true
---

<!-- # Academic Project Page -->

<div style="text-align: center;">
  Anjian Li, Zihan Ding, Adji Bousso Dieng, Ryne Beeson
</div>

<div style="text-align: center;">
  Princeton University
</div>

<div style="text-align: center; margin: 20px 0;">
  <a href="https://arxiv.org/abs/2403.05571" style="display: inline-block; padding: 10px 20px; background-color: #333; color: white; border-radius: 20px; text-decoration: none; margin-right: 10px;">
    <i class="fas fa-file-pdf" style="font-size: 0.8em;"></i> Paper
  </a>
  <!-- <a href="https://github.com/YOUR_REPO_HERE" style="display: inline-block; padding: 10px 20px; background-color: #333; color: white; border-radius: 20px; text-decoration: none;">
    <i class="fab fa-github" style="font-size: 0.8em;"></i> Code
  </a> -->
</div>

<!-- <video width="100%" controls autoplay style="margin-top: 20px;">
  <source src="/assets/video/project_1/banner_video.mp4" type="video/mp4">
</video> -->

![First image description](/assets/img/diffusolve/workflow.png)

## Abstract

Optimal trajectory design is computationally expensive for nonlinear and high-dimensional dynamical systems. The challenge arises from solving a non-convex optimization problem with multiple local optima, where traditional numerical solvers struggle to find diverse solutions efficiently without appropriate initial guesses. In this paper, we introduce \texttt{DiffuSolve}, a general diffusion model-based solver for non-convex trajectory optimization. An expressive diffusion model is trained on pre-collected locally optimal solutions and efficiently samples initial guesses, which then warm-starts numerical solvers to fine-tune the feasibility and optimality. We also present \texttt{DiffuSolve+}, a novel constrained diffusion model with an additional loss in training that further reduces the problem constraint violations of diffusion samples. Experimental evaluations on three tasks verify the improved robustness, diversity, and a 2x to 11x increase in computational efficiency with our proposed method, which generalizes well to trajectory optimization problems of varying challenges.

<!-- ## Introduction

![First image description](/assets/img/project_1/carousel1.jpg) -->


## BibTeX

```
@article{li2024diffusolve,
  title={Diffusolve: Diffusion-based solver for non-convex trajectory optimization},
  author={Li, Anjian and Ding, Zihan and Dieng, Adji Bousso and Beeson, Ryne},
  journal={arXiv preprint arXiv:2403.05571},
  year={2024}
}
```

<!-- ## Footer

XXX -->

