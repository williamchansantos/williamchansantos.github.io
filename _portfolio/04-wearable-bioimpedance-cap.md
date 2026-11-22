---
title: "Wearable Bioimpedance Cap and Multi-layered Head Phantom"
excerpt: "Avila Research Group, Rice University · May–August 2026<br/>A wearable cap for monitoring brain hydration in older adults, with a finite element head model and an anatomically accurate tissue-mimicking phantom for validation.<br/><img src='/images/portfolio/bioimpedance/phantom-measurement.jpg' alt='Bioimpedance cap measuring a head phantom' style='max-width:420px;width:100%;margin-top:0.5em'>"
collection: portfolio
permalink: /portfolio/wearable-bioimpedance-cap/
---

**Avila Research Group, Rice University** · Researcher · May–August 2026

<figure>
  <img src="/images/portfolio/bioimpedance/phantom-measurement.jpg" alt="Bioimpedance cap on an agar head phantom" style="max-width:640px">
  <figcaption>The cap measuring an agar head phantom, with Ag/AgCl electrodes connected to the impedance analyzer.</figcaption>
</figure>

* **Wearable device:** developed a bioimpedance cap for monitoring brain hydration in older adults, integrating an analog front end and a tetrapolar electrode array for benchtop and human testing.
* **Simulation:** built a multi-layered finite element human head model in COMSOL with frequency-dependent material properties to optimize stimulation frequency and electrode montage location.
* **Validation phantom:** designed and fabricated a tissue-mimicking, multi-layered head phantom with anatomically accurate geometry and layer conductivities, using node-based parametric modeling in Blender.
* **Deformation study:** characterized bioimpedance signal behavior under mechanical deformation on hydrogel substrates, and wrote a Python computer-vision pipeline (OpenCV, NumPy) using HSV color segmentation and contour centroid tracking to automate electrode-displacement monitoring.


<figure>
  <img src="/images/portfolio/bioimpedance/sensing-concept.png" alt="Tetrapolar bioimpedance sensing concept">
  <figcaption>Sensing concept: a tetrapolar electrode array injects current through the outer electrodes and senses voltage across the inner pair.</figcaption>
</figure>

<figure>
  <img src="/images/portfolio/bioimpedance/head-model-phantom.jpg" alt="Blender head model and physical phantom layers" style="max-width:560px">
  <figcaption>Multi-layered head model built in Blender (brain, skull, scalp) and the corresponding physical phantom layers.</figcaption>
</figure>

<figure>
  <img src="/images/portfolio/bioimpedance/frequency-sweep.png" alt="COMSOL frequency sweep results">
  <figcaption>COMSOL simulation: relative impedance change versus stimulation frequency for different electrode montages, used to select the operating frequency and montage.</figcaption>
</figure>

**Outputs:** poster at the [Rice Summer Research Symposium](/talks/2026-07-01-rice-bioimpedance-cap) (July 2026) and a co-authored [paper in the *ASME Journal of Applied Mechanics*](/publication/2026-10-01-bioimpedance-signals-under-deformation) (October 2026).
