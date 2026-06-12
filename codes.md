---
layout: archive
title: "Codes"
permalink: /codes/
author_profile: true
---

Here you can find the source code for my projects and research. 

## [Project Name 1](https://github.com/RodrigoZelada/How-to-insulate-a-pipe)
Codes used to obtain the results in the article F. Caubet, C. Conca, M. Dambrine, and R. Zelada, “Shape Optimization with Ventcel Transmission Condition: Application to the Design of a Heat Exchanger,” SIAM J. Sci. Comput., vol. 48, no. 2,
B113–B140, 2026, issn: 1064-8275,1095-7197. doi: 10.1137/25M1751360
I use different softwares: FreeFem++ to solve the classic FEM equations, C++ to solve the non-standard equations based on our in-house Nitsche extended FEM, petsc for the linear algebra methods, mmg for mesh adaptation, meshdist and advect for the signed distance, and the null-space algorithm for the optimization problem.

## [Project Name 2](https://github.com/RodrigoZelada/HeatExchanger)
F. Caubet, C. Conca, M. Dambrine, and R. Zelada, “How to insulate a pipe?” J. Optim. Theory Appl.,
vol. 207, no. 3, Paper No. 46, 41, 2025, issn: 0022-3239,1573-2878. doi: 10.1007/s10957-025-02782-6
I use different softwares: FreeFem++ to solve the classic FEM equations, C++ to solve the non-standard equations based on our in-house Nitsche extended FEM, petsc for the linear algebra methods, mmg for mesh adaptation, meshdist and advect for the signed distance, and the null-space algorithm for the optimization problem.

I have also implemented the spectral finite element method (in quadrilaterals) to solve the acoustic and elastic wave transient equation. I am actually implementing different Kalman Filter methods.

I hope that after finishing my postdoc, I will have enough time to clean my codes, even the ones that are public in my github and get better versions, and make the public the ones that I am working on it. 