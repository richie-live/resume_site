---
title: "Time-optimal Attitude Planning for Spacecraft with Movable Parts Using Second Order Cone Programming"
description: "Aerospace Science Technology: Major Revision"
date: 2023-08-01T03:49:15Z
image: cover.png
math: 
license: 
hidden: false
comments: true
draft: true
categories:
    - 论文
tags:
    - AST
    - Major Revision
---

## Introduction

The objective of this paper is to plan a time-optimal attitude trajectory
in a relatively short time for spacecraft with movable parts under complex
pointing constraints. The constrained attitude planning problem is first established, then the constraints on attitude maneuvers are described. The
time-optimal attitude planning for rigid spacecraft body is decoupled into
geometric level and dynamic level through the addition of the path scalar.
To obtain a given safe path in quaternion space, RRT*-Smart path planning and spherical and quadrangle (SQUAD) interpolation are carried out
at the geometric level. The time-optimal parameterization for a given path
is reformulated as a second order cone programming (SOCP) problem at
the dynamic level through a nonlinear change in variables and the addition
of various convexity-preserving extensions. In order to overcome the issue
of high system dimension caused by the movable parts, a decoupled attitude planning method is designed to generate the quaternion trajectory of
the spacecraft body and the rotation angle trajectory of the movable parts
respectively. In comparison to GPOPS, the simulation results demonstrate
that the proposed method can plan a suboptimal solution in milliseconds.
Furthermore, the performance indicator for energy consumption is better.

## Simulation Results

![Alt text](traj.png)
![Alt text](path_compare.png)
