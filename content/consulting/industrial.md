---
title: Industrial
---

# Industrial Applications
_I have recently established some academic collaborations to apply my vascularization software to industrial problems --- hopefully I will have some results to share soon!_

**Who is this for?**

You are probably a good fit for bio-inspired distribution networks if:
- You are obsessed with maximizing the efficiency of your reactors.
- You are using precision manufacturing methods to create highly specialized, custom components.

**You will need:**

- Knowledge of the microscale at which the reaction occurs: length scales, flow rates etc. or a pre-designed micro-reactor which you want to connect.
- The geometry of the volume you wish to serve, and an idea of how this should connect to the outside world.

### Reactions in Porous Media
Many processes involve the filtration of a reagent through a porous medium, which may act as a catalyst or a filter.
As the reaction occurs on the surface of the porous material, the marginal gain of extending the thickness decreases (as reactants are used up), whilst the marginal cost of pumping the fluid through the medium remains constant (assuming Darcy flow).
Eventually, it becomes infeasible to extend the thickness of the porous medium.

Fortunately, nature has solved this problem for us: split the design into two parts!
- **Microscale.** Where the reaction occurs: optimize this by simulation/experiments to create a unit cell.
- **Macroscale.** Channel networks which distribute fluid to the microscale.
We lose volume that could be used for reactions, but make far greater gains in the reduced power consumption required to distribute fluid into the remaining volume.

If you can provide the details of the microscale, my software can be used to generate the distribution networks, optimized for your choice of cost.

### Distributed Reactors / Heat Exchangers / Mixers
Some reactions cannot be scaled up due to the sheer amount of energy released, and can only be performed safely in small vessels, which may also require cooling.
Other reactors, such as microfluidic mixers, cannot scale on their own and must be distributed throughout a target volume.

My software can be used to automatically lay out arbitrary numbers of networks, enabling the compact design of distributed reaction chambers in a target volume, including disjoint networks of heat exchangers.
