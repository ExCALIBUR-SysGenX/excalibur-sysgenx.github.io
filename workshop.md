---
layout: page
title: Online Workshop - Scientific machine learning and Model order reduction for partial differential equations
---

Topics include computational fluid dynamics, model order reduction, neural networks and numerical PDEs, port-Hamiltonian systems and scientific machine learning with application to engineering and industrial problems.

## Schedule

### Day 1: 15 September 13:00-17:00

- 13:00 - 13:15: Garth Wells, University of Cambridge: Opening statement
- 13:15 - 14:00: Gianluigi Rozza, Scuola Internazionale Superiore di Studi Avanzati, Trieste: Reduced Order Modelling in Computational Fluid Dynamics: state of the art, challenges and perspectives
- 14:00 - 14:45: Mario Ohlberger, Westfälische Wilhelms-Universität, Münster
- 14:45 - 15:15: Break
- 15:15 - 16:00: Urban Fasel, Imperial College, London: Robust Model Discovery with SINDy and Ensemble Learning
- 16:00 - 16:45: Zhiqiang Cai, Purdue University: Least-Squares Neural Network (LSNN) Method for Scalar Hyperbolic Conservation Laws

### Day 2: 22 September 13:00-16:30

- 13:00 - 13:15: Introduction
- 13:15 - 14:00: Volker Mehrmann, Technische Universität Berlin: Model reduction  for port-Hamiltonian systems arising in fluid dynamics
- 14:00 - 14:45: Dirk Hartmann, Siemens: Executable Digital Twins – Harnessing model order reduction to integrate the digital and real world
- 14:45 - 15:15: Break
- 15:15 - 16:00: Francesco Ballarin, Università Cattolica del Sacro Cuore, Brescia
- 16:00 - 16:30: Closing remarks

All times in British Summer Time (GMT + 1) zone.

## Topics and Abstracts

### Gianluigi Rozza: Reduced Order Modelling in Computational Fluid Dynamics: state of the art, challenges and perspectives

We provide the state of the art of Reduced Order Methods (ROM) for parametric Partial Differential Equations (PDEs), and we focus on some perspectives in their current trends and developments, with a special interest in parametric problems arising in offline-online Computational Fluid Dynamics (CFD). Recent developments involve a better integration of emerging topics with model reduction, such as high performance computing (HPC), uncertainty quantification (UQ), data science (DS), machine learning (ML) in a data driven perspective, in order to allow a better exploitation of digital twins. All the previous aspects are quite relevant -- and often challenging —  when well integrated also in CFD problems, including turbulence, to focus on real time simulations for complex parametric industrial, environmental and biomedical flows, or even in a flow control/inverse problems setting with data assimilation. Crucial aspects to be addressed are related with uniqueness, stability, accuracy, as well as reliability of solutions. Some model problems will be illustrated by focusing on few benchmark study cases, for example on fluid-structure interaction problems and/or on shape optimisation, applied to some industrial and applied science problems of interest.

### Urban Fasel: Robust Model Discovery with SINDy and Ensemble Learning

The sparse identification of nonlinear dynamics (SINDy) algorithm can identify dynamical system models purely from data. In this talk, I will present recent work on extending the SINDy algorithm using ensemble learning to identify interpretable and generalizable models in the low-data and high-noise limit. We apply the ensemble-SINDy (E-SINDy) algorithm to a range of challenging synthetic and real-world data sets and demonstrate substantial improvements to the accuracy and robustness of model discovery from noisy and limited data. E-SINDy is computationally efficient, with similar scaling as standard SINDy. We show that E-SINDy can perform efficient uncertainty estimation and probabilistic forecasts, compared to expensive Bayesian uncertainty quantification methods via MCMC. Finally, we show that ensemble statistics from E-SINDy can be used for active learning and improved model predictive control.

### Zhiqiang Cai: Least-Squares Neural Network (LSNN) Method for Scalar Hyperbolic Conservation Laws

Solutions of nonlinear scalar hyperbolic conservation laws (HCLs) are often discontinuous due to shock formation; moreover, locations of shocks are a priori unknown. This presents a great challenge for traditional numerical methods because most of them are based on continuous or discontinuous piecewise polynomials on fixed meshes.

As an alternative, by employing a new class of approximating functions, neural network (NN), recently we proposed the least-squares neural network (LSNN) method for solving HCLs. The LSNN method shows a great potential to sharply capture shock without oscillation or smearing; moreover, its degrees of freedom are much less than those of mesh-based methods. Nevertheless, current iterative solvers for the LSNN discretization are computationally intensive and complicated.

### Volker Mehrmann: Model reduction  for port-Hamiltonian systems arising in fluid dynamics

We show how to design model order reduction techniques for systems with port-Hamiltonian structure arising in the discretization of problems from fluid dyanmics. We describe the available techniques and how they can be modified to preserve the port-Hamiltonian structure and at the same time handle the physical conservation laws, like conservation of mass and momentum, in the reduced model.

Besides these challenges we also discuss how reduced models can be generated purely from data. The performance of the methods is illustrated for benchmark examples originating from semi-discretized flow problems, acoustic fields in gas networks, and mechanical multibody systems.

### Dirk Hartmann: Executable Digital Twins – Harnessing model order reduction to integrate the digital and real world

As the complexity of our world continues to surge, digital twins, seamlessly interfacing the physical and digital spheres, are emerging as crucial decision-making tools for complex systems. This presentation explores the transformative concept of the 'executable digital twin', a self-contained and executable model encapsulating specific behaviors within a defined context.

We will place particular emphasis on the role of non-intrusive model order reduction technology. This technology enables the generation of reduced, manageable models without compromising the essential features of the original system, thereby enhancing computational efficiency, and facilitating real-time execution. In this talk, we will not limit our focus to model order reduction technology but will consider a multitude of technologies required in the complete industrial workflow of generating and operating an 'executable digital twin'. We will cover key concepts such as the design of experiments for data generation, state estimation, calibration, as well as hybrid physics- and data-driven models.

The potential of an executable digital twin will be illustrated with selected real-world examples – from virtual thermal sensors in electric machines to optimal control of manufacturing processes.

## Registration

[Registration](https://www.eventbrite.co.uk/e/666842954227) is required to access the Zoom Webinar

## Organisers

Garth Wells, Chris Richardson, [Nirav Shah](mailto:nvs31@cam.ac.uk) (University of Cambridge)
