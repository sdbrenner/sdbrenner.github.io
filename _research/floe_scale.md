---
title: "Floe-scale variablility in sea ice-ocean coupling"
layout: page
actions:   
  - label: "back to research page"
    icon: arrow-left
    url: "/research/"   
# thumbnail: /assets/images/floe_scale_turbulence.png    
# date: 01-07-2022
---

<div class="embed-responsive embed-responsive-16by9">
  <iframe width="640" height="360" src="https://www.youtube.com/embed/UBqMkirHENs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div> {: #floedyn_video}
Within the marginal ice zone (MIZ), sea ice is comprised of a mosaic of individual floes that span a wide range of horizontal scales—from meters to tens of kilometers across. 

However, when considering air-sea coupling at climate model scales, the role of sea ice variability is typically collapsed to a single metric: the sea ice concentration. 
As a result, the spatial heterogeniety in surface properities that is an inherent feature of the floe-covered MIZ is not resolved or accounted for. 
Yet, there is an increasing awareness that sea ice melt rates and atmosphere/ocean boundary layer dynamics are impacted by floe-scale effects.

Explicitly representing sea ice floes—rather than treating the ice cover as a continuum—introduces a range of new physical effects, as floe-scale features imprint on upper-ocean dynamics.
For example, because individual floes move as rigid bodies, their motion is subject to geometric and dynamical constraints that differ from continuum behaviour.
Because ice-ocean fluxes are driven by differences between sea ice and ocean velocity, these velocity constraints can impact the [transfers of momentum](/research/momentum_transfer) and energy across the atmosphere-ice-ocean boundary in a way that depends on the relative horizontal scales of floes and the scales of ocean variablity ([fig. 1](#fig1)).


<figure class="align-center">
  <img src="/assets/images/floe_scale_turbulence.png">
  <figcaption>fig. 1 
    (Reproduced from 
    <a href="#Brenner2023"> 
      Brenner et al., 2023
    </a>):
    A schematic showing how scale mismatches between ocean flow (blue colourmap and background vectors) and ice velocity (vector arrows over ice floes) contribute to boundary-layer turbulent production (cyan/red colourmap).
  </figcaption> 
</figure>{: #fig1}


During my postdoctoral work at Brown University, I made use of a high-resolution, discrete element model (DEM) of sea ice that explicitly resolves individual sea ice floes ([see video](#floedyn_video)) in order to investigate the joint roles of *floe-floe interactions* and *flow-floe interactions* in mediating ice-ocean exchanges ([Brenner et al., 2023](#Brenner2023)).
I also considered the role of individual ice floes in a surface-gravity-wave model to understand geometric constraints on local wave growth ([Brenner & Horvat, 2024](#Brenner2024)).

My ongoing postdoctoral work at Caltech continues investigating these effects using a combination of methods, including a sea ice DEM coupled to an ocean large-eddy-simulation (LES) model in order to understand how sea ice floe scales imprint on the scales associated with the underlying dynamics associated with energy transfers in the upper ocean.
In coupled ice-ocean simulations, FSDs that include larger floes generate stronger and more energetic eddies and filaments, even for identical total sea ice coverage ([fig. 2](#fig2)).
We see that the patterns of sea ice cover mediate the strength of large-scale ocean turbulence, with 
explicit representation of sea ice floes both energizing and damping ocean mesoscale and submesoscale dynamics ([Brenner et al., *in review*](#BrennerInReview)).


<figure class="align-center">
  <img src="/assets/images/three_dim_output.png">
  <figcaption>fig. 2 
    (Reproduced from 
    <a href="#BrennerInReview"> 
      Brenner et al., *in review*
    </a>):
    Upper-ocean sub/mesoscale turbulence in floe-resolving ice-ocean coupled model simulations of the MIZ for (a) an FSD with large maximum floe size, and (b) an FSD with small maximum floe size.
  </figcaption> 
</figure>{: #fig2}



#### Related publications

* {: #BrennerInReview}**Brenner, S.**, Thompson, A., Gupta, M. [*In review*]. Patterns of sea ice floes shape ocean turbulence in the marginal ice zone. [Preprint doi:10.21203/rs.3.rs-8099873/v1](https://doi.org/10.21203/rs.3.rs-8099873/v1){:target="blank"}.


* {: #Brenner2024}**Brenner, S.**, Horvat, C., 2024. Scaling simulations of local wind-waves amid sea ice floes. J. Geophys. Res. Oceans., 129, e2024JC021629. [doi:10.1029/2024JC021629](https://doi.org/10.1029/2024JC021629){:target="blank"}. 

* {: #Brenner2023}**Brenner, S.**, Horvat, C., Hall, P., Lo Piccolo, A., Fox-Kemper, B. Labbé, S., Dansereau, V. 2023.
Scale-dependent air-sea exchange in the polar oceans: floe-floe and floe-flow coupling in the generation of ice-ocean boundary layer turbulence. Geophys. Res. Lett., 50, e2023GL105703. [doi:10.1029/2023GL105703](https://doi.org/10.1029/2023GL105703){:target="blank"}.

<!-- Changes in Arctic sea ice are especially pronounced by the expansion of MIZs; however, these transition regions remain poorly understood. -->