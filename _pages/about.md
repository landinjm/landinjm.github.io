---
permalink: /
title: "Hi!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Jason, a PhD student at the University of Michigan, Ann Arbor. I primarily work in phase-field
modeling, but have a interest in scientific computing. Here's some of the codes I
contribute to/develop.

[PRISMS-PF](https://github.com/prisms-center/phaseField) - This is a high-level phase-field library that handles most all of the considerations for finite element discretizations of phase-field partial differential equations (PDEs). All users have to do is write their PDEs and select appropriate parameters! The developers do all the hard work of validating the code and optimzing it. I got heavily involved in this project around 2024 and ended up rewriting most of the existing code.

[pagoma](https://github.com/landinjm/pagoma) - This is a little pet project of mine! I started it to get familiar with GPU programming in deal.II (the FEM library PRISMS-PF uses). Since it's from scratch and there are no users to speak of, I get to try a lot of stuff that isn't possible in PRISMS-PF!

[Varis.jl](https://github.com/ocellifera/Varis.jl) - This is a little symbolic algebra package that I've been developing to avoid having to do hand derivations for higher order time discretizations for the Incompressible Navier-Stokes equations and coupling them with dendrite growth. 

[IPAM-PoissonBoltzmann](https://github.com/IPAM-ECH2025/PoissonBoltzmannIPAM2025) - This is ongoing work at IPAM-ECH 2025. I'll more on this later.
