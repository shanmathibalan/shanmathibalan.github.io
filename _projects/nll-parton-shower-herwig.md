---
layout: page
title: NLL Accurate Showers in Herwig
img: assets/img/lhc.jpg
importance: 2
permalink: /projects/nll-parton-shower-herwig/
---

We are quickly approaching the next stages of particle physics research. With the [High-Luminosity LHC](https://home.cern/science/accelerators/high-luminosity-lhc) coming soon and with the potential of the [Future Circular Collider](https://home.cern/science/accelerators/future-circular-collider), we expect to see high-energy collisions at very high precision. To keep up with these experiments, we need to make sure our event generators are also precise enough.

Whilst research groups are continous improving the hard scattering accuracy, generator and resummation communities are working on improving the accuracy of parton showers. At this stage (2025), we have a good few models of Next-to-Leading-Log accurate showers [[PanLocal and PanGlobal](https://gsalam.web.cern.ch/panscales/), [FHP](https://arxiv.org/abs/2003.06400), [Alaric](https://arxiv.org/abs/2404.14360), [Apollo](https://arxiv.org/abs/2403.19452)], with some attempts towards Next-to-Next-to-Leading-Log accurate showers.

The aim of this project is to implement the PanGlobal and FHP Models into [Herwig](https://herwig.hepforge.org/), alongside the current Catani-Seymour Shower. Some preliminary results are shown below. Once our paper is out, I'll fill this more, but for now, please see our latest talk

[NLL Showers in Herwig - LHC Monte Carlo Working Group, October 2025](https://indico.cern.ch/event/1553687/contributions/6702923/)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/thr.jpg" title="Thrust" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/y23.jpg" title="Durham y23" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Thrust and the Durham $y_{23}$ Observables. Made from LEP Simulations at NLO with cluster hadronisation.
</div>
