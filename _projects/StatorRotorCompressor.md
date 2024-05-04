---
layout: page
title: Stator-Rotor Compressor Simulation
description: Computational Fluid Dynamics project performed during my exchange at EPFL.
img: assets/img/RecirculationOnStator.png
importance: 2
category: 2021
related_publications:
---

The present report has the goal of investigating stator-rotor 2D interaction in an axial compressor. Axial compressors consist in a series of stages, composed of rotor and stator, in order to achieve high pressure in a gradual way. The kinetic energy of the fluid (usually air) is increased by the rotor, while in the stator the static pressure increases at the expense of the fluid velocity. In the field of turbomachinery, axial compressors are widely used in power generation or in the aeronautical field. The study is focused on the analysis of the evolution of velocity and pressure fields through a rotor-stator stage of a compressor. In particular, it is evaluated whether the compressor fulfills its compressing task by investigating the pressure difference over the rotor-stator stage.

The method used for the analysis of the compressor stage involves the use of different resources. The software SpaceClaim has been used to produce the 2D geometry. Due to the upward rotor movement, increasing the kinetic energy of the fluid, a sliding mesh is needed for the rotor region to simulate the compressor stage. The final mesh is obtained using a convergence study based on convergence of the pressure difference as well as the outlet velocity of the rotor-stator stage. A snapshot of the converged solution from ANSYS Fluent is finally used to analyse compression of the rotor-stator stage presented in this report. The overall goal of this work is to determine if the selected geometry is able to compress the flow and to investigate how the compression process takes place.


<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/NFS_Project.pdf" width="1000" height="1000" type="application/pdf"></object>
