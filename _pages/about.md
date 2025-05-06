---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**PhD in Bioengineering**

I obtained my PhD in Bioengineering at Stanford University,co-advised by [Prof. Michael Lin](https://linlab.stanford.edu/) and [Prof. Tom Clandinin](https://flyvisionlab.weebly.com/), focusing on developing new methods for revealing neuronal dynamics across spatialtemporal scales and understanding neuronal signal processing.

**BS in Mechanics**

From 2014 to 2018, I got my Bachelor's degree in mechanics and applied math from Tsinghua University. This provided me with a solid foundation in mathematics and physics.

## Research Experience

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <div style="flex: 1; margin-right: 20px;">
    <img src="/images/paper1.jpg" alt="Research Diagram" style="width: 100%; border: 1px solid #ddd; border-radius: 4px;" />
  </div>
  <div style="flex: 1.5;">
    <p>
      <h3>Do real neurons process information similarly to 'neurons' in artificial neural nets? </h3>
       To answer questions like this, I developed a protein—a nanoscale, two-state light bulb—to transduce electrical signals into optical signals for extracting neuronal voltage dynamics at multiple spatiotemporal scales. And when we expressed it in neurons in vitro and in vivo, we were able to see voltage signals flowing on neuronal surfaces, ranging from 1 mV to 100 mV. Here this figure visualizes an interesting fact: voltage signals decay exponentially as they trave from dendritic tree to soma (in a passive neuron). This decay induces an effective weight to the input signals, and it also suggests that there may be local nonlinear signal amplification to componsate for the passive signal decay. A next step would be applying this protein in model animals to visualize how active neurons compensate for the passive signal decay and process signals.
      This research extend the applications of voltage imaging to the quantal response domain, including in human neurons, opening up the possibility of high-throughput, high-content characterization of neuronal dynamics in healthy brains and disease models.
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <div style="flex: 1; margin-right: 20px;">
    <img src="/images/paper1.jpg" alt="Research Diagram" style="width: 100%; border: 1px solid #ddd; border-radius: 4px;" />
  </div>
  <div style="flex: 1.5;">
    <p>
      <h3>How do we integrate functional imaging datasets across labs and with ex-vivo resources? </h3>
      We developed BIFROST, a computation pipeline for bringing functional datasets into a common space with iterative image registration. Image registration can be hard, especially when recordings are from different modalities or different preparations. To make it easier, we made a couple intermediate templates (similar to the idea of simulated annealing) to gradually bridging the recordings from its original image space to a desired image space. We optimized the combination of linear and nonlinear registration methods to achieve best performance on the fruit fly datasets. Importantly, to eliminate the local distortion artifacts caused by the machine-learning based registration (which is not bounded), I approximated the ML-generated transformation by iterative bounded SyN transformation. Our final pipeline achieved ~ 5um accuracy in the fruit fly brain datasets. An obvious next goal is to verify this method with datasets from other model animals.
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <div style="flex: 1; margin-right: 20px;">
    <img src="/images/paper1.jpg" alt="Research Diagram" style="width: 100%; border: 1px solid #ddd; border-radius: 4px;" />
  </div>
  <div style="flex: 1.5;">
    <p>
      <h3>How to put the control knobs on a linear network for less control cost?</h3>
      We described and analyzed a linear quadratic control problem with selective input matrix (designable control knobs). We derived the formula for gradients, discussed the convexity of the problem using its energy variation, and proposed algorithms for optimization under several constraints. Numerical experiments are performed. 
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <div style="flex: 1; margin-right: 20px;">
    <img src="/images/paper1.jpg" alt="Research Diagram" style="width: 100%; border: 1px solid #ddd; border-radius: 4px;" />
  </div>
  <div style="flex: 1.5;">
    <p>
      <h3>Why do your clothes have wrinkles? And what regulates them? Scaling law for wrinkles?</h3>
      A more foundamental question is how do thin layers of homogenous materials deform? My undergrad thesis provided a potential way to estimate: by combining geometry, perturbation and variational methods. We noticed (at least) two modes of deformation for 2D thin layers: one without changing its Gaussian curvature, like reflection, and one changing its Gaussian curvature, like wrinkling. By Gauss' Theorema Egregium, the first may not cause in-plane deformation while the second one will. So for a thickless 2D surface, the first mode of deformation may not cause any change of deformation energy. Therefore, by the minimal-energy principle, the 2D surface tend to maintain its Gaussian curvature during deforming to minimize energy at the zero-thickness limit, and the deformation is piece-wise reflection or infinite wrinkle-field. However, when there is thickness, it prefers smooth deformation and sharp deformation would blow up the energy, thus the sharp boundaries of reflection or wrinkle-field will become smooth boundaries or finite wrinkles with certain wavelength. The wrinkles can be described by a scaling law with respect to the thickness. Along this line I published a few papers that describes the scaling laws of such deformations, and a novel wrinkle-unwrinkle transition.
    </p>
  </div>
</div>


## Ad-hoc 
- Co-organizer of [MBCT seminar series](https://neuroscience.stanford.edu/programs/community-building/seminar-series-wu-tsai-neuro/mind-brain-computation-and-technology-mbct-seminar-series) from 2022 to 2023.

- Designed [Litsurf](https://github.com/AlexYkHao/litsurf_backend), a web app that finds the most relevant content from a list of content sources for a user based on their profiles, allowing researchers to discover relevant publications they might otherwise miss using traditional keyword searches. Feel free to use it in my github repository.
  

