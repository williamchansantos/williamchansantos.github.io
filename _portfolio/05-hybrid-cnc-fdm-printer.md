---
title: "Autonomous Hybrid CNC/FDM Printer"
excerpt: "Capstone design project with LECS Energy, University of Miami · August 2025–May 2026<br/>A hybrid additive/subtractive machine that prints a part, finishes its surfaces, clears the build plate, and starts the next print without human intervention.<br/><img src='/images/portfolio/hybrid-printer/system-overview.png' alt='Hybrid CNC/FDM printer system' style='max-width:420px;width:100%;margin-top:0.5em'>"
collection: portfolio
permalink: /portfolio/hybrid-cnc-fdm-printer/
---

**University of Miami capstone design project, in partnership with LECS Energy** · August 2025–May 2026

<figure>
  <img src="/images/portfolio/hybrid-printer/system-overview.png" alt="Annotated hybrid printer system" style="max-width:480px">
  <figcaption>The full system: FDM printer with a subtractive mount, Dremel finishing tool on a linear actuator, part ramp, air compressor, and LIMS electronics boxes on a mobility cart.</figcaption>
</figure>

We built a hybrid additive/subtractive manufacturing system that prints a part, smooths its surfaces, clears it from the build plate, and starts a new print with no human intervention.

* **Finishing tool:** designed the housing for a deployable Dremel-based surface-finishing tool mounted on a linear actuator, and integrated its drive electronics: polarized relays for the actuator and a MOSFET for Dremel motor speed control.
* **Tool swap:** implemented a stepper-motor-driven mechanism that switches between surface smoothing and drilling for hole tolerances.
* **Controls:** established communication between a Raspberry Pi and an Arduino running CAM-generated toolpaths through LECS Energy's Learning Integrated Manufacturing System (LIMS).

<figure>
  <video src="/images/portfolio/hybrid-printer/printer-running.mp4" poster="/images/portfolio/hybrid-printer/printer-running-poster.jpg" controls muted loop playsinline preload="metadata" style="width:100%;max-width:720px"></video>
  <figcaption>The printer in operation.</figcaption>
</figure>

<figure>
  <img src="/images/portfolio/hybrid-printer/workflow.png" alt="Automated print and post-processing workflow" style="max-width:220px">
  <figcaption>Automated loop: clean up, print, smooth surfaces, tool swap, continue post-processing, and remove the part, then start again.</figcaption>
</figure>

<figure>
  <img src="/images/portfolio/hybrid-printer/electronics.jpg" alt="LIMS electronics enclosure" style="max-width:420px">
  <figcaption>Electronics enclosure for the LIMS control system.</figcaption>
</figure>
