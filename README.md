# energy-momentum-eqn-for-phonon-creation-annihilation
energy momentum eqn for phonon creation annihilation
equations used from book: 
Physics of Phonons by GP srivastava


In this code, we first define the lattice and reciprocal lattice vectors, as well as the momenta and frequencies of the two interacting phonons. For each type of event (class 1 or class 2), we then check whether it is an N-process or a U-process, and determine the momentum and frequency of the resulting phonon as well as the reciprocal lattice vector (if required).

Note that the omega function needs to be defined separately, and the lattice vectors a1, a2, and a3 need to be provided as input. Additionally, the reciprocal_lattice_vector function is used to determine the appropriate reciprocal lattice vector for a given momentum.
