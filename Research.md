---
layout: page
title: Research
permalink: /research/
---

# Research


### Geostrophic turbulence

I study geostrophic turbulence---the slowly evolving, large-scale turbulence in the atmosphere and ocean that is modified by Earth's rotation. Questions that I am interested in include:

- How does the fluid's density stratification impact the resulting turbulence? 
- What is the relationship between the vertical structure of geostrophic turbulence and the distribution of energy across horizontal scales? 

Answering these questions is important for understanding the physics of upper ocean turbulence at horizontal scales of 1-100 km. Turbulence at these horizontal scales is critical for the exchange of heat, carbon, and oxygen between the ocean and atmosphere, and may be important for Earth's climate. However, this turbulence occurs at length scales that are too small to be resolved in global climate models.

### The turbulence of surface buoyancy anomalies

My PhD dissertation answers the above two questions in the case that geostrophic turbulence is due to buoyancy anomalies at the ocean's surface. By surface buoyancy anomalies, I mean areas of the surface ocean that are either lighter or denser than its surroundings. When these surface buoyancy anomalies are sufficiently wide, they result in geostrophic currents in the upper ocean. 

The theory for such flows is developed in [Blumen (1978)](https://doi.org/10.1175/1520-0469(1978)035<0774:UPVFPI>2.0.CO;2) and [Held et al. (1995)](https://doi.org/10.1017/S0022112095000012). *However, this theory assumes that the density stratification does not change with depth*. The following animation shows what this turbulence looks like. This animation shows the buoyancy anomaly at the ocean's surface in a 400 km by 400 km [`pyqg`](https://github.com/pyqg/pyqg) simulation. Red areas indicate lighter fluid whereas blue areas indicate denser fluid.
<center>
    <video autoplay="autoplay" loop="loop" muted defaultMuted playsinline  oncontextmenu="return false;"  preload="auto" width="65%" height="auto">
          <source src="/videos/SQG_kf4_s1.mp4" type="video/mp4">
    </video>
</center>


However the ocean does not have a constant density stratification. Indeed, the ocean's density stratification is not only depth-dependent but seasonal as well. As a consequence, the theory developed in [Blumen (1978)](https://doi.org/10.1175/1520-0469(1978)035<0774:UPVFPI>2.0.CO;2) and [Held et al. (1995)](https://doi.org/10.1017/S0022112095000012) is only relevant at horizontal scales smaller than 10 km in the mid-latitude open ocean. At larger scales, the ocean's density stratification must be taken into account. In my dissertation, I generalize the theory to account for vertically variable density stratification. The resulting difference between summertime and wintertime turbulence is striking. 

In summer, the turbulence is diffuse and highly local in space:
<center>
    <video autoplay="autoplay" loop="loop" muted defaultMuted playsinline  oncontextmenu="return false;"  preload="auto" width="65%" height="auto">
          <source src="/videos/jul_scaled_ss1.mp4" type="video/mp4">
    </video>
</center> 

However, in winter, the turbulence is full of both large and small vortices, and large-scale strain is evident:
<center>
    <video autoplay="autoplay" loop="loop" muted defaultMuted playsinline  oncontextmenu="return false;"  preload="auto" width="65%" height="auto">
          <source src="/videos/jan_ss1.mp4" type="video/mp4">
    </video>
</center> 

Thus, the dynamics of buoyancy anomalies at the ocean's surface are inherently seasonal due to the seasonality in upper ocean density stratification. This seasonality implies a seasonality in the vertical velocity, the dispersion of tracers, and in the distribution of kinetic energy across horizontal scales.