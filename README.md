# ANT.Gaussian
New version with implementations of SOC and spin rotations by Wynand Dednam
It also works both with intel and PGI compilers. No need to maintain two versions. Just set your enviroments variables.


ANT.G-2.5.2 is intended to contain the latest changes of Wynand and Palacios already in 2.5.0, now including the evaluation of the polarization. 

There is is a partially resolved issue. The density matrix with SOC was not symmetric. It was due to an incorrect evaluation of the spectral function. One has to be careful when Hamiltonians are not real. Now it is solved but integratating along the real axis. I cannot integrate the advanced Green's function 
