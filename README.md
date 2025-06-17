# A phase-field model for thermo-mechanical fracture

In this article, we propose a thermodynamically consistent phase-field model for thermo-mechanical fracture and provide an open-source implementation of the proposed model using
a recently developed finite element toolbox, Gridap in Julia. Here, we have derived the balance equations for the thermo-mechanical fracture by invoking the virtual power principle 
and determined the constitutive relations for the thermodynamic fluxes based on the satisfaction of the thermodynamic laws. Our proposed formulation provides an equation of temperature
evolution that can easily accommodate dissipative effects such as viscous damping. We provide very compact and user-friendly open-source codes for implementing the proposed model using
Gridap in Julia that requires very low memory usage and gives a high degree of flexibility to the users in defining weak forms of the governing partial differential equations (PDEs). 
We have validated the proposed model and its implementation against such standard results available in the literature as crack propagation in the cruciform shape material, single edge 
notched plate, bi-material beam, and a quenching test.

# See the details using the link below: 

https://journals.sagepub.com/doi/abs/10.1177/10812865221085198

# Cite this article:

@article{prakash2023phase,
  title={A phase-field model for thermo-mechanical fracture},
  author={Prakash, Ved and Behera, Akash Kumar and Rahaman, Mohammad Masiur},
  journal={Mathematics and Mechanics of Solids},
  volume={28},
  number={2},
  pages={533--561},
  year={2023},
  publisher={SAGE Publications Sage UK: London, England}
}
