---
layout: page
title: Predictive Planning
description: Studying planning and model-based reinforcement learning approaches for dynamic environments
img: /assets/img/CIAO.png
importance: 3
---

Robots have been operating in dynamic environments and shared workspaces for decades. Most optimization based motion planning methods, however, do not consider the movement of other agents, e.g. humans or other robots, and therefore do not guarantee collision avoidance in such scenarios. 
In this line of research I am interested in developing novel local planning techniques for dynamic environments, considering also environmental contextual cues and human motion predictions. Some of recent approaches that I worked with are: Convex Inner ApprOximation (CIAO) for model predictive control, Informed Information Theoretics Model Predictive Control (IIT-MPC).


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    <p  align="center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/schoelsIFAC2020.png' | relative_url }}" alt="" title="CIAO*"/> <br>
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/CIAO.png' | relative_url }}" alt="" title="CIAO"/><br>
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/kusumotoPalmieriICRA2019.png' | relative_url }}" alt="" title="IITMPC"/>
        </p>
    </div>
</div>
<div class="caption">
    Example paths generated respectively with CIAO*, CIAO and IITMPC.
</div>
