---
layout: page
title: Online Workshop - Scientific machine learning and Model order reduction for partial differential equations
---

This workshop presents series of talks focused on developments in scientific machine learning and model order reduction with application to engineering and industrial problems. The topics include Reduced order modelling in computational fluid dynamics, Sparse identification of nonlinear dynamics method and ensemble learning, Least-squares neural network method, Model reduction for port-Hamiltonian systems, Executable digital twins and Reduced order models for Navier-Stokes equation.

## Schedule

### Day 1: 15 September 13:00-17:00

- 13:00 - 13:15: Garth Wells, University of Cambridge: Opening statement
- 13:15 - 14:00: Gianluigi Rozza, Scuola Internazionale Superiore di Studi Avanzati, Trieste: Reduced Order Modelling in Computational Fluid Dynamics: state of the art, challenges and perspectives
- 14:00 - 14:45: Mario Ohlberger, Westfälische Wilhelms-Universität, Münster: Model Reduction and Learning for PDE Constrained Optimization
- 14:45 - 15:15: Break
- 15:15 - 16:00: Urban Fasel, Imperial College, London: Robust Model Discovery with SINDy and Ensemble Learning
- 16:00 - 16:45: Zhiqiang Cai, Purdue University: Least-Squares Neural Network (LSNN) Method for Scalar Hyperbolic Conservation Laws

### Day 2: 22 September 13:00-16:30

- 13:00 - 13:15: Introduction
- 13:15 - 14:00: Volker Mehrmann, Technische Universität Berlin: Model reduction  for port-Hamiltonian systems arising in fluid dynamics
- 14:00 - 14:45: Dirk Hartmann, Siemens: Executable Digital Twins – Harnessing model order reduction to integrate the digital and real world
- 14:45 - 15:15: Break
- 15:15 - 16:00: Francesco Ballarin, Università Cattolica del Sacro Cuore, Brescia: Reduced order models for evolve-filter-relax regularization of Navier-Stokes equations
- 16:00 - 16:30: Closing remarks

All times in British Summer Time (GMT + 1) zone.

## Topics and Abstracts

### Gianluigi Rozza: Reduced Order Modelling in Computational Fluid Dynamics: state of the art, challenges and perspectives

We provide the state of the art of Reduced Order Methods (ROM) for parametric Partial Differential Equations (PDEs), and we focus on some perspectives in their current trends and developments, with a special interest in parametric problems arising in offline-online Computational Fluid Dynamics (CFD). Recent developments involve a better integration of emerging topics with model reduction, such as high performance computing (HPC), uncertainty quantification (UQ), data science (DS), machine learning (ML) in a data driven perspective, in order to allow a better exploitation of digital twins. All the previous aspects are quite relevant -- and often challenging —  when well integrated also in CFD problems, including turbulence, to focus on real time simulations for complex parametric industrial, environmental and biomedical flows, or even in a flow control/inverse problems setting with data assimilation. Crucial aspects to be addressed are related with uniqueness, stability, accuracy, as well as reliability of solutions. Some model problems will be illustrated by focusing on few benchmark study cases, for example on fluid-structure interaction problems and/or on shape optimisation, applied to some industrial and applied science problems of interest.

### Mario Ohlberger: Model Reduction and Learning for PDE Constrained Optimization

Model order reduction for parameterized systems has gained a lot of attention in the last two decades. In this talk we will focus on projection based model order reduction and their efficient application to solve large scale PDE constrained optimization problems. We will discuss learning strategies, such as adaptive enrichment as well as a combination of reduced order models with machine learning approaches in the contest of time dependent problems. Concepts of rigorous certification and convergence will be presented, as well as numerical experiments that demonstrate the efficiency of the proposed approaches.

### Urban Fasel: Robust Model Discovery with SINDy and Ensemble Learning

The sparse identification of nonlinear dynamics (SINDy) algorithm can identify dynamical system models purely from data. In this talk, I will present recent work on extending the SINDy algorithm using ensemble learning to identify interpretable and generalizable models in the low-data and high-noise limit. We apply the ensemble-SINDy (E-SINDy) algorithm to a range of challenging synthetic and real-world data sets and demonstrate substantial improvements to the accuracy and robustness of model discovery from noisy and limited data. E-SINDy is computationally efficient, with similar scaling as standard SINDy. We show that E-SINDy can perform efficient uncertainty estimation and probabilistic forecasts, compared to expensive Bayesian uncertainty quantification methods via MCMC. Finally, we show that ensemble statistics from E-SINDy can be used for active learning and improved model predictive control.

### Zhiqiang Cai: Least-Squares Neural Network (LSNN) Method for Scalar Hyperbolic Conservation Laws

Solutions of nonlinear scalar hyperbolic conservation laws (HCLs) are often discontinuous due to shock formation; moreover, locations of shocks are a priori unknown. This presents a great challenge for traditional numerical methods because most of them are based on continuous or discontinuous piecewise polynomials on fixed meshes.

As an alternative, by employing a new class of approximating functions, neural network (NN), recently we proposed the least-squares neural network (LSNN) method for solving HCLs. The LSNN method shows a great potential to sharply capture shock without oscillation or smearing; moreover, its degrees of freedom are much less than those of mesh-based methods. Nevertheless, current iterative solvers for the LSNN discretization are computationally intensive and complicated.

### Volker Mehrmann: Model reduction for port-Hamiltonian systems arising in fluid dynamics

We show how to design model order reduction techniques for systems with port-Hamiltonian structure arising in the discretization of problems from fluid dyanmics. We describe the available techniques and how they can be modified to preserve the port-Hamiltonian structure and at the same time handle the physical conservation laws, like conservation of mass and momentum, in the reduced model.

Besides these challenges we also discuss how reduced models can be generated purely from data. The performance of the methods is illustrated for benchmark examples originating from semi-discretized flow problems, acoustic fields in gas networks, and mechanical multibody systems.

### Dirk Hartmann: Executable Digital Twins – Harnessing model order reduction to integrate the digital and real world

As the complexity of our world continues to surge, digital twins, seamlessly interfacing the physical and digital spheres, are emerging as crucial decision-making tools for complex systems. This presentation explores the transformative concept of the 'executable digital twin', a self-contained and executable model encapsulating specific behaviors within a defined context.

We will place particular emphasis on the role of non-intrusive model order reduction technology. This technology enables the generation of reduced, manageable models without compromising the essential features of the original system, thereby enhancing computational efficiency, and facilitating real-time execution. In this talk, we will not limit our focus to model order reduction technology but will consider a multitude of technologies required in the complete industrial workflow of generating and operating an 'executable digital twin'. We will cover key concepts such as the design of experiments for data generation, state estimation, calibration, as well as hybrid physics- and data-driven models.

The potential of an executable digital twin will be illustrated with selected real-world examples – from virtual thermal sensors in electric machines to optimal control of manufacturing processes.

### Francesco Ballarin: Reduced order models for evolve-filter-relax regularization of Navier-Stokes equations

Numerical stabilization is often used to alleviate the spurious oscillations generally produced by full order models (FOMs) in under-resolved or marginally-resolved simulations of convection-dominated flows modelled by the incompressible Navier-Stokes equations. However, when dealing with reduced order models (ROMs) of convection-dominated, marginally-resolved flows, the role of numerical stabilization is still not well understood.

In the first part of this presentation, based on [1], we investigate the FOM-ROM consistency, i.e., whether the numerical stabilization is beneficial both at the FOM and the ROM level. As a numerical stabilization strategy, we focus on the evolve-filter-relax (EFR) regularization algorithm, which centers around spatial filtering.

In the second part of this presentation, related to [2], we apply the resulting ROM to a case of feedback control, where the forcing term acts as a feedback on the Navier-Stokes equations in order to reach a desired goal, measured as a distance between the numerical solution and a desired velocity.

In the final part of the presentation we will introduce a novel ROM, based on approximate deconvolution [3].

Results on relevant test cases in fluid dynamics will be discussed, alongside their implementation in RBniCSx.

[1] M. Strazzullo, M. Girfoglio, F. Ballarin, T. Iliescu, G. Rozza. Consistency of the full and reduced order models for evolve-filter-relax regularization of convection-dominated, marginally-resolved flows. International Journal for Numerical Methods in Engineering, 123(14):3148–3178, 2022.

[2] M. Strazzullo, F. Ballarin, T. Iliescu, C. Canuto. New feedback control and adaptive evolve-filter-relax regularization for the Navier-Stokes equations in the convection-dominated regime. Submitted, 2023. arXiv:2307.00675.

[3] A. Sanfilippo, I. Moore, F. Ballarin, T. Iliescu. Approximate deconvolution Leray reduced order model for convection-dominated flows. Submitted, 2023. arXiv:2307.10817.

## Registration

[Registration](https://www.eventbrite.co.uk/e/666842954227) is required to access the Zoom Webinar

## Organisers

Garth Wells, Chris Richardson, [Nirav Shah](mailto:nvs31@cam.ac.uk) (University of Cambridge)
