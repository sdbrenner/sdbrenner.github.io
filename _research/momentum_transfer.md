---
title: "Momentum transfer across the atmosphere-ice-ocean interface"
layout: page
actions:   
  - label: "back to research page"
    icon: arrow-left
    url: "/research/"
thumbnail: /assets/images/1D_momentum_balance.png    
# date: 01-06-2019    
---

In polar oceans, sea ice mediates air-sea exchanges of momentum and energy.
While it is easy to think that the sea ice isolates the water column from direct wind forcing, the highly dynamic nature of sea ice makes this a more complex system to understand.
This comlexity was the focus of my PhD work, with my dissertation: "[The role of sea ice in mediating atmosphere-ice-ocean momentum transfer](https://digital.lib.washington.edu:443/researchworks/handle/1773/49108)".


Using a set of mooring measurements in the Beaufort Sea as part of the [SODA project](http://www.apl.washington.edu/soda){:target="blank"}, I have investigated a range of topics related to ice-ocean momentum transfer, including [sea ice roughness](#roughness); [inertial oscillation strength](#inertial_oscillations); and [surface waves](#waves) in the marginal ice zone.


These questions continue to be a central focus for ongoing research — including how velocity constraints due to [floe-scale effects](/research/floe_scale/) further impact the transfers of momentum and energy across the  atmosphere-ice-ocean boundary.


#### Sea ice roughness
{: #roughness}


Calculation of surface momentum fluxes across the atmosphere-ice and ice-ocean interfaces typically uses bulk drag laws, that include a turbulent transer coefficient—or "drag coefficient".
The value off this drag coefficient depends on the surface roughness.
Sea ice is geometry is characterized by discrete roughness elements (i.e., ice sails and keels).
The drag coefficient can be parameterized as a combination of skin drag on the level ice (depending on micro-scale roughness) and form drag on these larger roughness elements.

Making use of data from the SODA mooriongs, I compared in situ values of parameters describing ice-ocean drag with those calculated from an ice geometry-based parameterization scheme (see [fig. 1](#fig1))
By analyzing why mismatches occurred, I made recommendations for future iterations of the scheme—which primarily revolved around improving parameterizations of subgrid sea ice geometry, such as floe size distributions ([Brenner et al., 2021](#Brenner2021)). 

I am interested in extending these results to other study regions and timeframes using extant mooring records.

<figure class="align-center" style="max-width:75%">
  <img src="">
  <figcaption>fig.  
    (Reproduced from 
    <a href="#Brenner2021"> 
      Brenner et al., 2021
    </a>):
    words words words
  </figcaption> 
</figure>{: #fig1}


The increasing seasonality of Arctic sea ice, and shift to a higher proportion of ``smoother'' first-year ice is leading to a shift to a more "slippery" boundary layer, and more mobile sea ice.
Through the use of emerging remote sensing products (such as ice roughness measurements from [IceSAT-2](https://icesat-2.gsfc.nasa.gov/)) and numerical model outputs, ongoing work is considering the the varying contributions of drag coefficient changes and ice mechanical weaking in observed increased trends of ice velocity.



#### Inertial oscillations
{: #inertial_oscillations}

Inertial oscillations are rotational motions of the mixed layer that are a natural resonant response to wind forcing.
These oscillations also provide a pathway for energy to be transfered from the atmosphere into the ocean interior, through the generation of near-inertial waves.
Seaonal variability in the strength of the inertial response in the Arctic provides evidence for the damping of inertial oscillations by sea ice.


Due to their fairly simple physics, mixed-layer inertial oscillations provide an ideal test case for the potential of sea ice to impede the transfer of momentum and energy from the wind.
Using a simplified, one-dimensional, coupled ice-ocean slab model (schematized in [fig. 2](#fig2)), some of my PhD work explored these relationships, and noted that mechanical weaking of the sea ice is permitting greater stress transfer to the ocean—even in the midwinter ice pack ([Brenner et al., 2023](#Brenner2023)).
However, these effects are timescale-dependent: while ice damped high-frequency motion (like inertial oscillations), there is evidence that the low-frequency "Ekman transport" is minimally impacted by the presence of sea ice.

<figure class="align-center" style="max-width:70%">
  <img src="/assets/images/1D_momentum_balance.png">
  <figcaption>fig. 2: schematic of 1D ice-ocean momentum transfer
  </figcaption> 
</figure>{: #fig2}




#### Surface gravity waves
{: #waves}

In the open ocean, atmosphere-ocean momentum transfer is mediated by surface gravity waves. 
Within the marginal ice zone (MIZ), that is disrupted as the ice damps the waves.
Wave-ice interactions are a subject of much active research within the community.

With the SODA mooring array we also made measurements of surface waves, which Cooper ([2022](#Cooper2022)) compared to model results to test existing model parameterizations of wave damping by ice. 
The wave characteristics measured by the moorings showed a preponderance small, locally generated waves can existing within leads and gaps between sea ice flows—even up to 100 km within the sea ice edge. 
These local waves were absent from model results using standard parameterizations, but may be an important part of sea ice evolution.
As waves provide surface roughness in the open ocean, these results are also important to bulk calculations of net atmosphere-ocean momentum flux.

I continue to be interested in interactions between sea ice and surface gravity waves.
In particular, I wonder how the combination of locally generated waves and ice-attenuated swell might impact ice-ocean momentum/energy fluxes in the marginal ice zone, and how to acount for those effects in "flux-averaging" methods of surface stress calculation. 




#### Related publications

* {: #Brenner2023}**Brenner, S.**, Rainville, L., Thomson, J., Crews, L., and Lee, C., 2023. Wind-driven motions of sea ice and the ocean surface mixed layer in the Western Arctic. J. Phys. Oceanogr., 53(7), 1787–1804. [doi:10.1175/JPO-D-22-0112.1](http://doi.org/10.1175/JPO-D-22-0112.1){:target="blank"}.

* {: #Cooper2022}Cooper, V., Roach, L., Thomson, J., **Brenner S.**, Smith, M., Meylan, M., Bitz, C., 2022. Wind waves in sea ice of the western Arctic and a global coupled wave-ice model. Phil. Trans. Roy. Soc. A., 380(2235), p. 19. [doi:10.1098/rsta.2021.0258](http://doi.org/10.1098/rsta.2021.0258){:target="blank"}.

* {: #Brenner2021}**Brenner, S.**, Rainville, L., Thomson, J. Cole, S. and Lee, C., 2021. Comparing observations and parameterizations of ice-ocean drag through an annual cycle across the Beaufort Sea. J. Geophys. Res. Oceans. [doi:10.1029/2020JC016977](http://doi.org/10.1029/2020JC016977){:target="blank"}

