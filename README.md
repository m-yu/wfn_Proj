wfn_Proj
========

This analysis is applied to understand the hybridization of isolated molecule orbitals upon adsorbing on semiconductor surfaces.

- Theory background
  - The combined interface system include molecule and semiconductor substrate.
  - The isolated molecule's Hamiltonian is H_mol, with wavefunctions \phi^mol_i.
		 	H_mol \phi^mol_i = E^mol_i \phi^mol_i
  - The combined system Hamiltonian is H_c, with wavefunctions \phi^c_nk
	 		H_c \phi^c_nk = E^c_i \phi^c_nk

  - We perform analysis on wavefuncitons in the planewave basis extracted from either Paratec or QEspresso simulation.

- Analyzation
  - Projected density of states(PDOS) of adsorption system on isolated molecular eigenstates
    \Sum_nk |<\phi^c_nk|\phi^mol_i>|^2 \delta(E-E_nk)
    

Example: J. Phys. Chem. Lett. 4, 1701 (2013). Fig 2
