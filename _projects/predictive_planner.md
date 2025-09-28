---
layout: page
title: "Predictive Planner for Autonomous Driving with Consistency Models"
# description: A brief description of Project 1.
img: /assets/img/predictive_planner/workflow.png
importance: 1
category: work
# related_publications: true
---

<!-- # Academic Project Page -->

<div style="text-align: center;">
  Anjian Li<sup>1</sup><sup>2</sup>, Sangjae Bae<sup>1</sup>, David Isele<sup>1</sup>, Ryne Beeson<sup>2</sup>, and Faizan M. Tariq<sup>1</sup>
</div>

<div style="text-align: center;">
  <sup>1</sup>Honda Research Institute<br>
  <sup>2</sup>Princeton University
</div>

<div style="text-align: center; margin: 20px 0;">
  <a href="https://arxiv.org/abs/2502.08033" style="display: inline-block; padding: 10px 20px; background-color: #333; color: white; border-radius: 20px; text-decoration: none; margin-right: 10px;">
    <i class="fas fa-file-pdf" style="font-size: 0.8em;"></i> Paper
  </a>
  <a href="https://github.com/YOUR_REPO_HERE" style="display: inline-block; padding: 10px 20px; background-color: #333; color: white; border-radius: 20px; text-decoration: none;">
    <i class="fab fa-github" style="font-size: 0.8em;"></i> Code
  </a>
</div>

<div style="text-align: center; margin: 10px 0;">
  <p style="color: #666; font-style: italic; font-size: 0.9em;">
    <i class="fas fa-clock" style="margin-right: 5px;"></i>Code will be published soon!
  </p>
</div>

<!-- <video width="100%" controls autoplay style="margin-top: 20px;">
  <source src="/assets/video/project_1/banner_video.mp4" type="video/mp4">
</video> -->

![First image description](/assets/img/predictive_planner/workflow.png)

## Abstract

Trajectory prediction and planning are essential for autonomous vehicles to navigate safely and efficiently in dynamic environments. Traditional approaches often treat them separately, limiting the ability for interactive planning. While recent diffusion-based generative models have shown promise in multi-agent trajectory generation, their slow sampling is less suitable for high-frequency planning tasks. In this paper, we leverage the consistency model to build a predictive planner that samples from a joint distribution of ego and surrounding agents, conditioned on the ego vehicle's navigational goal. Trained on real-world human driving datasets, our consistency model generates higher-quality trajectories with fewer sampling steps than standard diffusion models, making it more suitable for real-time deployment. To enforce multiple planning constraints simultaneously on the ego trajectory, a novel online guided sampling approach inspired by the Alternating Direction Method of Multipliers (ADMM) is introduced. Evaluated on the Waymo Open Motion Dataset (WOMD), our method enables proactive behavior such as nudging and yielding, and also demonstrates smoother, safer, and more efficient trajectories and satisfaction of multiple constraints under a limited computational budget.

<!-- ## Introduction

![First image description](/assets/img/project_1/carousel1.jpg) -->


## BibTeX

```
@article{li2025predictive,
  title={Predictive Planner for Autonomous Driving with Consistency Models},
  author={Li, Anjian and Bae, Sangjae and Isele, David and Beeson, Ryne and Tariq, Faizan M},
  journal={arXiv preprint arXiv:2502.08033},
  year={2025}
}
```

<!-- ## Footer

XXX -->

