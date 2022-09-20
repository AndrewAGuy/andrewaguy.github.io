---
title: Bioengineering
---

# Bioengineering Applications

I am an expert in the design of vascular networks for tissue engineering: I maintain an [open-source library](/research/vascularization) for laying out vascular networks in arbitrary domains, and have years of experience using this to design networks for different manufacturing methods.
Services that I can provide include:
- Advice on compatibility/feasibility of manufacturing approaches (e.g. bio-ink printing, sacrificial templates + casting, photopolymerization/ablation) and cellularization strategies (e.g. casting, injection, channel-wall seeding).
- Design of vascular networks for a given geometry and manufacturing process, or complete design of combined perfusion chamber and vascular networks based on experimental needs.
- Analysis of sensitivity to manufacturing tolerances and vessel breakage.

<img src="https://i.postimg.cc/8ChPSr5L/3d-printable-interpenetrating-networks.png" width="75%"/>

### Small-scale
You may be looking to rapidly culture large quantities of structured tissue samples for:
- Personalized medicine
- Toxicity screening
- Fundamental research

In this case, networks can be generated to maximize either the supply efficiency (tissue volume per unit supply cost) or experimental monetary costs (a balance, depending on channel manufacturing costs and total pump running time).
Any number of networks can be embedded, so you can create glandular structures with disjoint drainage networks: the only limit is the resolution of your manufacturing process!

### Large-scale
If you are a startup looking to create replacement organs or large static cultures (e.g. cultured meat that isn't just mince), the vascular networks will be a key component of your design.
My software has been designed with tissue engineering in mind, and is able to account for manufacturing constraints that are not present in the biological models.
It can be used for all kinds of workflows:
- Design any number of interpenetrating networks in arbitrary domains, with organ-specific structure enforced and the ability to insert functional structures between the terminal arterioles/venules.
- Start from root vessels reconstructed from scan data, then fill in the rest of the organ.
- Simple features, scaled up: designing small chunks to be patterned, optimizing node placements for a fixed topology, resolving inter-network collisions.

At this scale you may need custom software tailored to your workflow, such as importing data, inspecting the output and directly interfacing to your printers.
You're more than welcome to use my software to do this---it's free and open-source---but if you want rapid results or cannot spare the engineer hours, get in touch for a consultation.
