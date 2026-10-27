---
title: "Skin Deformation in a NACA 4412 Airfoil"
excerpt: "MAE 362 course project, University of Miami<br/>A COMSOL fluid–structure interaction study of how airspeed and skin thickness drive stress and deformation in an aluminum airfoil skin.<br/><img src='/images/projects/naca4412-fsi/displacement.png' alt='Displacement of a NACA 4412 airfoil skin' style='max-width:420px;width:100%;margin-top:0.5em'>"
collection: projects
permalink: /projects/naca4412-airfoil-fsi/
---

**MAE 362: Computer Analysis of Mechanical and Aerospace Problems** · University of Miami · Dr. Giacomo Po
Team project with Nikita Korchnoy

<figure>
  <img src="/images/projects/naca4412-fsi/displacement.png" alt="Displacement magnitude of the airfoil skin" style="max-width:640px">
  <figcaption>Displacement of the aluminum skin under airflow. The trailing edge deforms the most.</figcaption>
</figure>

## Overview

How thin can a wing skin be before airflow loads deform it too much? To explore that trade-off between weight and stiffness, we built a 2D fluid–structure interaction (FSI) model of a NACA 4412 airfoil in COMSOL Multiphysics. We then ran a parametric sweep over **inlet airspeed** and **skin thickness** to map how von Mises stress and displacement in the skin change.

## What we did

* **Geometry:** imported NACA 4412 coordinate data into COMSOL and built the airfoil as a polygon solid. The aluminum skin was modeled by offsetting the profile inward, and the airfoil was placed inside a rectangular air domain.
* **Physics:** derived the weak forms for plane-stress linear elasticity in the skin and steady laminar Navier–Stokes flow in the air, then coupled them with one-way fluid loading on the structure.
* **Boundary conditions:** the inner skin was fixed to represent internal spars, the inlet used a velocity parameter *V*, the outlet was set to zero gauge pressure, and the walls used a slip condition.
* **Mesh and study:** meshed the domain with refinement at the leading and trailing edges, then ran a two-parameter sweep of airspeed and skin thickness.

I contributed half of the COMSOL modeling and most of the written report.

<figure>
  <img src="/images/projects/naca4412-fsi/mesh.png" alt="Mesh with refinement around the airfoil" style="max-width:640px">
  <figcaption>Triangular mesh, refined around the leading and trailing edges.</figcaption>
</figure>

## Results

<figure>
  <img src="/images/projects/naca4412-fsi/velocity.png" alt="Velocity magnitude around the airfoil" style="max-width:640px">
  <figcaption>Velocity magnitude at 50 m/s. Air accelerates over the upper surface and stagnates at the leading edge.</figcaption>
</figure>

<figure>
  <img src="/images/projects/naca4412-fsi/pressure.png" alt="Pressure field around the airfoil" style="max-width:640px">
  <figcaption>Pressure field. Low pressure above the airfoil and high pressure at the leading edge produce lift.</figcaption>
</figure>

<figure>
  <img src="/images/projects/naca4412-fsi/stress-surface.png" alt="von Mises stress as a function of airspeed and skin thickness" style="max-width:640px">
  <figcaption>Peak von Mises stress across the sweep of airspeed and skin thickness.</figcaption>
</figure>

Stress rises sharply as the skin gets thinner and the flow gets faster. The trailing edge deforms the most, since it is farthest from the internal supports and has the least material. At 250 m/s with a 0.04 m skin, peak displacement was about 0.12 mm. A map like this one can be used to choose the thinnest skin that still meets a target safety factor at a given speed, saving weight and cost.

## Limitations and next steps

The model is deliberately simplified. It is 2D with plane stress, assumes incompressible laminar flow, and couples the physics in one direction only. At the thinnest skins and highest speeds, the predicted stresses exceed aluminum's yield strength, which is beyond what a linear-elastic model can describe. Natural extensions include compressible or turbulent flow for the higher speeds, two-way coupling, and a 3D wing with realistic spars and ribs.

**Tools:** COMSOL Multiphysics (Laminar Flow, Solid Mechanics, FSI), finite element analysis, parametric studies
