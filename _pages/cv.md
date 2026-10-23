---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Biomedical Engineering**, University of Miami, Coral Gables, FL, Class of 2027
  * GPA: 4.0
* **B.S. in Mechanical Engineering**, University of Miami, Coral Gables, FL, Class of 2026
  * GPA: 3.99
* **Relevant coursework:** Mechanics of Materials, Mechanical Design, Heat Transfer, Dynamics, System Dynamics, Additive Manufacturing, Automatic Control, Medical Imaging, Neurosensory Engineering, Neurophysiology, Medical Robotics, Regulation of Medical Devices, Neural Networks

Research experience
======
* **August 2026–present: Graduate Researcher**
  * Robotics and Mechatronics Laboratory, University of Miami, Coral Gables, FL
  * Leading the design and manufacturing of an assistive exoskeleton for patients with brachial plexus injury, using actuators on the dorsal side of the finger phalanges for flexion and extension.
  * Implementing a computer-vision human–machine interface for automatic object identification and grasp-type selection, with force sensors to apply the force needed for a secure grasp.
  * Leading the design of a robot-assisted surgery platform for endoscopic spine surgery, including a simulation of the endoscope and tool manipulators to demonstrate the operating workflow.

* **May 2026–August 2026: Researcher**
  * Avila Research Group, Rice University, Houston, TX
  * Developed a wearable bioimpedance cap for monitoring brain hydration in older adults, integrating an analog front end and tetrapolar electrode array for benchtop and human testing.
  * Built a multi-layered finite element human head model in COMSOL with frequency-dependent material properties to optimize stimulation frequency and electrode montage location.
  * Designed and fabricated a tissue-mimicking, multi-layered head phantom with anatomically accurate geometry and layer conductivities, using Blender node-based parametric modeling.
  * Characterized bioimpedance signal behavior under mechanical deformation on hydrogel substrates; developed a Python computer-vision pipeline (OpenCV, NumPy) using HSV color segmentation and contour centroid tracking to automate electrode-displacement monitoring.

* **May 2025–May 2026: Undergraduate Researcher**
  * IMERSE and HAMR labs, Johns Hopkins University, Baltimore, MD (hybrid)
  * Designed a pneumatically actuated soft robotic sphincterotome for bile and pancreatic duct cannulation, reaching a maximum bending angle of 180° (vs. 155° for the conventional device) with full omnidirectional motion.
  * Reduced targeting-task completion time by 58% relative to a conventional sphincterotome in benchtop evaluation.
  * Iterated the design through CAD, finite element analysis, and additive manufacturing; built hyperelastic FEA models to localize the weak points driving burst failure.
  * Developed a Python program (Pandas, NumPy, Matplotlib) implementing Taguchi design-of-experiments methods to guide future parameter optimization.

* **August 2025–May 2026: Capstone Design Project, CNC/FDM Hybrid Printer (LECS Energy partnership)**
  * University of Miami, Coral Gables, FL
  * Built a hybrid additive/subtractive manufacturing system that prints a part, smooths its surfaces, clears it from the build plate, and starts a new print without human intervention.
  * Designed the housing for a deployable Dremel-based finishing tool on a linear actuator and integrated its drive electronics (polarized relays for the actuator, MOSFET for motor speed control); implemented a stepper-driven tool swap between surface smoothing and drilling.
  * Established communication between a Raspberry Pi and Arduino with CAM-generated toolpaths through the Learning Integrated Manufacturing System (LIMS).

* **September 2024–May 2025: Undergraduate Research Assistant**
  * College of Engineering, University of Miami, Coral Gables, FL
  * Led a team of undergraduate students synthesizing high-entropy alloys of different compositions by arc melting; prepared samples for mechanical characterization.
  * Diagnosed and replaced the arc melter's turbomolecular vacuum pump to restore the high-purity vacuum environment required for alloy synthesis.

* **February 2024–August 2024: MakerSpace Undergraduate Research Assistant**
  * College of Engineering, University of Miami, Coral Gables, FL
  * Learned standard operating procedures for equipment including an Instron tensile tester and a Keyence VHX-5000 microscope.
  * Analyzed Ti64 powder used in laser powder bed fusion metal 3D printing using the Microtrac.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Leadership and service
======
* **May 2025–May 2026: Vice President, Pi Tau Sigma** (mechanical engineering honor society), University of Miami
  * Coordinated $7,000 in fundraising to acquire a desktop CNC machine and an FDM 3D printer for engineering students' prototyping and research.
  * Repaired and set up a resin 3D printing and post-processing station, creating a new prototyping resource for students.
* **December 2024–December 2025: Historian, Tau Beta Pi** (engineering honor society), University of Miami
  * Conducted outreach to alumni and delivered monthly presentations sharing their experiences and professional advice with members.

Awards
======
* **Mechanical and Aerospace Engineering Junior Award**, awarded to the top four mechanical and aerospace engineering students
* **Brownell Award Nominee**, recognizing outstanding service to the College of Engineering
* **President's Honor Roll** (7 semesters), the highest scholastic distinction for a semester

Skills
======
* **CAD:** Creo Parametric, SolidWorks
* **Simulation and analysis:** COMSOL, Ansys, Abaqus, topology optimization
* **Programming:** Python, MATLAB, R, Arduino IDE, ROS2, Linux
* **Fabrication:** additive manufacturing (FDM, SLA), CAM, soldering, Ecoflex and hydrogel fabrication
* **Other software:** Blender (Geometry Nodes), 3D Slicer, Microsoft Office, MeshInspector
* **Languages:** Spanish (native), English (native), Mandarin (elementary)
