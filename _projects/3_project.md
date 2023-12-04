---
layout: page
title: polymer
description: molecular dynamics of photodegradation of polymeric chains
img: assets/img/polymer.jpg
importance: 3
category: work
giscus_comments: false
---


Pressure has grown for industrial members to produce chemicals and materials following green chemistry guidelines due to increasing environmental impacts, public interest, and regulatory policies. One strategy is upcycling with the closed-loop methodology to recycle materials and prevent them being disposed into waste facilities. Biomass, specifically fructose, has been highlighted as a carbon source replacement of fossil fuels due to its availability, extensive opportunities for development of chemical compounds, and reusability. To further comply with green chemistry principles, one can combine renewable biomass with upcycling to form a biorenewable closed system for the development of recoverable and reusable materials with reducing reliance on fossil fuels. Experimental studies have shown that 2,5-furandicarboxylic acid (FDCA) can be recovered for recycling when incorporated as building blocks into photodegradable polymeric systems. It has the potential to build plastics that are synthetic or biobased, recyclable, and photodegradable in natural environments. In this project, we conduct detailed studies on the mechanism and related sequence of reaction steps and microscopic structures involved in the photodegradation.

<ul>
<li><b>Photodegradation of polymeric chains</b>: We use time-dependent excited-state molecular dynamics (TDESMD) method to simulate how polymeric chains made from FDCA and nitrobenzyl chromophore break down under light exposure.</li>
<li><b>TDESMD algorithm</b>: The implementation rests on the combination of Rabi theory and surface hopping approximation. In the TDESMD algorithm, a molecule experiences cyclic excitations and de-excitations between the ground state and excited state to model the perturbation of molecules by light. The TDESMD method has been used to explore photoreactions for a range of materials.</li>
<li><b>Vacuum and aqueous environments</b>: We find a similar trend of photodegradation pathways for trajectories in vacuum and aqueous environments: nitro groups are labile, and the backbone chain typically breaks between the C–O bond of the alkoxy group in the linker. Molecules similar to nitrobenzene and furan are frequently observed at early stages of computed trajectories. At later stages, smaller fragments with lighter molecular weights are found, due to the accumulation of thermal energy. TDESMD trajectories in the vacuum phase show a higher degree of degradation than those in the aqueous phase. Following the breaking of polymeric chains, one observes the degradation of the FDCA backbone in the vacuum trajectory, whereas a FDCA molecule is formed and remains intact in the aqueous trajectory. our results indicate that proton transfers involving polymeric derivatives and surrounding solvent molecules are essential for the recovery of FDCA monomers.</li>
</ul>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/polymer-fig.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
</div>
<div class="caption">
    <b>(a)</b>: Density of states. <b>(b)</b>: Calculated absorption spectra. Insets: partial charge densities for frontier orbitals of optimized structures in vacuum and aqueous environments. <b>(c)</b>: Computed mass spectra from TDESMD trajecories.
</div>

Reference:

M. Erickson, Y. Han, B. Rasulev, D. Kilin. Molecular Dynamics Study of the Photodegradation of Polymeric Chains. <a href='https://doi.org/10.1021/acs.jpclett.2c00802'>J. Phys. Chem. Lett. 2022, 13, 19, 4374-4380.</a>





