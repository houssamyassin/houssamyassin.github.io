---
layout: page
title: Research
permalink: /research/
image: /images/sshstd.png
---

# Research

## Current work

As part of the [Ocean Transport and Eddy Energy Climate Process Team](https://ocean-eddy-cpt.github.io), I am working on two projects aimed at improving our understanding of ocean turbulence and its representation in ocean models.

My first project is on improving the representation of mesoscale eddies in the 1/4° configuration of the ocean component of the [Community Earth System Model (CESM)](https://www.cesm.ucar.edu). Mesoscale ocean eddies, which can be thought of as being the ‘weather’ of the ocean, are either inadequately resolved by the model or are strongly dissipated by the artificially high viscosities imposed to maintain numerical stability. One way of addressing this deficiency is through recently proposed 'backscatter' schemes, which have been designed to reintroduce kinetic energy back into the resolved ocean circulation. The primary aim of this project is to compare the various previously proposed backscatter schemes in a realistic model and identify the optimal eddy parameterization to enhance the fidelity of the 1/4° configuration of the ocean component of CESM.

<p align="center">
  <img src="{{ page.image | relative_url }}" alt="Relative difference in SSH standard deviation between AVISO and model.">
</p>

My second project is on understanding the seasonal cycle of geostrophic turbulence in the ocean. Recent observations and high-resolutions numerical simulations have shown that upper ocean geostrophic turbulence experiences a strong seasonal cycle, following the seasonal cycle of mixed-layer depth. However, the underlying dynamics behind this seasonality remains poorly understood. For this project, I have derived an extension of the [quasigeostrophic model](https://en.wikipedia.org/wiki/Quasi-geostrophic_equations) that allows for time-dependent stratification. With this new model, we are able to evaluate two mechanisms that we hypothesize to contribute to the seasonal cycle:
1. the seasonal injection of kinetic energy into the mixed-layer from mixed-layer instability
2. the modulation of nonlinear eddy interactions by changes in mixed layer depth, which acts to redistribute energy across horizontal scale.

Our approach aims to identify the essential dynamics necessary for developing improved subgrid-scale parameterizations for climate models, enabling a more accurate representation of the ocean mesoscale seasonal cycle.

## Past work

Much of my PhD was on a [quasi-2D turbulence regime](https://doi.org/10.1175/JPO-D-22-0040.1) that is relevant for rotating stratified fluids (e.g., planetary atmospheres or oceans). I created a new theoretical model for this class of turbulence and I developed a theory for how energy is distributed across spatial scales. In addition, I used this new model to investigate the formation of [anisotropic structures](https://doi.org/10.1017/jfm.2023.318) arising from the interaction of waves with turbulence. This work is likely to be relevant for the upcoming [SWOT satellite](https://en.wikipedia.org/wiki/Surface_Water_and_Ocean_Topography) mission which will provide data on upper ocean turbulence at unprecedented length scales. More details can be found [here](/research/sqg).

I also have more technical work on the [Fourier analysis of geophysical waves](https://doi.org/10.1063/5.0048273). This work describes the mathematical properties of Fourier expansions for systems for dynamically-active boundaries. Such systems are common in geophysical fluids (e.g., surface gravity waves, [Rossby edge waves](https://doi.org/10.1175/JPO-D-21-0199.1), capillary waves).

Finally, I have also worked on the [transport](https://doi.org/10.1017/jfm.2019.30) induced by [internal gravity waves](https://doi.org/10.1017/jfm.2022.690). This transport is analogous to the [Stokes drift](https://en.wikipedia.org/wiki/Stokes_drift) induced by surface gravity waves, but occurs throughout the volume of the fluid.

<center>
    <video autoplay="autoplay" loop="loop" muted defaultMuted playsinline  oncontextmenu="return false;"  preload="auto" width="65%" height="auto">
          <source src="/videos/alpha05_J42_s1.mp4" type="video/mp4">
    </video>
</center> 