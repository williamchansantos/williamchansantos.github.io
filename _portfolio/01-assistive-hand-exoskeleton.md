---
title: "Assistive Hand Exoskeleton for Brachial Plexus Injury"
excerpt: "Robotics and Mechatronics Laboratory, University of Miami · August 2026–present<br/>A hand exoskeleton that restores finger flexion and extension. We compare existing exoskeleton designs in simulation and with physical prototypes to choose the best approach, and pair the device with a gaze-based interface that predicts the grasp the user needs.<br/><img src='/images/portfolio/hand-exoskeleton/finger-module-render.jpg' alt='Render of a cable-driven finger module on a hand' style='max-width:420px;width:100%;margin-top:0.5em'>"
collection: portfolio
permalink: /portfolio/assistive-hand-exoskeleton/
---

**Robotics and Mechatronics Laboratory, University of Miami** · Graduate Researcher · August 2026–present

<figure>
  <img src="/images/portfolio/hand-exoskeleton/finger-module-render.jpg" alt="Render of a cable-driven finger module on a hand" style="max-width:640px">
  <figcaption>Concept render of a cable-driven finger module.</figcaption>
</figure>

I lead the design and manufacturing of an assistive hand exoskeleton for patients with brachial plexus injury (BPI), which damages the nerves running from the spinal cord down to the hand. The device drives finger flexion and extension from the back of the hand and uses force sensing to hold objects securely.

Many hand exoskeleton designs have been published, but they are rarely compared under the same conditions. We compare existing designs side by side, first in simulation and then with physical prototypes, and use the results to choose the best approach for our own device.

## What I am working on

* **Simulation test bed:** a common simulation that models cable-driven and rigid-linkage designs on the same standard finger, so their joint range of motion, mechanical advantage and force transmission can be compared directly.
* **Physical prototypes:** finger prototypes of the best-performing designs for bench testing, including a lead-screw linear actuator with Arduino control for the cable-driven design.
* **Test setup:** a phantom finger and motion tracking markers for repeatable measurements, with metrics informed by clinicians and patients.
* **Intent prediction:** a gaze-based interface that identifies the object the user is looking at and the grasp it requires. I am exploring a CNN-based detector for object identification and a recurrent or transformer model for grasp prediction.

<figure>
  <img src="/images/portfolio/hand-exoskeleton/actuator-cad.jpg" alt="Linear actuator CAD model" style="max-width:640px">
  <figcaption>CAD model of a linear actuator module.</figcaption>
</figure>

<figure>
  <img src="/images/portfolio/hand-exoskeleton/gaze-hand-tracking.jpg" alt="Head-worn camera recording with eye gaze and hand tracking overlays" style="max-width:760px">
  <figcaption>Recording for the intent prediction interface: head-worn camera video with eye gaze (magenta) and hand tracking overlaid.</figcaption>
</figure>

**Outputs:** poster at the [University of Miami College of Engineering Research Symposium](/talks/2026-10-01-um-coe-exoskeleton-benchmark) (October 2026).

*This work is ongoing and not published yet, so this page is an overview. Some design details and results are left out, and I am happy to discuss them.*
